Documentation of the Wemo binding bundle

## Introduction

This binding integrates the [Belkin WeMo Family](http://www.belkin.com/us/Products/c/home-automation/).
The integration happens either through the WeMo-Link bridge (feature still to come), which acts as an IP gateway to the ZigBee devices or through WiFi connection to standalone devices.

For installation of the binding, please see Wiki page [[Bindings]].

####The new channels for energy measurement of WeMo Insight devices are no available with openHAB Version 1.8

Wemo Binding needs no configuration in openhab.cfg


## Item Binding Configuration (Version 1.7)

In order to bind an item to the device, you need to provide configuration settings. The easiest way to do so is to add some binding information in your item file (in the folder configurations/items`). The syntax of the binding configuration strings accepted is the following:

    wemo="<friendlyName>"

The friendlyName is given to your device during initial setup with your Android or IOS device.
You can find the friendlyNames of your devices in your openhab.log. The discovered devices are listed.

Examples, how to configure your items in your items file:

    Switch WallFanOffice   {wemo="WemoFanOffice"} 
    Item Name and friendlyName don't have to be identical!


## Item Binding Configuration (Version 1.8)

In order to bind an item to the device, you need to provide configuration settings. The easiest way to do so is to add some binding information in your item file (in the folder configurations/items`). The syntax of the binding configuration strings accepted is the following:

    wemo="<UDN>;[<channel-type>]"


You can find your WeMo devices' UDN in your openHAB logfile. The Binding lists all discovered WeMo devices at start.

The channel type of your item definition is **optional**, it will default to channel type "**state**".
The following channel types are possible for Insight switch devices:

	state			Whether the device is on or off
	lastChangedAt	DateTime the device was last turned on or off
	lastOnFor		Time in seconds the device was last turned on for
	onToday			Time in seconds the device has been on for today
	onTotal			Time in seconds the device has been on for in total over timespan period
	timespan		Time in seconds over which onTotal applies. Typically 2 weeks except when device first used
	averagePower	Average power in Watts. Unclear how this is calculated exactly
	currentPower	Current power usage in Watts. 0 if switched off
	energyToday		Energy in Wh used today
	energyTotal		Energy in Wh used in total
	standbyLimit	Minimum energy draw in W to register device as switched on (default 8W, configurable via wemo app)

Examples, how to configure your items in your items file:

	Switch Socket1                                       {wemo="Socket-1-0-12345678"}
	Switch Insight1                                      {wemo="Insight-1-0-87654321"}
	Number Insight_currentPower  "Current Power [%.0f]"  {wemo="Insight-1-0-87654321;currentPower"}
	Number Insight_onToday       "On Today [%.0f]"       {wemo="Insight-1-0-87654321;onToday"}
	Number Insight_onTotal       "On Total [%.0f]"       {wemo="Insight-1-0-87654321;onTotal"}
	Number Insight_energyToday   "Energy Today [%.0fWh]" {wemo="Insight-1-0-87654321;energyToday"}
	DateTime Insight_LastChange  "Last change [%1$tH:%1$tM]"  {wemo="Insight-1_0-87654321;lastChangedAt"}
	Contact Motion1                                      {wemo="Sensor-1-0-56437891"}

