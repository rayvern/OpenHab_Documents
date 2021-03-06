## New & Noteworthy

Please find below the release notes of the 1.8 Release.

### Version 1.8.3

This is the third bugfix release of the 1.8 release. See the Github issue tracker for a [full change log](https://github.com/openhab/openhab/issues?q=milestone%3A1.8.3).

#### Updating the openHAB runtime 1.8.2 to 1.8.3

Many of the fixes does not require to update the Runtime itself so it would suffice to simply replace the Binding jars in your Add-Ons folder. However, if you would like have one of these [issues in the runtime](https://github.com/openhab/openhab/issues?q=milestone%3A1.8.3+label%3Aruntime) fixed you will have to update the Runtime as well.

####Enhancements:
* [#4311](https://github.com/openhab/openhab/pull/4311) - Update pairing mechanism of hue binding to be compatible with new firmware (@dominicdesu)
* [#4309](https://github.com/openhab/openhab/pull/4309) - FritzBoxTR064 Binding: Update for network stability (@gitbock)
* [#4231](https://github.com/openhab/openhab/pull/4231) - Log a warning if the Hue binding for an item is empty. (@9037568)

####Bugfixes:
* [#4397](https://github.com/openhab/openhab/pull/4397) - Updated notes and attributes for the weather binding. (@9037568)
* [#4388](https://github.com/openhab/openhab/pull/4388) - Typo corrected (@ralle12345)
* [#4356](https://github.com/openhab/openhab/pull/4356) - [ecobee] Remove leading spaces to avoid confusion (@watou)
* [#4351](https://github.com/openhab/openhab/pull/4351) - Bugfix at binding EM. only Datapoint.CUMULATED items could be updated… (@svenschreier)
* [#4292](https://github.com/openhab/openhab/pull/4292) - deb packaging: docker support (@theoweiss)
* [#4290](https://github.com/openhab/openhab/pull/4290) - renamed netatmo binding v1 (@kaikreuzer)
* [#4281](https://github.com/openhab/openhab/pull/4281) - Fix issue reported in #4239 (@kreutpet)
* [#4278](https://github.com/openhab/openhab/pull/4278) - fix Classic-UI (@teichsta)
* [#4263](https://github.com/openhab/openhab/pull/4263) - Issue-2863: Moved files to interal-package to be able to log properly. Reduced ti… (@steintore)
* [#4258](https://github.com/openhab/openhab/pull/4258) - Onkyo Binding multiple devices status update fix (@vavaroutsos)
* [#4246](https://github.com/openhab/openhab/issues/4246) - apt-get install openhab-runtime assumes dbus is installed (@marnikvde)
* [#4237](https://github.com/openhab/openhab/pull/4237) - RFXCOM Add Average speed for all wind sensors (@Speederc)
* [#4214](https://github.com/openhab/openhab/issues/4214) - No updates in Classic UI after 1.8.2 upgrade (@watou)
* [#4208](https://github.com/openhab/openhab/pull/4208) - [DSC Alarm] Bug Fix - Could not handle 'deviceType' configuration parameter (@RSStephens)
* [#3258](https://github.com/openhab/openhab/issues/3258) - Adjust hue binding for hue API whitelist changes (@dominicdesu)

### Version 1.8.2

This is the second bugfix release of the 1.8 release. See the Github issue tracker for a [full change log](https://github.com/openhab/openhab/issues?q=milestone%3A1.8.2).

#### Updating the openHAB runtime 1.8.1 to 1.8.2

Many of the fixes does not require to update the Runtime itself so it would suffice to simply replace the Binding jars in your Add-Ons folder. However, if you would like have one of these [issues in the runtime](https://github.com/openhab/openhab/issues?q=milestone%3A1.8.2+label%3Aruntime) fixed you will have to update the Runtime as well.

####Enhancements:
* [#4190](https://github.com/openhab/openhab/pull/4190) - ZWave Update database (@cdjackson)
* [#4169](https://github.com/openhab/openhab/pull/4169) - Update Z-Wave database for 1.8.2 release (@cdjackson)
* [#4142](https://github.com/openhab/openhab/pull/4142) - updated jodatime to 2.9.2 (@teichsta)
* [#4062](https://github.com/openhab/openhab/pull/4062) - Denon binding: use different http request method (@idserda)
* [#3777](https://github.com/openhab/openhab/pull/3777) - [neohub] Set heating to on when preheat is on (@carlossg)

####Bugfixes:
* [#4200](https://github.com/openhab/openhab/pull/4200) - Minor spelling/grammar fixes for S bindings. (@9037568)
* [#4199](https://github.com/openhab/openhab/pull/4199) - Correct squeezebox action and binding example config (@watou)
* [#4197](https://github.com/openhab/openhab/pull/4197) - bugfix in the way house codes and unit codes are packed into a single… (@renescherer)
* [#4171](https://github.com/openhab/openhab/pull/4171) - 4 Bugs in Derby DAO and some typo (@lewie)
* [#4168](https://github.com/openhab/openhab/pull/4168) - Maven warnings on build start (@slawekjaranowski)
* [#4166](https://github.com/openhab/openhab/pull/4166) - don't change file mode of files in OPENHAB_HOME_DIR (@theoweiss)
* [#4161](https://github.com/openhab/openhab/pull/4161) - fritzboxtr064 binding: fix compilation error (@stefanroellin)
* [#4159](https://github.com/openhab/openhab/pull/4159) - Small fixes to TACmi binding (@Wolfgang1966)
* [#4153](https://github.com/openhab/openhab/pull/4153) - MalformedByteSequenceException in stiebelheatpump ConfigParserTest (@slawekjaranowski)
* [#4146](https://github.com/openhab/openhab/pull/4146) - Fix dropbox for windows machines (@computergeek1507)
* [#4120](https://github.com/openhab/openhab/pull/4120) - [novelan] Fix for issue #4119 (@watou)
* [#4117](https://github.com/openhab/openhab/pull/4117) - ClassicUI: full image and chart refresh (@watou)
* [#4115](https://github.com/openhab/openhab/pull/4115) - Freebox binding: fix FTP config compatibility with firmware 3.3 (@lolodomo)
* [#4110](https://github.com/openhab/openhab/pull/4110) - Changed regex matcher to "Find" method to support more garage door openers (@computergeek1507)
* [#4106](https://github.com/openhab/openhab/pull/4106) - eBUS - Fix NullPointException if telegram value is invalid/out of range (@csowada)
* [#4068](https://github.com/openhab/openhab/pull/4068) - Fix bug in node name class where location was set as the name (@cdjackson)
* [#4062](https://github.com/openhab/openhab/pull/4062) - Denon binding: use different http request method (@idserda)
* [#4060](https://github.com/openhab/openhab/pull/4060) - Handle null terminations in node naming class (@cdjackson)
* [#4058](https://github.com/openhab/openhab/issues/4058) - NULLs in zwave data cause message length errors (@TheKorn2)
* [#4057](https://github.com/openhab/openhab/pull/4057) - Update handling of configuration class detection (@cdjackson)
* [#4051](https://github.com/openhab/openhab/pull/4051) - reverted: Implement slider widget for WebUI #2792 (@teichsta)
* [#4047](https://github.com/openhab/openhab/pull/4047) - [ecobee] Include alerts in the payload when any item is bound to an alerts property (@watou)
* [#4046](https://github.com/openhab/openhab/issues/4046) - Embedded NULLs in zwave XML persistence files cause deserialization errors on openHAB startup. (@TheKorn2)
* [#4032](https://github.com/openhab/openhab/pull/4032) - RFXCOM clear buffer after reset command (@ivanfmartinez)
* [#4021](https://github.com/openhab/openhab/pull/4021) - Fixed javascript that was breaking the colorpicker. (@9037568)
* [#4020](https://github.com/openhab/openhab/pull/4020) - Fix error casting wakeup class (@cdjackson)
* [#4018](https://github.com/openhab/openhab/pull/4018) - [davis] correct barometric pressure conversion (@watou)
* [#4017](https://github.com/openhab/openhab/pull/4017) - Rfxcom reset buffer (@ivanfmartinez)
* [#4014](https://github.com/openhab/openhab/pull/4014) - ZWave: Fix casting error in config (@cdjackson)
* [#4008](https://github.com/openhab/openhab/pull/4008) - [ecobee] Change seconds back to minutes for PIN expiration (@watou)


### Version 1.8.1

This is the first bugfix release of the 1.8 release. See the Github issue tracker for a [full change log](https://github.com/openhab/openhab/issues?q=milestone%3A1.8.1).

#### Updating the openHAB runtime 1.8.0 to 1.8.1

Many of the fixes does not require to update the Runtime itself so it would suffice to simply replace the Binding jars in your Add-Ons folder. However, if you would like have one of these [issues in the runtime](https://github.com/openhab/openhab/issues?q=milestone%3A1.8.1+label%3Aruntime) fixed you will have to update the Runtime as well.

####Enhancements:
* [#3881](https://github.com/openhab/openhab/pull/3881) - Remove dependancy on database to determine if device supports class during config (@cdjackson)
* [#3774](https://github.com/openhab/openhab/pull/3774) - DSC Alarm Binding: IT-100 TCP Connection Support (@marclennox)

####Bugfixes:
* [#3950](https://github.com/openhab/openhab/pull/3950) - [nest] Allow setting setpoints with decimals (@watou)
* [#3890](https://github.com/openhab/openhab/pull/3890) - [tcp] Same change as #3792 on 1.8 (@watou)
* [#3888](https://github.com/openhab/openhab/pull/3888) - [weather] workaround for #3860 (@watou)
* [#3882](https://github.com/openhab/openhab/pull/3882) - Bugfix in frontiersiliconradio: volume update posted from value on bus. (@paphko)
* [#3844](https://github.com/openhab/openhab/pull/3844) - Sonance binding power query and volume command fix (@LaurensVanAcker)
* [#3830](https://github.com/openhab/openhab/issues/3830) - 1.8 Classic UI Does not render properly (@z00tv)
* [#3825](https://github.com/openhab/openhab/pull/3825) - ExecUtil: fixed incorrect exitValue configuration. (@steve-bate)
* [#3821](https://github.com/openhab/openhab/issues/3821) - ExecUtil command execution raises exception when exitCode != 1 (@steve-bate)
* [#3819](https://github.com/openhab/openhab/pull/3819) - Modbus TCP connections closed after every transaction (@ssalonen)
transaction (@ssalonen)
* [#3816](https://github.com/openhab/openhab/pull/3816) - Some bugfix (@fazioa)
* [#3813](https://github.com/openhab/openhab/pull/3813) - [weather] Add name examples to default weather binding config (@watou)
* [#3812](https://github.com/openhab/openhab/pull/3812) - MariaDB compatibility update (@lewie)
* [#3804](https://github.com/openhab/openhab/pull/3804) - Rename duplicate influxdb project Eclipse (@idserda)
* [#3796](https://github.com/openhab/openhab/pull/3796) - Fix ClassicUI Slider for no-value-labels (@sja)
* [#3779](https://github.com/openhab/openhab/pull/3779) - Remove the switch_all command class from the default command classes … (@cdjackson)
* [#3733](https://github.com/openhab/openhab/pull/3733) - Fix bug with ZWave library types (@cdjackson)
* [#3122](https://github.com/openhab/openhab/pull/3122) - RRD4J: Handling of Dimmer and Rollershutter items during restore of values improved (Fix for #3090). (@LKuech)

####Uncategorized:

* [#3881](https://github.com/openhab/openhab/pull/3881) - Remove dependancy on database to determine if device supports class during config (@cdjackson)
* [#3774](https://github.com/openhab/openhab/pull/3774) - DSC Alarm Binding: IT-100 TCP Connection Support (@marclennox)
* [#3770](https://github.com/openhab/openhab/pull/3770) - some cleanup on yamahareceiver project (@kaikreuzer)


### Version 1.8.0

See the Github issue tracker for a [full change log](https://github.com/openhab/openhab/issues?q=milestone%3A1.8.0).

####Major Features:
* [#3680](https://github.com/openhab/openhab/pull/3680) - [sallegra] Added Sallegra binding (replaces #3520) (@watou)
* [#3624](https://github.com/openhab/openhab/pull/3624) - initial checkin of the AKM868 on behalf of @MitchSUEW (@teichsta)
* [#3610](https://github.com/openhab/openhab/pull/3610) - InfluxDB persistence for influxdb versions >= 0.9  (@theoweiss)
* [#3569](https://github.com/openhab/openhab/pull/3569) - First Checkin of FritzBox TR064 Binding for 1.8.0 (@gitbock)
* [#3539](https://github.com/openhab/openhab/pull/3539) - Added Chamberlain MyQ Binding (@computergeek1507)
* [#3468](https://github.com/openhab/openhab/pull/3468) - caldav binding 26/11 (@querdenker2k)
* [#3401](https://github.com/openhab/openhab/pull/3401) - Sonance binding (@LaurensVanAcker)
* [#3386](https://github.com/openhab/openhab/pull/3386) - Implemented RWE Smarthome binding (@ollie-dev)
* [#3266](https://github.com/openhab/openhab/pull/3266) - New DSC Alarm Action (@RSStephens)
* [#3248](https://github.com/openhab/openhab/pull/3248) - New generic JDBC Persistence Service (@lewie)
* [#3230](https://github.com/openhab/openhab/pull/3230) - Telegram action (@paolodenti)
* [#3229](https://github.com/openhab/openhab/pull/3229) - new binding for picnet home automation devices (@paolodenti)
* [#3187](https://github.com/openhab/openhab/pull/3187) - New binding: panStamp wireless Arduino modules (@GideonLeGrange)
* [#3086](https://github.com/openhab/openhab/pull/3086) - MQTT Action bundle (@kstaniek)
* [#3082](https://github.com/openhab/openhab/pull/3082) - Binding for relay boards available from http://www.ucprojects.eu (@rmichalak)
* [#3076](https://github.com/openhab/openhab/pull/3076) - Mystrom Binding (@coolweb)
* [#3002](https://github.com/openhab/openhab/pull/3002) - Added LCN binding (@Issendorff)
* [#2755](https://github.com/openhab/openhab/pull/2755) - Added Ecobee action bundle. (@watou)
* [#2707](https://github.com/openhab/openhab/pull/2707) - Initial contribution of SiteWhere persistence provider (@derekadams)
* [#2568](https://github.com/openhab/openhab/pull/2568) - Binding for octoller (www.octoller.com) V1.0.0 / Try 2 (@JPlenert)
* [#2567](https://github.com/openhab/openhab/pull/2567) - New binding to control RC switches (@mroeckl)
* [#2525](https://github.com/openhab/openhab/pull/2525) - Initial implementation of TACmi binding. (@twendt)
* [#2478](https://github.com/openhab/openhab/pull/2478) - New binding for IPX800 (@seebag)
* [#2101](https://github.com/openhab/openhab/pull/2101) - new stiebel eltron heat pump binding (@kreutpet)

####Enhancements:
* [#3737](https://github.com/openhab/openhab/pull/3737) - Added cause of ConnectException to the log call (@kwave)
* [#3704](https://github.com/openhab/openhab/pull/3704) - Add additional device information flags (@cdjackson)
* [#3703](https://github.com/openhab/openhab/pull/3703) - Update to new ESH feature (@dvanherbergen)
* [#3692](https://github.com/openhab/openhab/pull/3692) - [nest] Added optional nest:timeout config parameter (@watou)
* [#3682](https://github.com/openhab/openhab/pull/3682) - InsteonPLM: add support for rampdimmer with KeypadLinc dimmers (@robnielsen)
* [#3671](https://github.com/openhab/openhab/pull/3671) - Add support for energie measuerement on PWM-LAN devices. Replaces #2908 (@hmerk)
* [#3669](https://github.com/openhab/openhab/pull/3669) - Improve max cul support (@johgoe)
* [#3653](https://github.com/openhab/openhab/pull/3653) - Modbus binding: writing open/closed types now work with registers too (@ssalonen)
* [#3648](https://github.com/openhab/openhab/pull/3648) - Prevented Atmosphere from calling home - fixes #1527 (@digitaldan)
* [#3640](https://github.com/openhab/openhab/pull/3640) - Add type for maxCube binding to get informed about connection errors (@dominicdesu)
* [#3639](https://github.com/openhab/openhab/pull/3639) - Major Update eBus binding (docs) (@csowada)
* [#3636](https://github.com/openhab/openhab/pull/3636) - Major Update eBus binding (source) (@csowada)
* [#3621](https://github.com/openhab/openhab/pull/3621) - Insteon: Added Ramp Dimmer Support (@steve-bate)
* [#3615](https://github.com/openhab/openhab/pull/3615) - [novelanheatpump] Add port config parameter (for #3607) (@watou)
* [#3608](https://github.com/openhab/openhab/pull/3608) - Tinkerforge binding and action: new devices, enhancements and fixes (@theoweiss)
* [#3607](https://github.com/openhab/openhab/issues/3607) - Novelan / Luxtronic Port has changed (@boxerfahrer)
* [#3606](https://github.com/openhab/openhab/pull/3606) - InsteonPLM: Improved logging of items that match devices in modem database (@robnielsen)
* [#3604](https://github.com/openhab/openhab/pull/3604) - Plex binding update (@idserda)
* [#3598](https://github.com/openhab/openhab/pull/3598) - Weather: Added Wunderground total precipitation (@gerrieg)
* [#3593](https://github.com/openhab/openhab/pull/3593) - Weather: Fixed exception if degree is not in a valid range (@gerrieg)
* [#3590](https://github.com/openhab/openhab/pull/3590) - InsteonPLM: removed comments after port configuration in openhab_default.cfg (@berndpfrommer)
* [#3588](https://github.com/openhab/openhab/pull/3588) - Updated Squeezebox speak action to allow configurable TTS URL (@sumnerboy12)
* [#3568](https://github.com/openhab/openhab/pull/3568) - [ecobee] Added quick poll after update, command or action. (@watou)
* [#3565](https://github.com/openhab/openhab/pull/3565) - a few fixes to run smoothly on Karaf (@kaikreuzer)
* [#3564](https://github.com/openhab/openhab/pull/3564) - Add Souliss types 54, 55, 56 and 58 (light, voltage, current, pressure). (@slepp)
* [#3553](https://github.com/openhab/openhab/pull/3553) - [Telegram action] enhancement: added send photo capability (@paolodenti)
* [#3552](https://github.com/openhab/openhab/pull/3552) - Tinkerforge binding and action: new devices, enhancements and fixes (@theoweiss)
* [#3544](https://github.com/openhab/openhab/pull/3544) - Wemo insight: additional parameters added #3538 (@toby200)
* [#3534](https://github.com/openhab/openhab/pull/3534) - OneWireBinding - Support for iButtons (@Dennis650)
* [#3515](https://github.com/openhab/openhab/pull/3515) - InsteonPLM: Include known features when an item is configured with an unknown feature (@robnielsen)
* [#3494](https://github.com/openhab/openhab/pull/3494) - [Ecobee] Updated to align with December 2015 ecobee API update. (@watou)
* [#3489](https://github.com/openhab/openhab/pull/3489) - [Sapp Binding] BigDecimal precision in scaling vs double (@paolodenti)
* [#3486](https://github.com/openhab/openhab/pull/3486) - Added support for regex substitutions to Regex transformation (@steve-bate)
* [#3485](https://github.com/openhab/openhab/pull/3485) - Log execution failures in ExecUtil. (@steve-bate)
* [#3476](https://github.com/openhab/openhab/pull/3476) - apt installation: openhab user as owner of /etc/openhab/configurations directory (@theoweiss)
* [#3434](https://github.com/openhab/openhab/pull/3434) - insteonplm: Added On/Off Outlet configuration (@SwissKid)

####Bugfixes:
* [#3738](https://github.com/openhab/openhab/pull/3738) - [db4o-persistence] fix for #3728 (@watou)
* [#3733](https://github.com/openhab/openhab/pull/3733) - Fix bug with ZWave library types (@cdjackson)
* [#3731](https://github.com/openhab/openhab/pull/3731) - Souliss - Fix typical T18 state mapping - fixes  #3730 (@xalopp)
* [#3728](https://github.com/openhab/openhab/issues/3728) - db4o persistence not working in 1.8 RC (@watou)
* [#3725](https://github.com/openhab/openhab/issues/3725) - io.caldav bundle not in addons.zip (@watou)
* [#3723](https://github.com/openhab/openhab/issues/3723) - Fritzbox TR064 to integrate into the maven build (@teichsta)
* [#3721](https://github.com/openhab/openhab/pull/3721) - MyQ Device fixes (@computergeek1507)
* [#3719](https://github.com/openhab/openhab/pull/3719) - Fix a bug preventing proper logout from energenie devices (@hmerk)
* [#3718](https://github.com/openhab/openhab/pull/3718) - [nibeheatpump] Fix for #3714 (@watou)
* [#3717](https://github.com/openhab/openhab/pull/3717) - Updates to fix XML serialisation issues (@cdjackson)
* [#3687](https://github.com/openhab/openhab/pull/3687) - Modbus binding: holding/input register state updates now support all the same item types as coil/discrete inputs (@ssalonen)
* [#3679](https://github.com/openhab/openhab/pull/3679) - remove the special toString() in order to sync with ESH (@teichsta)
* [#3677](https://github.com/openhab/openhab/pull/3677) - [caldav] fix logging and rescheduling (@querdenker2k)
* [#3676](https://github.com/openhab/openhab/pull/3676) - fix logging and rescheduling (@querdenker2k)
* [#3675](https://github.com/openhab/openhab/pull/3675) - Include binding fritzboxtr064 into build process (@gitbock)
* [#3670](https://github.com/openhab/openhab/pull/3670) - add bundles to maven build which will help increasing their version t… (@teichsta)
* [#3666](https://github.com/openhab/openhab/pull/3666) - Remove already renamed configs, fix generated id-lists and generator. (@csowada)
* [#3655](https://github.com/openhab/openhab/pull/3655) - Modbus binding: Items bound to discrete / coil issue fixed (@ssalonen)
* [#3651](https://github.com/openhab/openhab/pull/3651) - Make maxCube tests compatible with Java 1.6 (@dominicdesu)
* [#3646](https://github.com/openhab/openhab/pull/3646) - Update stale Bundle-Versions (for #3638) (@watou)
* [#3642](https://github.com/openhab/openhab/pull/3642) - Compare strings with equals method (@coolweb)
* [#3637](https://github.com/openhab/openhab/pull/3637) - [dsmr] fixed Bundle-Version (@watou)
* [#3633](https://github.com/openhab/openhab/pull/3633) - [Hue] Osram-Par16-50-Workaround (@markusmazurczak)
* [#3605](https://github.com/openhab/openhab/pull/3605) - Better connection handling in pilight binding (@idserda)
* [#3566](https://github.com/openhab/openhab/pull/3566) - Added PersistenceService interface (@derekadams)
* [#3562](https://github.com/openhab/openhab/pull/3562) - Denon NPE fix (@idserda)
* [#3561](https://github.com/openhab/openhab/pull/3561) - Denon binding telnet connection fix (@idserda)
* [#3555](https://github.com/openhab/openhab/pull/3555) - Fixed session timeout problem (important for 1.8.0 release) (@ollie-dev)
* [#3552](https://github.com/openhab/openhab/pull/3552) - Tinkerforge binding and action: new devices, enhancements and fixes (@theoweiss)
* [#3551](https://github.com/openhab/openhab/pull/3551) - Fixes #3454: Use userdata for token path when running in OH2 (@hakan42)
* [#3547](https://github.com/openhab/openhab/pull/3547) - Specify pid file when checking process status (@jshprentz)
* [#3540](https://github.com/openhab/openhab/issues/3540) - Init.d reports incorrect openHAB status in Ubuntu 14.04 (@jshprentz)
* [#3532](https://github.com/openhab/openhab/pull/3532) - Updated start.bat to work on a path with spaces (@Tom-Davidson)
* [#3530](https://github.com/openhab/openhab/pull/3530) - jdbc persistence: fix postgresql table creation (@hakan42)
* [#3524](https://github.com/openhab/openhab/pull/3524) - [sapp binding] - binding not included in addons build (@paolodenti)
* [#3523](https://github.com/openhab/openhab/issues/3523) - Caldav binding: error executing event job (@TheNetStriker)
* [#3522](https://github.com/openhab/openhab/pull/3522) - Milight Binding - map a saturation value of 0 to WhiteMode, fixes #1400 (@hmerk)
* [#3516](https://github.com/openhab/openhab/issues/3516) - jdbc persistence: tableNamePrefix error on startup (@hakan42)
* [#3512](https://github.com/openhab/openhab/pull/3512) - Modbus binding to close connections on configuration refresh (@ssalonen)
* [#3507](https://github.com/openhab/openhab/pull/3507) - PointType needs hashCode and equals to be used in tests (@watou)
* [#3504](https://github.com/openhab/openhab/pull/3504) - [mqtt] Make inbound messages sensitive to item's accepted types and commands (@watou)
* [#3500](https://github.com/openhab/openhab/pull/3500) - mpd: fix artist and track not updated (@stefanroellin)
* [#3475](https://github.com/openhab/openhab/pull/3475) - fix permission and content directory issues when used within apt installation (@theoweiss)

####Uncategorized:
* [#3741](https://github.com/openhab/openhab/pull/3741) - fixes #3723 to make tr064 binding build with maven (@teichsta)
* [#3740](https://github.com/openhab/openhab/pull/3740) - switched to release versions to make it stable (and not being impacte… (@kaikreuzer)
* [#3738](https://github.com/openhab/openhab/pull/3738) - [db4o-persistence] fix for #3728 (@watou)
* [#3737](https://github.com/openhab/openhab/pull/3737) - Added cause of ConnectException to the log call (@kwave)
* [#3733](https://github.com/openhab/openhab/pull/3733) - Fix bug with ZWave library types (@cdjackson)
* [#3731](https://github.com/openhab/openhab/pull/3731) - Souliss - Fix typical T18 state mapping - fixes  #3730 (@xalopp)
* [#3728](https://github.com/openhab/openhab/issues/3728) - db4o persistence not working in 1.8 RC (@watou)
* [#3726](https://github.com/openhab/openhab/pull/3726) - changed include pattern to include all org.openhab.io bundles (@teichsta)
* [#3725](https://github.com/openhab/openhab/issues/3725) - io.caldav bundle not in addons.zip (@watou)
* [#3723](https://github.com/openhab/openhab/issues/3723) - Fritzbox TR064 to integrate into the maven build (@teichsta)
* [#3721](https://github.com/openhab/openhab/pull/3721) - MyQ Device fixes (@computergeek1507)
* [#3720](https://github.com/openhab/openhab/pull/3720) - Added Ecobee and Nest to features. (@watou)
* [#3719](https://github.com/openhab/openhab/pull/3719) - Fix a bug preventing proper logout from energenie devices (@hmerk)
* [#3718](https://github.com/openhab/openhab/pull/3718) - [nibeheatpump] Fix for #3714 (@watou)
* [#3717](https://github.com/openhab/openhab/pull/3717) - Updates to fix XML serialisation issues (@cdjackson)
* [#3716](https://github.com/openhab/openhab/pull/3716) - [RRD4j] Reduce log level (@kaikreuzer)
* [#3709](https://github.com/openhab/openhab/pull/3709) - Fix list compare change in #3670 (@gameldar comment) (@watou)
* [#3704](https://github.com/openhab/openhab/pull/3704) - Add additional device information flags (@cdjackson)
* [#3703](https://github.com/openhab/openhab/pull/3703) - Update to new ESH feature (@dvanherbergen)
* [#3697](https://github.com/openhab/openhab/pull/3697) - Remove applicationUpdateReceived from XML (@cdjackson)
* [#3692](https://github.com/openhab/openhab/pull/3692) - [nest] Added optional nest:timeout config parameter (@watou)
* [#3688](https://github.com/openhab/openhab/pull/3688) - Add node information frame into saved node XML file (@cdjackson)
* [#3687](https://github.com/openhab/openhab/pull/3687) - Modbus binding: holding/input register state updates now support all the same item types as coil/discrete inputs (@ssalonen)
* [#3682](https://github.com/openhab/openhab/pull/3682) - InsteonPLM: add support for rampdimmer with KeypadLinc dimmers (@robnielsen)
* [#3680](https://github.com/openhab/openhab/pull/3680) - [sallegra] Added Sallegra binding (replaces #3520) (@watou)
* [#3679](https://github.com/openhab/openhab/pull/3679) - remove the special toString() in order to sync with ESH (@teichsta)
* [#3677](https://github.com/openhab/openhab/pull/3677) - [caldav] fix logging and rescheduling (@querdenker2k)
* [#3676](https://github.com/openhab/openhab/pull/3676) - fix logging and rescheduling (@querdenker2k)
* [#3675](https://github.com/openhab/openhab/pull/3675) - Include binding fritzboxtr064 into build process (@gitbock)
* [#3671](https://github.com/openhab/openhab/pull/3671) - Add support for energie measuerement on PWM-LAN devices. Replaces #2908 (@hmerk)


####Removals:
* none

#### Major API changes
* none

## Updating the openHAB runtime 1.7 to 1.8

If you have a running openHAB runtime 1.7 installation, you can easily update it to version 1.8 by following these steps:
 1. Unzip the runtime 1.8 and all required addons to a new installation folder
 1. Replace the folder "configurations" by the version from your 1.7 installation
 1. Copy all other customizations you might have done to the new installation (e.g. additional images, sounds, etc.)

If you use the openHAB deb packages from the apt repository
 1. Add this line to your sources.list: "deb http://dl.bintray.com/openhab/apt-repo   stable    main“
 1. Open a command-line  and execute: apt-get update && apt-get upgrade

**NOTE: The upgrade process may overwrite your start script, so any custom modifications added to the openHAB launch command may need to be re-customized.**  An example of this is the use of named serial port instances with the option `-Dgnu.io.rxtx.SerialPorts=/dev/ttyAMA0`.  A restart may also be required.