### Overview
The [SiteWhere](http://www.sitewhere.org/) persistence provider allows openHAB data to be forwarded to a SiteWhere
server instance running locally or in the cloud. Selected events from an openHAB instance can be stored in SiteWhere
under a virtual device with hardware id specified in the persistence provider implementation. Events are
delivered via the SiteWhere agent which uses the MQTT protocol. The SiteWhere 
[administrative application](http://documentation.sitewhere.org/userguide/adminui/adminui.html) may be 
used to view data for the virtual device. It can also be used to issue commands to items in openHAB based
on the SiteWhere command framework. See [this tutorial](http://documentation.sitewhere.org/integration/openhab.html) 
for a step-by-step walkthrough.

### Configuring SiteWhere
Both SiteWhere and openHAB by default run on port 8080, so the port will need to be changed if both are running on the same machine. To change the port for SiteWhere, open the **conf/server.xml** file and look for the following:

```
<Connector port="8080" protocol="HTTP/1.1"
    connectionTimeout="20000"
    redirectPort="8443" />
```

Change the port to another value such as 9090.

No configuration is necessary for SiteWhere to listen for events on the MQTT transport if using the default
tenant configuration. The SiteWhere agent used by the persistence plugin is configured to send MQTT messages
on the topic where SiteWhere is listening.

## Configuring openHAB
The default values configured in the openHAB SiteWhere persistence plugin will work with no changes
if using the default SiteWhere tenant configuration. The default values are shown below:

```
############################ SiteWhere Persistence Service #############################
#
# Unique hardware id of device that will receive events.
# sitewhere:defaultHardwareId=123-OPENHAB-777908324
#
# Device specification token used if device is not already registered.
# sitewhere:specificationToken=5a95f3f2-96f0-47f9-b98d-f5c081d01948
#
# MQTT broker hostname SiteWhere is listening to. 
# sitewhere:mqttHost=localhost
#
# MQTT broker port SiteWhere is listening to. 
# sitewhere:mqttPort=1883
```
The following configuration values may be specified to change the default behavior:

* **defaultHardwareId** - provides an association between the openHAB instance and a SiteWhere device. 
Once connected, if no device exists in SiteWhere with the given hardware id, a new openHAB virtual device 
will be registered under that id. All data sent from the openHAB instance will be recorded under the virtual 
device. If more than one openHAB instance is connecting to SiteWhere, different hardware ids should be used 
for each instance. SiteWhere can scale to support thousands or even millions of openHAB instances running 
concurrently.
* **specificationToken** - indicates the device specification to be used if a new device needs to be registered 
with SiteWhere (if the hardware id does not exist). The default value corresponds to the *openHAB Virtual Device*
specification included with the SiteWhere sample data. This specification includes the device commands used
to trigger events on the openHAB bus from SiteWhere.
* **mqttHost** - the host name for the MQTT broker SiteWhere is listening to.
* **mqttPort** - the port number for the MQTT broker SiteWhere is listening to.
