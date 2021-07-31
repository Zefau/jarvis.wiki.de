# Heizung

## vordefinierte Datenpunkte

| Datenpunkt Bezeichner | Datenpunkt Stil | Anzeige | Einheit | Icon | Icon Stil |
| :--- | :--- | :--- | :--- | :--- | :--- |
| `temperature` | - | - | `" °C"` | `"thermometer"` | - |
| `settemperature` | - | - | `" °C"` | `"thermometer-chevron-up"` | - |
| `humidity` | - | - | `" %"` | - | - |
| `boost` | - | - | - | `"radiator"` | - |
| `boostTime` | - | - | `"min."` | `"clock-outline"` | - |
| `boostState` | - | - | - | - | - |
| `frost` | - | - | - | - | - |
| `windowState` | - | - | - | - | - |
| `partyMode` | - | - | - | - | - |
| `modeAuto` | - | - | - | `"brightness-auto"` | - |
| `modeManu` | - | - | - | - | - |
| `modeCurrent` | - | - | - | - | - |
| `modeLowering` | - | - | - | - | - |
| `modeControl` | - | - | - | `"list-status"` | - |
| `valve` | - | - | `"%"` | `"valve"` | - |
| `valvePosition` | - | - | - | - | - |
| `valveState` | - | - | - | - | - |

## Beispielkonfiguration

### Adapter hm-rpc

#### HmIP-STHD

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `temperature` | `.1.ACTUAL_TEMPERATURE` |  |  |  |
| `setTemperature` | `.1.SET_POINT_TEMPERATURE` |  |  | `.1.SET_POINT_TEMPERATURE` |
| `humidity` | `.1.HUMIDITY` |  |  |  |
| `frost` | `.1.FROST_PROTECTION` |  |  |  |
| `boost` | `.1.BOOST_MODE` |  |  | `.1.BOOST_MODE` |
| `boostTime` | `.1.BOOST_TIME` |  |  | `.1.BOOST_TIME` |
| `windowState` | `.1.WINDOW_STATE` |  |  |  |
| `partyMode` | `.1.PARTY_MODE` |  |  | `.1.PARTY_MODE` |

#### HmIP-eTRV-B

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `temperature` | `.1.ACTUAL_TEMPERATURE` |  |  |  |
| `setTemperature` | `.1.SET_POINT_TEMPERATURE` |  |  | `.1.SET_POINT_TEMPERATURE` |
| `frost` | `.1.FROST_PROTECTION` |  |  |  |
| `boost` | `.1.BOOST_MODE` |  |  | `.1.BOOST_MODE` |
| `boostTime` | `.1.BOOST_TIME` |  |  | `.1.BOOST_TIME` |
| `windowState` | `.1.WINDOW_STATE` |  |  |  |
| `partyMode` | `.1.PARTY_MODE` |  |  | `.1.PARTY_MODE` |

#### HmIP-eTRV

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `temperature` | `.1.ACTUAL_TEMPERATURE` |  |  |  |
| `setTemperature` | `.1.SET_POINT_TEMPERATURE` |  |  | `.1.SET_POINT_TEMPERATURE` |
| `frost` | `.1.FROST_PROTECTION` |  |  |  |
| `boost` | `.1.BOOST_MODE` |  |  | `.1.BOOST_MODE` |
| `boostTime` | `.1.BOOST_TIME` |  |  | `.1.BOOST_TIME` |
| `windowState` | `.1.WINDOW_STATE` |  |  |  |
| `partyMode` | `.1.PARTY_MODE` |  |  | `.1.PARTY_MODE` |
| `level` | `.1.LEVEL` |  |  | `.1.LEVEL` |
| `valve` | `.1.VALVE_STATE` |  |  | `.1.VALVE_STATE` |

#### HmIP-eTRV-2

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `temperature` | `.1.ACTUAL_TEMPERATURE` |  |  |  |
| `setTemperature` | `.1.SET_POINT_TEMPERATURE` |  |  | `.1.SET_POINT_TEMPERATURE` |
| `frost` | `.1.FROST_PROTECTION` |  |  |  |
| `boost` | `.1.BOOST_MODE` |  |  | `.1.BOOST_MODE` |
| `boostTime` | `.1.BOOST_TIME` |  |  | `.1.BOOST_TIME` |
| `windowState` | `.1.WINDOW_STATE` |  |  |  |
| `partyMode` | `.1.PARTY_MODE` |  |  | `.1.PARTY_MODE` |
| `level` | `.1.LEVEL` |  |  | `.1.LEVEL` |
| `valve` | `.1.VALVE_STATE` |  |  | `.1.VALVE_STATE` |

#### HmIP-BWTH

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `temperature` | `.1.ACTUAL_TEMPERATURE` |  |  |  |
| `setTemperature` | `.1.SET_POINT_TEMPERATURE` |  |  | `.1.SET_POINT_TEMPERATURE` |
| `humidity` | `.1.HUMIDITY` |  |  |  |
| `boost` | `.1.BOOST_MODE` |  |  | `.1.BOOST_MODE` |

#### HmIP-WTH

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `temperature` | `.1.ACTUAL_TEMPERATURE` |  |  |  |
| `setTemperature` | `.1.SET_POINT_TEMPERATURE` |  |  | `.1.SET_POINT_TEMPERATURE` |
| `humidity` | `.1.HUMIDITY` |  |  |  |
| `boost` | `.1.BOOST_MODE` |  |  | `.1.BOOST_MODE` |

#### HmIP-WTH-2

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `temperature` | `.1.ACTUAL_TEMPERATURE` |  |  |  |
| `setTemperature` | `.1.SET_POINT_TEMPERATURE` |  |  | `.1.SET_POINT_TEMPERATURE` |
| `humidity` | `.1.HUMIDITY` |  |  |  |
| `boost` | `.1.BOOST_MODE` |  |  | `.1.BOOST_MODE` |

#### HM-CC-RT-DN

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `temperature` | `.4.ACTUAL_TEMPERATURE` |  |  |  |
| `setTemperature` | `.4.SET_TEMPERATURE` |  |  | `.4.SET_TEMPERATURE` |
| `boost` | `.4.BOOST_MODE` |  |  | `.4.BOOST_MODE` |
| `batteryState` | `.4.BATTERY_STATE` |  |  |  |
| `partyTemperature` | `.4.PARTY_TEMPERATURE` |  |  |  |
| `modeAuto` | `.4.AUTO_MODE` |  |  | `.4.AUTO_MODE` |
| `modeManu` | `.4.MANU_MODE` |  |  | `.4.MANU_MODE` |
| `boostState` | `.4.BOOST_STATE` |  |  | `.4.BOOST_STATE` |
| `modeCurrent` | `.4.COMFORT_MODE` |  |  | `.4.COMFORT_MODE` |
| `modeLowering` | `.4.LOWERING_MODE` |  |  | `.4.LOWERING_MODE` |
| `modeControl` | `.4.CONTROL_MODE` |  | `{  "0": "Auto-Mode",  "1": "Manu-Mode",  "2": "Party-Mode",  "3": "Boost-Mode" }` | `.4.CONTROL_MODE` |
| `valve` | `.4.VALVE_STATE` |  |  | `.4.VALVE_STATE` |

#### HM-TC-IT-WM-W-EU

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `temperature` | `.1.TEMPERATURE` |  |  |  |
| `humidity` | `.1.HUMIDITY` |  |  |  |
| `actualHumidity` | `.2.ACTUAL_HUMIDITY` |  |  |  |
| `actualTemperature` | `.2.ACTUAL_TEMPERATURE` |  |  |  |
| `modeAuto` | `.2.AUTO_MODE` |  |  | `.2.AUTO_MODE` |
| `batteryState` | `.2.BATTERY_STATE` |  |  |  |
| `boost` | `.2.BOOST_MODE` |  |  | `.2.BOOST_MODE` |
| `boostState` | `.2.BOOST_STATE` |  |  | `.2.BOOST_STATE` |
| `modeControl` | `.2.CONTROL_MODE` |  | `{  "0": "Auto-Mode",  "1": "Manu-Mode",  "2": "Party-Mode",  "3": "Boost-Mode" }` | `.2.CONTROL_MODE` |
| `modeCurrent` | `.2.COMFORT_MODE` |  |  | `.2.COMFORT_MODE` |
| `lowBatteryAlarmReporting` | `.2.LOWBAT_REPORTING` |  |  | `.2.LOWBAT_REPORTING` |
| `modeManu` | `.2.MANU_MODE` |  |  | `.2.MANU_MODE` |
| `partyTemperature` | `.2.PARTY_TEMPERATURE` |  |  |  |
| `setTemperature` | `.2.SET_TEMPERATURE` |  |  | `.2.SET_TEMPERATURE` |
| `openWindow` | `.2.WINDOW_OPEN_REPORTING` |  |  | `.2.WINDOW_OPEN_REPORTING` |

#### HM-WDS40-TH-I

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `temperature` | `.1.TEMPERATURE` |  |  |  |
| `humidity` | `.1.HUMIDITY` |  |  |  |

#### HM-WDS10-TH-O

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `temperature` | `.1.TEMPERATURE` |  |  |  |
| `humidity` | `.1.HUMIDITY` |  |  |  |

#### HM-WDS30-OT2-SM

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `temperatureCh1` | `.1.TEMPERATURE` |  |  |  |
| `lowBatteryCh1` | `.1.LOWBAT` |  |  |  |
| `temperatureCh2` | `.2.TEMPERATURE` |  |  |  |
| `lowBatteryCh2` | `.2.LOWBAT` |  |  |  |
| `temperatureCh3` | `.3.TEMPERATURE` |  |  |  |
| `lowBatteryCh3` | `.3.LOWBAT` |  |  |  |
| `temperatureCh4` | `.4.TEMPERATURE` |  |  |  |
| `lowBatteryCh4` | `.4.LOWBAT` |  |  |  |
| `temperatureCh5` | `.5.TEMPERATURE` |  |  |  |
| `lowBatteryCh5` | `.5.LOWBAT` |  |  |  |
| `temperatureCh6` | `.6.TEMPERATURE` |  |  |  |
| `lowBatteryCh6` | `.6.LOWBAT` |  |  |  |

### Adapter hmip

#### HmIP-STH

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `temperature` | `.channels.1.actualTemperature` |  |  |  |
| `humidity` | `.channels.1.humidity` |  |  |  |
| `setTemperature` | `.channels.1.setPointTemperature` |  |  | `.channels.1.setPointTemperature` |

#### HmIP-eTRV-B

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `temperature` | `.channels.1.valveActualTemperature` |  |  |  |
| `setTemperature` | `.channels.1.setPointTemperature` |  |  | `.channels.1.setPointTemperature` |
| `valvePosition` | `.channels.1.valvePosition` |  |  |  |
| `valveState` | `.channels.1.valveState` |  |  |  |

#### HmIP-eTRV-2

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `temperature` | `.channels.1.valveActualTemperature` |  |  |  |
| `setTemperature` | `.channels.1.setPointTemperature` |  |  | `.channels.1.setPointTemperature` |

#### HmIP-WTH-2

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `temperature` | `.channels.1.actualTemperature` |  |  |  |
| `humidity` | `.channels.1.humidity` |  |  |  |
| `setTemperature` | `.channels.1.setPointTemperature` |  |  | `.channels.1.setPointTemperature` |
| `vapor` | `.channels.1.vaporAmount` |  |  |  |

