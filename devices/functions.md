# Gewerke

Die Gewerke definierten den Typs eines Geräts, z. B. Licht oder Heizung. 

Grundsätzlich kann durch den Benutzer in Jarvis alles frei definiert und konfiguriert werden. Die Gewerke liefern hierzu bestimmte Voreinstellungen als Grundlage (die jedoch überschrieben werden können).

*Hinweis*: Die Spalten der unten dargestellten Tabellen sind unter [Geräte](#konfiguration-der-datenpunkte-states) erläutert.


# Übersicht der Gewerke
- [Rollladen / Jalousie](#gewerk-rollladen--jalousie-blind)
- [Tür](#gewerk-tür-door)
- [Lüfter](#gewerk-lüfter-fan)
- [Heizung](#gewerk-heizung-heating)
- [Haushalt](#gewerk-haushalt-household)
- [Licht](#gewerk-licht-light)
- [Ort](#gewerk-ort-location)
- [Bewegungs-/Präsenzmelder](#gewerk-bewegungs-präsenzmelder-motion)
- [Rasenmäher-Roboter](#gewerk-rasenmäher-roboter-mower)
- [Szenen](#gewerk-szenen-scenes)
- [Sensor](#gewerk-sensor-sensor)
- [Server](#gewerk-server-server)
- [Rauchmelder](#gewerk-rauchmelder-smoke)
- [Steckdose](#gewerk-steckdose-socket)
- [Lautsprecher](#gewerk-lautsprecher-speaker)
- [Schalter](#gewerk-schalter-switch)
- [Fernseher](#gewerk-fernseher-tv)
- [Benutzer](#gewerk-benutzer-user)
- [Staubsauger-Roboter](#gewerk-staubsauger-roboter-vacuum)
- [Wetter-Station](#gewerk-wetter-station-weather-station)
- [Fenster](#gewerk-fenster-window)
- [Sonstige](#gewerk-sonstige-_defaults)


## Gewerk Rollladen / Jalousie (`blind`)
### vordefinierte Datenpunkte

| Datenpunkt Bezeichner | Datenpunkt Stil |Anzeige | Einheit | Icon | Icon Stil |
| `_any` | - | - | - | - | - |

| `level` | - | - | `%` | `{
   "default": "window-shutter-open",
   ">90": "window-shutter-open",
   "<=90": "window-shutter"
}` | - |

| `level2` | - | - | `%` | `{
   "default": "window-shutter-open",
   ">90": "window-shutter-open",
   "<=90": "window-shutter"
}` | - |

| `activity` | - | `{
   "true": "in Bewegung",
   "false": "keine"
}` | - | `{
   "true": "pan-vertical",
   "false": "dots-vertical"
}` | - |

### Beispielkonfiguration
#### Adapter hm-rpc
*HmIP-BBL*
- `level`
  - state: `.3.LEVEL`
  - action: `.4.LEVEL`
- `level2`
  - state: `.3.LEVEL2`
  - action: `.4.LEVEL2`
- `activity`
  - state: `.3.ACTIVITY_STATE`
- `stop`
  - action: `.4.STOP`
*HmIP-FROLL*
- `level`
  - state: `.3.LEVEL`
  - action: `.4.LEVEL`
- `activity`
  - state: `.3.ACTIVITY_STATE`
- `stop`
  - action: `.4.STOP`
*HmIP-BROLL*
- `level`
  - state: `.3.LEVEL`
  - action: `.4.LEVEL`
- `level2`
  - state: `.3.LEVEL2`
  - action: `.4.LEVEL2`
- `activity`
  - state: `.3.ACTIVITY_STATE`
- `stop`
  - action: `.4.STOP`
*HM-LC-Bl1-FM*
- `level`
  - state: `.1.LEVEL`
  - action: `.1.LEVEL`
- `activity`
  - state: `.1.WORKING`
- `stop`
  - action: `.1.STOP`
*HM-LC-Bl1PBU-FM*
- `level`
  - state: `.1.LEVEL`
  - action: `.1.LEVEL`
- `activity`
  - state: `.1.WORKING`
- `stop`
  - action: `.1.STOP`
*HmIPW-DRBL4*
- `levelCh1`
  - state: `.2.LEVEL`
  - action: `.2.LEVEL`
- `level2Ch1`
  - state: `.2.LEVEL_2`
  - action: `.2.LEVEL_2`
- `activityCh1`
  - state: `.2.PROCESS`
- `stopCh1`
  - action: `.2.STOP`
- `levelCh2`
  - state: `.6.LEVEL`
  - action: `.6.LEVEL`
- `level2Ch2`
  - state: `.6.LEVEL_2`
  - action: `.6.LEVEL_2`
- `activityCh2`
  - state: `.6.PROCESS`
- `stopCh2`
  - action: `.6.STOP`
- `levelCh3`
  - state: `.10.LEVEL`
  - action: `.10.LEVEL`
- `level2Ch3`
  - state: `.10.LEVEL_2`
  - action: `.10.LEVEL_2`
- `activityCh3`
  - state: `.10.PROCESS`
- `stopCh3`
  - action: `.10.STOP`
- `levelCh4`
  - state: `.14.LEVEL`
  - action: `.14.LEVEL`
- `level2Ch4`
  - state: `.14.LEVEL_2`
  - action: `.14.LEVEL_2`
- `activityCh4`
  - state: `.14.PROCESS`
- `stopCh4`
  - action: `.14.STOP`
#### Adapter hmip
*HmIP-BBL*
- `level`
  - state: `.channels.1.shutterLevel`
  - action: `.channels.1.shutterLevel`
- `activity`
  - state: `.channels.1.processing`
- `stop`
  - action: `.channels.1.stop`
*HmIP-BROLL*
- `level`
  - state: `.channels.1.shutterLevel`
  - action: `.channels.1.shutterLevel`
- `activity`
  - state: `.channels.1.processing`
- `stop`
  - action: `.channels.1.stop`
#### Adapter shelly
- `level`
  - state: `.Shutter.Position`
  - action: `.Shutter.Position`
- `activity`
  - state: `.Shutter.state`
  - action: `.Shutter.Pause`

## Gewerk Tür (`door`)
### vordefinierte Datenpunkte

| Datenpunkt Bezeichner | Datenpunkt Stil |Anzeige | Einheit | Icon | Icon Stil |
| `_any` | - | - | - | - | - |

| `open` | - | `{
   "0": "door#open#closed",
   "1": "door#open#opened",
   "false": "geschlossen",
   "true": "offen"
}` | - | `{
   "0": "window-closed-variant",
   "1": "window-open-variant",
   "false": "door-closed",
   "true": "door-open"
}` | - |

| `lock` | - | - | - | - | - |

### Beispielkonfiguration
#### Adapter hm-rpc
*HM-Sec-Key*
- `error`
  - state: `.1.ERROR`
- `lock`
  - state: `.1.OPEN`

## Gewerk Lüfter (`fan`)
### vordefinierte Datenpunkte

| Datenpunkt Bezeichner | Datenpunkt Stil |Anzeige | Einheit | Icon | Icon Stil |
| `_any` | - | - | - | - | - |

| `power` | - | - | - | `{
   "true": "fan",
   "false": "fan-off"
}` | - |


## Gewerk Heizung (`heating`)
### vordefinierte Datenpunkte

| Datenpunkt Bezeichner | Datenpunkt Stil |Anzeige | Einheit | Icon | Icon Stil |
| `_any` | - | - | - | - | - |

| `temperature` | - | - | `°C` | `"thermometer"` | - |

| `settemperature` | - | - | `°C` | `"thermometer-chevron-up"` | - |

| `humidity` | - | - | `%` | - | - |

| `boost` | - | - | - | `"radiator"` | - |

| `boostTime` | - | - | `min.` | `"clock-outline"` | - |

| `boostState` | - | - | - | - | - |

| `frost` | - | - | - | - | - |

| `windowState` | - | - | - | - | - |

| `partyMode` | - | - | - | - | - |

| `modeAuto` | - | - | - | `"brightness-auto"` | - |

| `modeManu` | - | - | - | - | - |

| `modeCurrent` | - | - | - | - | - |

| `modeLowering` | - | - | - | - | - |

| `modeControl` | - | - | - | `"list-status"` | - |

| `valve` | - | - | `%` | `"valve"` | - |

| `valvePosition` | - | - | - | - | - |

| `valveState` | - | - | - | - | - |

### Beispielkonfiguration
#### Adapter hm-rpc
*HmIP-STHD*
- `temperature`
  - state: `.1.ACTUAL_TEMPERATURE`
- `setTemperature`
  - state: `.1.SET_POINT_TEMPERATURE`
  - action: `.1.SET_POINT_TEMPERATURE`
- `humidity`
  - state: `.1.HUMIDITY`
- `frost`
  - state: `.1.FROST_PROTECTION`
- `boost`
  - state: `.1.BOOST_MODE`
  - action: `.1.BOOST_MODE`
- `boostTime`
  - state: `.1.BOOST_TIME`
  - action: `.1.BOOST_TIME`
- `windowState`
  - state: `.1.WINDOW_STATE`
- `partyMode`
  - state: `.1.PARTY_MODE`
  - action: `.1.PARTY_MODE`
*HmIP-eTRV-B*
- `temperature`
  - state: `.1.ACTUAL_TEMPERATURE`
- `setTemperature`
  - state: `.1.SET_POINT_TEMPERATURE`
  - action: `.1.SET_POINT_TEMPERATURE`
- `frost`
  - state: `.1.FROST_PROTECTION`
- `boost`
  - state: `.1.BOOST_MODE`
  - action: `.1.BOOST_MODE`
- `boostTime`
  - state: `.1.BOOST_TIME`
  - action: `.1.BOOST_TIME`
- `windowState`
  - state: `.1.WINDOW_STATE`
- `partyMode`
  - state: `.1.PARTY_MODE`
  - action: `.1.PARTY_MODE`
*HmIP-eTRV*
- `temperature`
  - state: `.1.ACTUAL_TEMPERATURE`
- `setTemperature`
  - state: `.1.SET_POINT_TEMPERATURE`
  - action: `.1.SET_POINT_TEMPERATURE`
- `frost`
  - state: `.1.FROST_PROTECTION`
- `boost`
  - state: `.1.BOOST_MODE`
  - action: `.1.BOOST_MODE`
- `boostTime`
  - state: `.1.BOOST_TIME`
  - action: `.1.BOOST_TIME`
- `windowState`
  - state: `.1.WINDOW_STATE`
- `partyMode`
  - state: `.1.PARTY_MODE`
  - action: `.1.PARTY_MODE`
- `level`
  - state: `.1.LEVEL`
  - action: `.1.LEVEL`
- `valve`
  - state: `.1.VALVE_STATE`
  - action: `.1.VALVE_STATE`
*HmIP-eTRV-2*
- `temperature`
  - state: `.1.ACTUAL_TEMPERATURE`
- `setTemperature`
  - state: `.1.SET_POINT_TEMPERATURE`
  - action: `.1.SET_POINT_TEMPERATURE`
- `frost`
  - state: `.1.FROST_PROTECTION`
- `boost`
  - state: `.1.BOOST_MODE`
  - action: `.1.BOOST_MODE`
- `boostTime`
  - state: `.1.BOOST_TIME`
  - action: `.1.BOOST_TIME`
- `windowState`
  - state: `.1.WINDOW_STATE`
- `partyMode`
  - state: `.1.PARTY_MODE`
  - action: `.1.PARTY_MODE`
- `level`
  - state: `.1.LEVEL`
  - action: `.1.LEVEL`
- `valve`
  - state: `.1.VALVE_STATE`
  - action: `.1.VALVE_STATE`
*HmIP-BWTH*
- `temperature`
  - state: `.1.ACTUAL_TEMPERATURE`
- `setTemperature`
  - state: `.1.SET_POINT_TEMPERATURE`
  - action: `.1.SET_POINT_TEMPERATURE`
- `humidity`
  - state: `.1.HUMIDITY`
- `boost`
  - state: `.1.BOOST_MODE`
  - action: `.1.BOOST_MODE`
*HmIP-WTH*
- `temperature`
  - state: `.1.ACTUAL_TEMPERATURE`
- `setTemperature`
  - state: `.1.SET_POINT_TEMPERATURE`
  - action: `.1.SET_POINT_TEMPERATURE`
- `humidity`
  - state: `.1.HUMIDITY`
- `boost`
  - state: `.1.BOOST_MODE`
  - action: `.1.BOOST_MODE`
*HmIP-WTH-2*
- `temperature`
  - state: `.1.ACTUAL_TEMPERATURE`
- `setTemperature`
  - state: `.1.SET_POINT_TEMPERATURE`
  - action: `.1.SET_POINT_TEMPERATURE`
- `humidity`
  - state: `.1.HUMIDITY`
- `boost`
  - state: `.1.BOOST_MODE`
  - action: `.1.BOOST_MODE`
*HM-CC-RT-DN*
- `temperature`
  - state: `.4.ACTUAL_TEMPERATURE`
- `setTemperature`
  - state: `.4.SET_TEMPERATURE`
  - action: `.4.SET_TEMPERATURE`
- `boost`
  - state: `.4.BOOST_MODE`
  - action: `.4.BOOST_MODE`
- `batteryState`
  - state: `.4.BATTERY_STATE`
- `partyTemperature`
  - state: `.4.PARTY_TEMPERATURE`
- `modeAuto`
  - state: `.4.AUTO_MODE`
  - action: `.4.AUTO_MODE`
- `modeManu`
  - state: `.4.MANU_MODE`
  - action: `.4.MANU_MODE`
- `boostState`
  - state: `.4.BOOST_STATE`
  - action: `.4.BOOST_STATE`
- `modeCurrent`
  - state: `.4.COMFORT_MODE`
  - action: `.4.COMFORT_MODE`
- `modeLowering`
  - state: `.4.LOWERING_MODE`
  - action: `.4.LOWERING_MODE`
- `modeControl`
  - state: `.4.CONTROL_MODE`
  - action: `.4.CONTROL_MODE`
  - display: `[object Object]`
- `valve`
  - state: `.4.VALVE_STATE`
  - action: `.4.VALVE_STATE`
*HM-TC-IT-WM-W-EU*
- `temperature`
  - state: `.1.TEMPERATURE`
- `humidity`
  - state: `.1.HUMIDITY`
- `actualHumidity`
  - state: `.2.ACTUAL_HUMIDITY`
- `actualTemperature`
  - state: `.2.ACTUAL_TEMPERATURE`
- `modeAuto`
  - state: `.2.AUTO_MODE`
  - action: `.2.AUTO_MODE`
- `batteryState`
  - state: `.2.BATTERY_STATE`
- `boost`
  - state: `.2.BOOST_MODE`
  - action: `.2.BOOST_MODE`
- `boostState`
  - state: `.2.BOOST_STATE`
  - action: `.2.BOOST_STATE`
- `modeControl`
  - state: `.2.CONTROL_MODE`
  - action: `.2.CONTROL_MODE`
  - display: `[object Object]`
- `modeCurrent`
  - state: `.2.COMFORT_MODE`
  - action: `.2.COMFORT_MODE`
- `lowBatteryAlarmReporting`
  - state: `.2.LOWBAT_REPORTING`
  - action: `.2.LOWBAT_REPORTING`
- `modeManu`
  - state: `.2.MANU_MODE`
  - action: `.2.MANU_MODE`
- `partyTemperature`
  - state: `.2.PARTY_TEMPERATURE`
- `setTemperature`
  - state: `.2.SET_TEMPERATURE`
  - action: `.2.SET_TEMPERATURE`
- `openWindow`
  - state: `.2.WINDOW_OPEN_REPORTING`
  - action: `.2.WINDOW_OPEN_REPORTING`
*HM-WDS40-TH-I*
- `temperature`
  - state: `.1.TEMPERATURE`
- `humidity`
  - state: `.1.HUMIDITY`
*HM-WDS10-TH-O*
- `temperature`
  - state: `.1.TEMPERATURE`
- `humidity`
  - state: `.1.HUMIDITY`
*HM-WDS30-OT2-SM*
- `temperatureCh1`
  - state: `.1.TEMPERATURE`
- `lowBatteryCh1`
  - state: `.1.LOWBAT`
- `temperatureCh2`
  - state: `.2.TEMPERATURE`
- `lowBatteryCh2`
  - state: `.2.LOWBAT`
- `temperatureCh3`
  - state: `.3.TEMPERATURE`
- `lowBatteryCh3`
  - state: `.3.LOWBAT`
- `temperatureCh4`
  - state: `.4.TEMPERATURE`
- `lowBatteryCh4`
  - state: `.4.LOWBAT`
- `temperatureCh5`
  - state: `.5.TEMPERATURE`
- `lowBatteryCh5`
  - state: `.5.LOWBAT`
- `temperatureCh6`
  - state: `.6.TEMPERATURE`
- `lowBatteryCh6`
  - state: `.6.LOWBAT`
#### Adapter hmip
*HmIP-STH*
- `temperature`
  - state: `.channels.1.actualTemperature`
- `humidity`
  - state: `.channels.1.humidity`
- `setTemperature`
  - state: `.channels.1.setPointTemperature`
  - action: `.channels.1.setPointTemperature`
*HmIP-eTRV-B*
- `temperature`
  - state: `.channels.1.valveActualTemperature`
- `setTemperature`
  - state: `.channels.1.setPointTemperature`
  - action: `.channels.1.setPointTemperature`
- `valvePosition`
  - state: `.channels.1.valvePosition`
- `valveState`
  - state: `.channels.1.valveState`
*HmIP-eTRV-2*
- `temperature`
  - state: `.channels.1.valveActualTemperature`
- `setTemperature`
  - state: `.channels.1.setPointTemperature`
  - action: `.channels.1.setPointTemperature`
*HmIP-WTH-2*
- `temperature`
  - state: `.channels.1.actualTemperature`
- `humidity`
  - state: `.channels.1.humidity`
- `setTemperature`
  - state: `.channels.1.setPointTemperature`
  - action: `.channels.1.setPointTemperature`
- `vapor`
  - state: `.channels.1.vaporAmount`

## Gewerk Haushalt (`household`)
### vordefinierte Datenpunkte

| Datenpunkt Bezeichner | Datenpunkt Stil |Anzeige | Einheit | Icon | Icon Stil |
| `_any` | - | - | - | - | - |

| `power` | - | - | - | - | - |

| `consumption` | - | - | `W` | `{
   "default": "mdi-power-plug-off-outline",
   ">0": "mdi-power-plug"
}` | - |

| `meter` | - | - | `W` | `{
   "default": "mdi-power-plug-off-outline",
   ">0": "mdi-power-plug"
}` | - |


## Gewerk Licht (`light`)
### vordefinierte Datenpunkte

| Datenpunkt Bezeichner | Datenpunkt Stil |Anzeige | Einheit | Icon | Icon Stil |
| `_any` | - | - | - | - | - |

| `on` | - | - | - | `{
   "true": "lightbulb-on",
   "false": "lightbulb-off-outline"
}` | - |

| `power` | - | - | - | `{
   "true": "lightbulb-on",
   "false": "lightbulb-off-outline"
}` | - |

| `dimmer` | `{
   "0": {
      "color": "#999"
   }
}` | `{
   "0": "aus"
}` | `val => val > 0 ? \ %\ : null` | `{
   "0": "lightbulb-off-outline",
   "default": "lightbulb-on"
}` | - |

| `level` | `{
   "0": {
      "color": "#999"
   }
}` | `{
   "0": "aus"
}` | `val => val > 0 ? \ %\ : null` | `{
   "0": "lightbulb-off-outline",
   "default": "lightbulb-on"
}` | - |

| `ct` | - | - | `°K` | `{
   "default": "thermometer"
}` | - |

| `colortemperature` | - | - | `°K` | `{
   "default": "thermometer"
}` | - |

| `hue` | - | - | `°` | `{
   "default": "palette"
}` | - |

| `rgb` | - | - | - | `{
   "default": "palette"
}` | - |

| `hsv` | - | - | - | `{
   "default": "palette"
}` | - |

| `hex` | - | - | - | `{
   "default": "palette"
}` | - |

### Beispielkonfiguration
#### Adapter hm-rpc
*HmIP-BSM*
- `power`
  - state: `.4.STATE`
  - action: `.4.STATE`
- `powerMeter`
  - state: `.7.POWER`
- `powerVoltage`
  - state: `.7.VOLTAGE`
- `powerFrequency`
  - state: `.7.FREQUENCY`
*HmIP-BSL*
- `power`
  - state: `.4.STATE`
  - action: `.4.STATE`
- `levelTop`
  - state: `.8.LEVEL`
  - action: `.8.LEVEL`
- `colorTop`
  - state: `.8.COLOR`
  - action: `.8.COLOR`
  - display: `[object Object]`
- `levelBottom`
  - state: `.12.LEVEL`
  - action: `.12.LEVEL`
- `colorBottom`
  - state: `.12.COLOR`
  - action: `.12.COLOR`
  - display: `[object Object]`
*HmIP-BRC2*
- `power`
  - state: `.3.STATE`
  - action: `.4.STATE`
*HmIP-BDT*
- `level`
  - state: `.3.LEVEL`
  - action: `.4.LEVEL`
*HM-LC-Dim1T-FM*
- `level`
  - state: `.1.LEVEL`
  - action: `.1.LEVEL`
- `timerOff`
  - state: `.1.ON_TIME`
  - action: `.1.ON_TIME`
- `timerOn`
  - state: `.1.RAMP_TIME`
  - action: `.1.RAMP_TIME`
*HM-LC-RGBW-WM*
- `level`
  - state: `.1.LEVEL`
  - action: `.1.LEVEL`
- `timerOff`
  - state: `.1.ON_TIME`
  - action: `.1.ON_TIME`
- `timerOn`
  - state: `.1.RAMP_TIME`
  - action: `.1.RAMP_TIME`
- `hue`
  - state: `.2.COLOR`
  - action: `.2.COLOR`
*HM-LC-Sw1PBU-FM*
- `power`
  - state: `.1.STATE`
  - action: `.1.STATE`
*HM-LC-Sw1-FM*
- `power`
  - state: `.1.STATE`
  - action: `.1.STATE`
- `timerOff`
  - state: `.1.ON_TIME`
  - action: `.1.ON_TIME`
- `activity`
  - state: `.1.WORKING`
  - action: `.1.WORKING`
*HM-LC-Sw1-DR*
- `power`
  - state: `.1.STATE`
  - action: `.1.STATE`
- `timerOff`
  - state: `.1.ON_TIME`
  - action: `.1.ON_TIME`
*HM-LC-Sw2-FM*
- `power`
  - state: `.1.STATE`
  - action: `.1.STATE`
- `timerOff`
  - state: `.1.ON_TIME`
  - action: `.1.ON_TIME`
- `powerCh2`
  - state: `.2.STATE`
  - action: `.2.STATE`
- `timerOffCh2`
  - state: `.2.ON_TIME`
  - action: `.2.ON_TIME`
*HM-LC-Sw4-DR*
- `power`
  - state: `.1.STATE`
  - action: `.1.STATE`
- `timerOff`
  - state: `.1.ON_TIME`
  - action: `.1.ON_TIME`
- `powerCh2`
  - state: `.2.STATE`
  - action: `.2.STATE`
- `timerOffCh2`
  - state: `.2.ON_TIME`
  - action: `.2.ON_TIME`
- `powerCh3`
  - state: `.3.STATE`
  - action: `.3.STATE`
- `timerOffCh3`
  - state: `.3.ON_TIME`
  - action: `.3.ON_TIME`
- `powerCh4`
  - state: `.4.STATE`
  - action: `.4.STATE`
- `timerOffCh4`
  - state: `.4.ON_TIME`
  - action: `.4.ON_TIME`
*HM-LC-Dim1TPBU-FM*
- `level`
  - state: `.1.LEVEL`
  - action: `.1.LEVEL`
*HM-LC-Dim1T-Pl-3*
- `level`
  - state: `.1.LEVEL`
  - action: `.1.LEVEL`
- `timerOff`
  - state: `.1.ON_TIME`
  - action: `.1.ON_TIME`
- `timerOn`
  - state: `.1.RAMP_TIME`
  - action: `.1.RAMP_TIME`
#### Adapter hue-extended
- `power`
  - state: `.action.on`
  - action: `.action.on`
- `level`
  - state: `.action.level`
  - action: `.action.level`
- `colorTemperature`
  - state: `.action.colorTemperature`
  - action: `.action.colorTemperature`
- `hue`
  - state: `.action.hue`
  - action: `.action.hue`
- `hex`
  - state: `.action.hex`
  - action: `.action.hex`
#### Adapter hue
- `power`
  - state: `.on`
  - action: `.on`
- `level`
  - state: `.level`
  - action: `.level`
- `colorTemperature`
  - state: `.ct`
  - action: `.ct`
- `hue`
  - state: `.hue`
  - action: `.hue`
- `reachability`
  - state: `.reachable`
#### Adapter mqtt
- `dimmer`
  - state: `.Dimmer`
  - action: `.Dimmer`
- `ct`
  - state: `.CT`
  - action: `.CT`
  - properties: `[object Object]`
- `hue`
  - state: `.Hue`
  - action: `.Hue`
- `sat`
  - state: `.Saturation`
  - action: `.Saturation`
#### Adapter shelly
- `power`
  - state: `.lights.Switch`
  - action: `.lights.Switch`
- `level`
  - state: `.lights.brightness`
  - action: `.lights.brightness`

## Gewerk Ort (`location`)
### vordefinierte Datenpunkte

| Datenpunkt Bezeichner | Datenpunkt Stil |Anzeige | Einheit | Icon | Icon Stil |
| `_any` | - | - | - | - | - |

| `position` | - | - | - | `"map-marker"` | - |

| `presence` | - | `{
   "true": "anwesend",
   "false": "abwesend"
}` | - | `{
   "true": "map-marker-radius",
   "false": "map-marker-remove-outline"
}` | - |

| `users` | - | `{
   "": "niemand anwesend"
}` | - | `{
   "": "account-group-outline",
   "default": "account-group"
}` | - |


## Gewerk Bewegungs-/Präsenzmelder (`motion`)
### vordefinierte Datenpunkte

| Datenpunkt Bezeichner | Datenpunkt Stil |Anzeige | Einheit | Icon | Icon Stil |
| `_any` | - | - | - | - | - |

| `motion` | - | - | - | `{
   "true": "motion-sensor",
   "false": "motion-sensor-off"
}` | - |

| `presence` | - | - | - | `{
   "true": "motion-sensor",
   "false": "motion-sensor-off"
}` | - |

### Beispielkonfiguration
#### Adapter hm-rpc
*HmIP-SMI55*
- `motion`
  - state: `.3.MOTION`
- `brightness`
  - state: `.3.BRIGHTNESS`
*HmIP-SMI*
- `motion`
  - state: `.1.MOTION`
- `illumination`
  - state: `.1.ILLUMINATION`
*HmIP-SMO-A*
- `motion`
  - state: `.1.MOTION`
- `illumination`
  - state: `.1.ILLUMINATION`
*HmIP-SAM*
- `motion`
  - state: `.1.MOTION`
- `illumination`
  - state: `.1.ILLUMINATION`
*HmIP-SPI*
- `presence`
  - state: `.1.PRESENCE_DETECTION_STATE`
- `illumination`
  - state: `.1.ILLUMINATION`
*HM-PB-6-WM55*
- `PRESS_LONG1`
  - state: `.1.PRESS_LONG`
  - action: `.1.PRESS_LONG`
- `PRESS_SHORT1`
  - state: `.1.PRESS_SHORT`
  - action: `.1.PRESS_SHORT`
- `PRESS_LONG2`
  - state: `.2.PRESS_LONG`
  - action: `.2.PRESS_LONG`
- `PRESS_SHORT2`
  - state: `.2.PRESS_SHORT`
  - action: `.2.PRESS_SHORT`
- `PRESS_LONG3`
  - state: `.3.PRESS_LONG`
  - action: `.3.PRESS_LONG`
- `PRESS_SHORT3`
  - state: `.3.PRESS_SHORT`
  - action: `.3.PRESS_SHORT`
- `PRESS_LONG4`
  - state: `.4.PRESS_LONG`
  - action: `.4.PRESS_LONG`
- `PRESS_SHORT4`
  - state: `.4.PRESS_SHORT`
  - action: `.4.PRESS_SHORT`
- `PRESS_LONG5`
  - state: `.5.PRESS_LONG`
  - action: `.5.PRESS_LONG`
- `PRESS_SHORT5`
  - state: `.5.PRESS_SHORT`
  - action: `.5.PRESS_SHORT`
- `PRESS_LONG6`
  - state: `.6.PRESS_LONG`
  - action: `.6.PRESS_LONG`
- `PRESS_SHORT6`
  - state: `.6.PRESS_SHORT`
  - action: `.6.PRESS_SHORT`
*HM-Sen-MDIR-WM55*
- `PRESS_LONG_BOTTOM`
  - state: `.1.PRESS_LONG`
  - action: `.1.PRESS_LONG`
- `PRESS_SHORT_BOTTOM`
  - state: `.1.PRESS_SHORT`
  - action: `.1.PRESS_SHORT`
- `PRESS_LONG_TOP`
  - state: `.2.PRESS_LONG`
  - action: `.2.PRESS_LONG`
- `PRESS_SHORT_TOP`
  - state: `.2.PRESS_SHORT`
  - action: `.2.PRESS_SHORT`
- `motion`
  - state: `.3.MOTION`
- `illumination`
  - state: `.3.ILLUMINATION`
*HM-Sen-MDIR-O-2*
- `motion`
  - state: `.1.MOTION`
- `brightness`
  - state: `.1.BRIGHTNESS`
*HM-Sen-MDIR-O-3*
- `motion`
  - state: `.1.MOTION`
- `brightness`
  - state: `.1.BRIGHTNESS`
#### Adapter hmip
*HmIP-SMI*
- `motion`
  - state: `.channels.1.motionDetected`
- `illumination`
  - state: `.channels.1.illumination`

## Gewerk Rasenmäher-Roboter (`mower`)
### vordefinierte Datenpunkte

| Datenpunkt Bezeichner | Datenpunkt Stil |Anzeige | Einheit | Icon | Icon Stil |
| `_any` | - | - | - | - | - |


## Gewerk Szenen (`scenes`)
### vordefinierte Datenpunkte

| Datenpunkt Bezeichner | Datenpunkt Stil |Anzeige | Einheit | Icon | Icon Stil |

## Gewerk Sensor (`sensor`)
### vordefinierte Datenpunkte

| Datenpunkt Bezeichner | Datenpunkt Stil |Anzeige | Einheit | Icon | Icon Stil |
| `_any` | - | - | - | - | - |

| `temperature` | - | - | `°C` | `"mdi-thermometer"` | - |

| `humidity` | - | - | `%` | - | - |

| `illumination` | - | - | `lux` | `"mdi-brightness-7"` | - |

| `pressure` | - | - | `hPa` | `"mdi-air-purifier"` | - |

### Beispielkonfiguration
#### Adapter hm-rpc
*HM-Sec-TiS*
- `power`
  - state: `.1.STATE`
*HmIP-SLO*
- `illuminationAverage`
  - state: `.1.AVERAGE_ILLUMINATION`
  - unit: ` Lux`
- `illuminationCurrent`
  - state: `.1.CURRENT_ILLUMINATION`
  - unit: ` Lux`
- `illuminationHighest`
  - state: `.1.HIGHEST_ILLUMINATION`
  - unit: ` Lux`
- `illuminationLowest`
  - state: `.1.LOWEST_ILLUMINATION`
  - unit: ` Lux`
*HmIP-SWD*
- `alarm`
  - state: `.1.ALARMSTATE`
- `alarmMoisture`
  - state: `.1.MOISTURE_DETECTED`
- `alarmWaterlevel`
  - state: `.1.WATERLEVEL_DETECTED`
*HM-Sec-WDS-2*
- `alarm`
  - state: `.1.STATE`

## Gewerk Server (`server`)
### vordefinierte Datenpunkte

| Datenpunkt Bezeichner | Datenpunkt Stil |Anzeige | Einheit | Icon | Icon Stil |
| `_any` | - | - | - | - | - |

| `power` | - | - | - | `{
   "true": "server-network",
   "false": "server-network-off"
}` | - |


## Gewerk Rauchmelder (`smoke`)
### vordefinierte Datenpunkte

| Datenpunkt Bezeichner | Datenpunkt Stil |Anzeige | Einheit | Icon | Icon Stil |
| `_any` | - | - | - | - | - |

| `alarm` | - | - | - | `{
   "0": "mdi-alarm-light-outline",
   "1": "mdi-alarm-light",
   "2": "mdi-alarm-light",
   "3": "mdi-alarm-light",
   "true": "mdi-alarm-light",
   "false": "mdi-alarm-light-outline"
}` | - |

### Beispielkonfiguration
#### Adapter hm-rpc
*HmIP-SWSD*
- `alarm`
  - state: `.1.SMOKE_DETECTOR_ALARM_STATUS`
  - display: `[object Object]`
*HM-Sec-SD*
- `alarm`
  - state: `.1.STATE`
- `lowBatteryCh1`
  - state: `.1.LOWBAT`
*HM-Sec-SD-2*
- `alarm`
  - state: `.1.STATE`
- `lowBatteryCh1`
  - state: `.1.LOWBAT`
*HM-Sec-SD-2-Team*
- `alarm`
  - state: `.1.STATE`

## Gewerk Steckdose (`socket`)
### vordefinierte Datenpunkte

| Datenpunkt Bezeichner | Datenpunkt Stil |Anzeige | Einheit | Icon | Icon Stil |
| `_any` | - | - | - | - | - |

| `power` | - | - | - | - | - |

| `consumption` | - | - | `W` | `{
   "default": "mdi-power-plug-off-outline",
   ">0": "mdi-power-plug"
}` | - |

| `meter` | - | - | `W` | `{
   "default": "mdi-power-plug-off-outline",
   ">0": "mdi-power-plug"
}` | - |

### Beispielkonfiguration
#### Adapter hm-rpc
*HmIP-FSM*
- `power`
  - state: `.2.STATE`
  - action: `.2.STATE`
- `timerOff`
  - state: `.2.ON_TIME`
  - action: `.2.ON_TIME`
- `powerCurrent`
  - state: `.5.CURRENT`
  - unit: ` mA`
- `powerFrequency`
  - state: `.5.FREQUENCY`
- `powerCounter`
  - state: `.5.ENERGY_COUNTER`
  - unit: ` Wh`
- `powerMeter`
  - state: `.5.POWER`
  - unit: ` W`
- `powerVoltage`
  - state: `.5.VOLTAGE`
  - unit: ` V`
*HmIP-PS*
- `power`
  - state: `.3.STATE`
*HmIP-PSM*
- `power`
  - state: `.3.STATE`
- `meter`
  - state: `.6.POWER`
*HM-ES-PMSw1-Pl-DN-R1*
- `power`
  - state: `.1.STATE`
  - action: `.1.STATE`
- `timerOff`
  - state: `.1.ON_TIME`
  - action: `.1.ON_TIME`
- `powerCurrent`
  - state: `.2.CURRENT`
  - unit: ` mA`
- `powerFrequency`
  - state: `.2.FREQUENCY`
- `powerCounter`
  - state: `.2.ENERGY_COUNTER`
  - unit: ` Wh`
- `powerMeter`
  - state: `.2.POWER`
  - unit: ` W`
- `powerVoltage`
  - state: `.2.VOLTAGE`
  - unit: ` V`
*HM-LC-Sw1-Pl-2*
- `power`
  - state: `.1.STATE`
  - action: `.1.STATE`
- `timerOff`
  - state: `.1.ON_TIME`
  - action: `.1.ON_TIME`
*HM-LC-Sw1-Pl-DN-R1*
- `power`
  - state: `.1.STATE`
  - action: `.1.STATE`
- `timerOff`
  - state: `.1.ON_TIME`
  - action: `.1.ON_TIME`
*HM-ES-PMSw1-DR*
- `power`
  - state: `.1.STATE`
  - action: `.1.STATE`
- `timerOff`
  - state: `.1.ON_TIME`
  - action: `.1.ON_TIME`
- `boot`
  - state: `.2.BOOT`
  - action: `.2.BOOT`
- `powerCurrent`
  - state: `.2.CURRENT`
  - unit: ` mA`
- `powerFrequency`
  - state: `.2.FREQUENCY`
- `powerCounter`
  - state: `.2.ENERGY_COUNTER`
  - unit: ` Wh`
- `powerMeter`
  - state: `.2.POWER`
  - unit: ` W`
- `powerVoltage`
  - state: `.2.VOLTAGE`
  - unit: ` V`
*HM-ES-PMSw1-Pl*
- `power`
  - state: `.1.STATE`
  - action: `.1.STATE`
- `timerOff`
  - state: `.1.ON_TIME`
  - action: `.1.ON_TIME`
- `boot`
  - state: `.2.BOOT`
  - action: `.2.BOOT`
- `powerCurrent`
  - state: `.2.CURRENT`
  - unit: ` mA`
- `powerFrequency`
  - state: `.2.FREQUENCY`
- `powerCounter`
  - state: `.2.ENERGY_COUNTER`
  - unit: ` Wh`
- `powerMeter`
  - state: `.2.POWER`
  - unit: ` W`
- `powerVoltage`
  - state: `.2.VOLTAGE`
  - unit: ` V`
#### Adapter hmip
*HmIP-PS*
- `power`
  - state: `.channels.1.on`
  - action: `.channels.1.on`

## Gewerk Lautsprecher (`speaker`)
### vordefinierte Datenpunkte

| Datenpunkt Bezeichner | Datenpunkt Stil |Anzeige | Einheit | Icon | Icon Stil |
| `_any` | - | - | - | - | - |


## Gewerk Schalter (`switch`)
### vordefinierte Datenpunkte

| Datenpunkt Bezeichner | Datenpunkt Stil |Anzeige | Einheit | Icon | Icon Stil |
| `power` | - | - | - | - | - |

### Beispielkonfiguration
#### Adapter hm-rpc
*HmIP-WRC2*
- `PRESS_LONG_BOTTOM`
  - state: `.1.PRESS_LONG`
  - action: `.1.PRESS_LONG`
- `PRESS_SHORT_BOTTOM`
  - state: `.1.PRESS_SHORT`
  - action: `.1.PRESS_SHORT`
- `PRESS_LONG_TOP`
  - state: `.2.PRESS_LONG`
  - action: `.2.PRESS_LONG`
- `PRESS_SHORT_TOP`
  - state: `.2.PRESS_SHORT`
  - action: `.2.PRESS_SHORT`
*HM-RC-2-PBU-FM*
- `PRESS_CONT_BOTTOM`
  - state: `.1.PRESS_CONT`
  - action: `.1.PRESS_CONT`
- `PRESS_LONG_BOTTOM`
  - state: `.1.PRESS_LONG`
  - action: `.1.PRESS_LONG`
- `PRESS_LONGRELEASE_BOTTOM`
  - state: `.1.PRESS_LONG_RELEASE`
  - action: `.1.PRESS_LONG_RELEASE`
- `PRESS_SHORT_BOTTOM`
  - state: `.1.PRESS_SHORT`
  - action: `.1.PRESS_SHORT`
- `PRESS_CONT_TOP`
  - state: `.2.PRESS_CONT`
  - action: `.2.PRESS_CONT`
- `PRESS_LONG_TOP`
  - state: `.2.PRESS_LONG`
  - action: `.2.PRESS_LONG`
- `PRESS_LONGRELEASE_TOP`
  - state: `.2.PRESS_LONG_RELEASE`
  - action: `.2.PRESS_LONG_RELEASE`
- `PRESS_SHORT_TOP`
  - state: `.2.PRESS_SHORT`
  - action: `.2.PRESS_SHORT`
*HM-LC-Sw1-DR*
- `power`
  - state: `.1.STATE`
  - action: `.1.STATE`
*HM-LC-SW1-FM*
- `power`
  - state: `.1.STATE`
  - action: `.1.STATE`
*HM-PB-2-WM55*
- `lowBatteryCh1`
  - state: `.1.LOWBAT`
- `PRESS_LONG_BOTTOM`
  - state: `.1.PRESS_LONG`
  - action: `.1.PRESS_LONG`
- `PRESS_SHORT_BOTTOM`
  - state: `.1.PRESS_SHORT`
  - action: `.1.PRESS_SHORT`
- `PRESS_LONG_TOP`
  - state: `.2.PRESS_LONG`
  - action: `.2.PRESS_LONG`
- `PRESS_SHORT_TOP`
  - state: `.2.PRESS_SHORT`
  - action: `.2.PRESS_SHORT`
*HB-UNI-SenAct-4-4-RC*
- `state1`
  - state: `.1.STATE`
- `state2`
  - state: `.2.STATE`
- `state3`
  - state: `.3.STATE`
- `state4`
  - state: `.4.STATE`
- `PRESS_LONG1`
  - state: `.5.PRESS_LONG`
  - action: `.5.PRESS_LONG`
- `PRESS_SHORT1`
  - state: `.5.PRESS_SHORT`
  - action: `.5.PRESS_SHORT`
- `PRESS_LONG2`
  - state: `.6.PRESS_LONG`
  - action: `.6.PRESS_LONG`
- `PRESS_SHORT2`
  - state: `.6.PRESS_SHORT`
  - action: `.6.PRESS_SHORT`
- `PRESS_LONG3`
  - state: `.7.PRESS_LONG`
  - action: `.7.PRESS_LONG`
- `PRESS_SHORT3`
  - state: `.7.PRESS_SHORT`
  - action: `.7.PRESS_SHORT`
- `PRESS_LONG4`
  - state: `.8.PRESS_LONG`
  - action: `.8.PRESS_LONG`
- `PRESS_SHORT4`
  - state: `.8.PRESS_SHORT`
  - action: `.8.PRESS_SHORT`

## Gewerk Fernseher (`tv`)
### vordefinierte Datenpunkte

| Datenpunkt Bezeichner | Datenpunkt Stil |Anzeige | Einheit | Icon | Icon Stil |
| `_any` | - | - | - | - | - |

| `power` | - | - | - | `{
   "true": "television-clean",
   "false": "television-off"
}` | - |


## Gewerk Benutzer (`user`)
### vordefinierte Datenpunkte

| Datenpunkt Bezeichner | Datenpunkt Stil |Anzeige | Einheit | Icon | Icon Stil |
| `_any` | - | - | - | - | - |

| `position` | - | - | - | `"map-marker"` | - |

| `location` | - | - | - | `"account"` | - |

| `battery` | - | - | - | - | - |


## Gewerk Staubsauger-Roboter (`vacuum`)
### vordefinierte Datenpunkte

| Datenpunkt Bezeichner | Datenpunkt Stil |Anzeige | Einheit | Icon | Icon Stil |
| `_any` | - | - | - | - | - |


## Gewerk Wetter-Station (`weather-station`)
### vordefinierte Datenpunkte

| Datenpunkt Bezeichner | Datenpunkt Stil |Anzeige | Einheit | Icon | Icon Stil |
| `_any` | - | - | - | - | - |

| `humidity` | - | - | - | - | - |

| `wind` | - | - | - | - | - |

| `temperature` | - | - | - | - | - |

| `illumination` | - | - | - | `"mdi-brightness-7"` | - |

| `sunshineduration` | - | - | - | `"mdi-weather-sunny"` | - |

### Beispielkonfiguration
#### Adapter hm-rpc
*HmIP-STHO*
- `temperature`
  - state: `.1.ACTUAL_TEMPERATURE`
- `humidity`
  - state: `.1.HUMIDITY`
*HmIP-STHO-A*
- `temperature`
  - state: `.1.ACTUAL_TEMPERATURE`
- `humidity`
  - state: `.1.HUMIDITY`
*HmIP-SWO-B*
- `humidity`
  - state: `.1.HUMIDITY`
- `wind`
  - state: `.1.WIND_SPEED`
- `temperature`
  - state: `.1.ACTUAL_TEMPERATURE`
- `illumination`
  - state: `.1.ILLUMINATION`
- `sunshineDuration`
  - state: `.1.SUNSHINEDURATION`
*HmIP-SWO-PL*
- `humidity`
  - state: `.1.HUMIDITY`
- `wind`
  - state: `.1.WIND_SPEED`
- `temperature`
  - state: `.1.ACTUAL_TEMPERATURE`
- `illumination`
  - state: `.1.ILLUMINATION`
- `sunshineDuration`
  - state: `.1.SUNSHINEDURATION`
- `raining`
  - state: `.1.RAINING`
- `rainCounter`
  - state: `.1.RAIN_COUNTER`
*HM-WDS40-TH-I-2*
- `temperature`
  - state: `.1.TEMPERATURE`
- `humidity`
  - state: `.1.HUMIDITY`
#### Adapter hmip
*HmIP-STHO*
- `temperature`
  - state: `.channels.1.actualTemperature`
- `humidity`
  - state: `.channels.1.humidity`
- `vapor`
  - state: `.channels.1.vaporAmount`
- `display`
  - state: `.channels.1.display`
*HmIP-STHO-A*
- `temperature`
  - state: `.1.ACTUAL_TEMPERATURE`
- `humidity`
  - state: `.1.HUMIDITY`
*HmIP-SWO-B*
- `humidity`
  - state: `.1.HUMIDITY`
- `wind`
  - state: `.1.WIND_SPEED`
- `temperature`
  - state: `.1.ACTUAL_TEMPERATURE`
- `illumination`
  - state: `.1.ILLUMINATION`
- `sunshineduration`
  - state: `.1.SUNSHINEDURATION`

## Gewerk Fenster (`window`)
### vordefinierte Datenpunkte

| Datenpunkt Bezeichner | Datenpunkt Stil |Anzeige | Einheit | Icon | Icon Stil |
| `_any` | - | - | - | - | - |

| `open` | - | `{
   "0": "geschlossen",
   "1": "offen",
   "2": "offen",
   "false": "geschlossen",
   "true": "offen"
}` | - | `{
   "0": "window-closed-variant",
   "1": "window-open-variant",
   "false": "window-closed-variant",
   "true": "window-open-variant"
}` | - |

### Beispielkonfiguration
#### Adapter hm-rpc
*HmIP-SWDM*
- `open`
  - state: `.1.STATE`
*HmIP-SWDO-I*
- `open`
  - state: `.1.STATE`
*HmIP-SWDO*
- `open`
  - state: `.1.STATE`
*HmIP-SRH*
- `open`
  - state: `.1.STATE`
  - display: `[object Object]`
*HM-Sec-RHS*
- `open`
  - state: `.1.STATE`
  - display: `[object Object]`
*HM-Sec-Sco*
- `open`
  - state: `.1.STATE`
*HM-Sec-SC-2*
- `open`
  - state: `.1.STATE`
#### Adapter hmip
*HmIP-SWDO*
- `open`
  - state: `.channels.1.windowOpen`
*HmIP-SWDO-I*
- `open`
  - state: `.channels.1.windowOpen`
*HmIP-SRH*
- `open`
  - state: `.channels.1.windowOpen`
- `state`
  - state: `.channels.1.windowState`
  - display: `[object Object]`

## Gewerk Sonstige (`_defaults`)
### vordefinierte Datenpunkte

| Datenpunkt Bezeichner | Datenpunkt Stil |Anzeige | Einheit | Icon | Icon Stil |
| `_any` | `{
   "true": {
      "color": "#090",
      "fontWeight": "bold"
   },
   "false": {
      "color": "#999"
   }
}` | `{
   "true": "an",
   "false": "aus"
}` | - | - | - |

| `battery` | - | - | `%` | `{
   ">80": "battery-high",
   "<=80": "battery-medium",
   "<=30": "battery-low",
   "<=10": "battery-outline blink",
   "<=5": "battery-alert-variant-outline blink"
}` | `{
   "<=10": {
      "color": "#900"
   }
}` |

| `firmware` | - | `{
   "true": "Update verfügbar",
   "false": "kein Update"
}` | - | `{
   "true": "mdi-cog-refresh",
   "false": "mdi-cog-outline"
}` | - |

| `frost` | - | - | - | `{
   "default": "mdi-snowflake"
}` | - |

| `humidity` | - | - | `%` | `"water-percent"` | - |

| `illuminance` | - | - | `lux` | - | - |

| `level` | - | - | `%` | - | - |

| `lowbattery` | `{
   "true": {
      "color": "#900",
      "fontWeight": "bold"
   },
   "false": {
      "color": "#999"
   }
}` | `{
   "true": "niedrig",
   "false": "voll"
}` | - | `{
   "true": "battery-alert-variant-outline",
   "false": "battery-high"
}` | - |

| `position` | - | - | - | `"map-marker"` | - |

| `power` | - | - | - | `"power"` | - |

| `config` | - | - | - | `{
   "default": "mdi-cog"
}` | - |

| `connectivity` | - | - | - | `{
   "default": "mdi-wifi-arrow-left-right"
}` | - |

| `reachability` | `{
   "true": {
      "color": "#090"
   },
   "false": {
      "color": "#900",
      "fontWeight": "bold"
   }
}` | `{
   "true": "erreichbar",
   "false": "nicht erreichbar"
}` | - | `{
   "true": "lan-connect",
   "false": "lan-disconnect"
}` | - |

| `rssi` | - | - | - | `{
   "default": "mdi-antenna"
}` | - |

| `temperature` | - | - | `°C` | `"thermometer"` | - |

| `trigger` | - | - | - | `"power"` | - |

| `unreach` | `{
   "true": {
      "color": "#900",
      "fontWeight": "bold"
   },
   "false": {
      "color": "#090"
   }
}` | `{
   "true": "nicht erreichbar",
   "false": "erreichbar"
}` | - | `{
   "true": "lan-disconnect",
   "false": "lan-connect"
}` | - |

| `wind` | - | - | `km/h` | `"weather-windy"` | - |

### Beispielkonfiguration
#### Adapter hm-rpc
*HM-LC-Sw1PBU-FM*
- `powerCh1`
  - state: `.1.STATE`
  - action: `.1.STATE`
- `powerCh2`
  - state: `.2.STATE`
  - action: `.2.STATE`
- `powerCh3`
  - state: `.3.STATE`
  - action: `.3.STATE`
- `powerCh4`
  - state: `.4.STATE`
  - action: `.4.STATE`
- `powerCh5`
  - state: `.5.STATE`
  - action: `.5.STATE`
- `powerCh6`
  - state: `.6.STATE`
  - action: `.6.STATE`
- `powerCh7`
  - state: `.7.STATE`
  - action: `.7.STATE`
- `powerCh8`
  - state: `.8.STATE`
  - action: `.8.STATE`
- `powerCh9`
  - state: `.9.STATE`
  - action: `.9.STATE`
- `powerCh10`
  - state: `.10.STATE`
  - action: `.10.STATE`
- `powerCh11`
  - state: `.11.STATE`
  - action: `.11.STATE`
- `powerCh12`
  - state: `.12.STATE`
  - action: `.12.STATE`
- `powerCh13`
  - state: `.13.STATE`
  - action: `.13.STATE`
- `powerCh14`
  - state: `.14.STATE`
  - action: `.14.STATE`
- `powerCh15`
  - state: `.15.STATE`
  - action: `.15.STATE`
- `powerCh16`
  - state: `.16.STATE`
  - action: `.16.STATE`
#### Adapter mihome-vacuum
*state*
- `0`
  - 0: `.`
- `1`
  - 0: `i`
- `2`
  - 0: `n`
- `3`
  - 0: `f`
- `4`
  - 0: `o`
- `5`
  - 0: `.`
- `6`
  - 0: `q`
- `7`
  - 0: `u`
- `8`
  - 0: `e`
- `9`
  - 0: `u`
- `10`
  - 0: `e`
*action*
- `0`
  - 0: `.`
- `1`
  - 0: `c`
- `2`
  - 0: `o`
- `3`
  - 0: `n`
- `4`
  - 0: `t`
- `5`
  - 0: `r`
- `6`
  - 0: `o`
- `7`
  - 0: `l`
- `8`
  - 0: `.`
- `9`
  - 0: `c`
- `10`
  - 0: `l`
- `11`
  - 0: `e`
- `12`
  - 0: `a`
- `13`
  - 0: `r`
- `14`
  - 0: `Q`
- `15`
  - 0: `u`
- `16`
  - 0: `e`
- `17`
  - 0: `u`
- `18`
  - 0: `e`
#### Adapter mqtt
*version*
- `0`
  - 0: `.`
  - 1: `V`
  - 2: `e`
  - 3: `r`
  - 4: `s`
  - 5: `i`
  - 6: `o`
  - 7: `n`
- `1`
  - 0: `.`
  - 1: `I`
  - 2: `N`
  - 3: `F`
  - 4: `O`
  - 5: `.`
  - 6: `V`
  - 7: `e`
  - 8: `r`
  - 9: `s`
  - 10: `i`
  - 11: `o`
  - 12: `n`
*reachability*
- `0`
  - 0: `.`
- `1`
  - 0: `a`
- `2`
  - 0: `l`
- `3`
  - 0: `i`
- `4`
  - 0: `v`
- `5`
  - 0: `e`
*ip*
- `0`
  - 0: `.`
- `1`
  - 0: `I`
- `2`
  - 0: `N`
- `3`
  - 0: `F`
- `4`
  - 0: `O`
- `5`
  - 0: `.`
- `6`
  - 0: `I`
- `7`
  - 0: `P`
- `8`
  - 0: `A`
- `9`
  - 0: `d`
- `10`
  - 0: `d`
- `11`
  - 0: `r`
- `12`
  - 0: `e`
- `13`
  - 0: `s`
- `14`
  - 0: `s`
*signal*
- `0`
  - 0: `.`
- `1`
  - 0: `W`
- `2`
  - 0: `i`
- `3`
  - 0: `f`
- `4`
  - 0: `i`
- `5`
  - 0: `_`
- `6`
  - 0: `S`
- `7`
  - 0: `i`
- `8`
  - 0: `g`
- `9`
  - 0: `n`
- `10`
  - 0: `a`
- `11`
  - 0: `l`
*dataReceived*
- `0`
  - 0: `.`
- `1`
  - 0: `R`
- `2`
  - 0: `f`
- `3`
  - 0: `R`
- `4`
  - 0: `e`
- `5`
  - 0: `c`
- `6`
  - 0: `e`
- `7`
  - 0: `i`
- `8`
  - 0: `v`
- `9`
  - 0: `e`
- `10`
  - 0: `d`
- `11`
  - 0: `_`
- `12`
  - 0: `D`
- `13`
  - 0: `a`
- `14`
  - 0: `t`
- `15`
  - 0: `a`
*power*
- `state`
  - 0: `.`
  - 1: `P`
  - 2: `O`
  - 3: `W`
  - 4: `E`
  - 5: `R`
- `action`
  - 0: `.`
  - 1: `P`
  - 2: `O`
  - 3: `W`
  - 4: `E`
  - 5: `R`
*powerCurrent*
- `state`
  - 0: `.`
  - 1: `E`
  - 2: `N`
  - 3: `E`
  - 4: `R`
  - 5: `G`
  - 6: `Y`
  - 7: `_`
  - 8: `C`
  - 9: `u`
  - 10: `r`
  - 11: `r`
  - 12: `e`
  - 13: `n`
  - 14: `t`
- `unit`
  - 0: ` `
  - 1: `A`
*powerMeter*
- `state`
  - 0: `.`
  - 1: `E`
  - 2: `N`
  - 3: `E`
  - 4: `R`
  - 5: `G`
  - 6: `Y`
  - 7: `_`
  - 8: `P`
  - 9: `o`
  - 10: `w`
  - 11: `e`
  - 12: `r`
- `unit`
  - 0: ` `
  - 1: `W`
*powerConsumption*
- `state`
  - 0: `.`
  - 1: `E`
  - 2: `N`
  - 3: `E`
  - 4: `R`
  - 5: `G`
  - 6: `Y`
  - 7: `_`
  - 8: `T`
  - 9: `o`
  - 10: `t`
  - 11: `a`
  - 12: `l`
- `unit`
  - 0: ` `
  - 1: `k`
  - 2: `W`
  - 3: `h`
*powerConsumptionToday*
- `state`
  - 0: `.`
  - 1: `E`
  - 2: `N`
  - 3: `E`
  - 4: `R`
  - 5: `G`
  - 6: `Y`
  - 7: `_`
  - 8: `T`
  - 9: `o`
  - 10: `d`
  - 11: `a`
  - 12: `y`
- `unit`
  - 0: ` `
  - 1: `k`
  - 2: `W`
  - 3: `h`
*powerConsumptionYesterday*
- `state`
  - 0: `.`
  - 1: `E`
  - 2: `N`
  - 3: `E`
  - 4: `R`
  - 5: `G`
  - 6: `Y`
  - 7: `_`
  - 8: `Y`
  - 9: `e`
  - 10: `s`
  - 11: `t`
  - 12: `e`
  - 13: `r`
  - 14: `d`
  - 15: `a`
  - 16: `y`
- `unit`
  - 0: ` `
  - 1: `k`
  - 2: `W`
  - 3: `h`
*power1*
- `state`
  - 0: `.`
  - 1: `P`
  - 2: `O`
  - 3: `W`
  - 4: `E`
  - 5: `R`
  - 6: `1`
- `action`
  - 0: `.`
  - 1: `P`
  - 2: `O`
  - 3: `W`
  - 4: `E`
  - 5: `R`
  - 6: `1`
*power2*
- `state`
  - 0: `.`
  - 1: `P`
  - 2: `O`
  - 3: `W`
  - 4: `E`
  - 5: `R`
  - 6: `2`
- `action`
  - 0: `.`
  - 1: `P`
  - 2: `O`
  - 3: `W`
  - 4: `E`
  - 5: `R`
  - 6: `2`
*power3*
- `state`
  - 0: `.`
  - 1: `P`
  - 2: `O`
  - 3: `W`
  - 4: `E`
  - 5: `R`
  - 6: `3`
- `action`
  - 0: `.`
  - 1: `P`
  - 2: `O`
  - 3: `W`
  - 4: `E`
  - 5: `R`
  - 6: `3`
*power4*
- `state`
  - 0: `.`
  - 1: `P`
  - 2: `O`
  - 3: `W`
  - 4: `E`
  - 5: `R`
  - 6: `4`
- `action`
  - 0: `.`
  - 1: `P`
  - 2: `O`
  - 3: `W`
  - 4: `E`
  - 5: `R`
  - 6: `4`
*power5*
- `state`
  - 0: `.`
  - 1: `P`
  - 2: `O`
  - 3: `W`
  - 4: `E`
  - 5: `R`
  - 6: `5`
- `action`
  - 0: `.`
  - 1: `P`
  - 2: `O`
  - 3: `W`
  - 4: `E`
  - 5: `R`
  - 6: `5`
*power6*
- `state`
  - 0: `.`
  - 1: `P`
  - 2: `O`
  - 3: `W`
  - 4: `E`
  - 5: `R`
  - 6: `6`
- `action`
  - 0: `.`
  - 1: `P`
  - 2: `O`
  - 3: `W`
  - 4: `E`
  - 5: `R`
  - 6: `6`
*power7*
- `state`
  - 0: `.`
  - 1: `P`
  - 2: `O`
  - 3: `W`
  - 4: `E`
  - 5: `R`
  - 6: `7`
- `action`
  - 0: `.`
  - 1: `P`
  - 2: `O`
  - 3: `W`
  - 4: `E`
  - 5: `R`
  - 6: `7`
*power8*
- `state`
  - 0: `.`
  - 1: `P`
  - 2: `O`
  - 3: `W`
  - 4: `E`
  - 5: `R`
  - 6: `8`
- `action`
  - 0: `.`
  - 1: `P`
  - 2: `O`
  - 3: `W`
  - 4: `E`
  - 5: `R`
  - 6: `8`
*power9*
- `state`
  - 0: `.`
  - 1: `P`
  - 2: `O`
  - 3: `W`
  - 4: `E`
  - 5: `R`
  - 6: `9`
- `action`
  - 0: `.`
  - 1: `P`
  - 2: `O`
  - 3: `W`
  - 4: `E`
  - 5: `R`
  - 6: `9`
#### Adapter nuki-extended
- `door`
  - state: `.state.closed`
- `doorState`
  - state: `.state.doorState`
  - display: `[object Object]`
- `lock`
  - state: `.state.locked`
- `lockState`
  - state: `.state.lockState`
  - display: `[object Object]`
- `lockUpdate`
  - state: `.state.lastStateUpdate`
- `lowbattery`
  - state: `.state.batteryCritical`
- `ACTIONS`
  - action: `._ACTION`
  - display: `[object Object]`
  - actionElement: `DropdownAction`
- `LOCK`
  - action: `._ACTION.LOCK`
  - actionElement: `IconButtonAction`
- `LOCK_N_GO`
  - action: `._ACTION.LOCK_N_GO`
  - actionElement: `IconButtonAction`
- `LOCK_N_GO_WITH_UNLATCH`
  - action: `._ACTION.LOCK_N_GO_WITH_UNLATCH`
  - actionElement: `IconButtonAction`
- `UNLATCH`
  - action: `._ACTION.UNLATCH`
  - actionElement: `IconButtonAction`
- `UNLOCK`
  - action: `._ACTION.UNLOCK`
  - actionElement: `IconButtonAction`
#### Adapter tr-064
- `ab`
  - state: `.ab`
- `ip`
  - state: `.externalIP`
- `ipv6`
  - state: `.externalIPv6`
- `reboot`
  - action: `.reboot`
  - actionElement: `IconButtonAction`
- `reconnect`
  - action: `.reconnectInternet`
  - actionElement: `IconButtonAction`
- `wlan24`
  - state: `.wlan24`
- `wlan50`
  - state: `.wlan50`
#### Adapter unifi
- `update_available`
  - state: `.update_available`
- `version`
  - state: `.version`
#### Adapter zwave2
- `valve`
  - state: `.Multilevel_Switch.currentValue`
  - unit: `%`
  - icon: `rotate-right`
- `mode`
  - state: `.Thermostat_Mode.mode`
  - action: `.Thermostat_Mode.mode`
  - icon: `[object Object]`
- `setTemperatureEnergySave`
  - state: `.Thermostat_Setpoint.setpoint_energySaveHeating`
  - action: `.Thermostat_Setpoint.setpoint_energySaveHeating`
  - unit: `°C`
  - icon: `radiator-disabled`
- `temperature`
  - state: `.Multilevel_Sensor.airTemperature`
- `setTemperature`
  - state: `.Thermostat_Setpoint.setpoint_heating`
  - action: `.Thermostat_Setpoint.setpoint_heating`
