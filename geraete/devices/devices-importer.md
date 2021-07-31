# Geräte importieren

Um schnell in jarvis zu starten, können vorhandene Geräte aus ioBroker importiert werden:

![Importer](../../.gitbook/assets/devices-importer_button.png)

## Such-Modus \(alle oder Enums\)

Es werden zwei Modi unterstützt um die Adapter-Struktur zu durchsuchen:

![Importer](../../.gitbook/assets/devices-importer_structure-selection.png)

* `nach allen Geräten durchsuchen`: Durchsucht die komplette Struktur der ausgewählten Adapter nach allen vorhandenen Geräten und listet diese auf.
* `nur nach in Enums hinzugefügten Geräten durchsuchen`: Durchsucht die Struktur der ausgewählten Adapter nur nach Geräten, die bereits in Enums zugeordnet sind.

## Liste unterstützter Adapter

* [alias](devices-importer.md#adapter-alias)
* [ble](devices-importer.md#adapter-ble)
* [daswetter](devices-importer.md#adapter-daswetter)
* [deconz](devices-importer.md#adapter-deconz)
* [hm-rpc](devices-importer.md#adapter-hm-rpc)
  * [Function `light` of hm-rpc](devices-importer.md#function-light-of-hm-rpc)
  * [Function `heating` of hm-rpc](devices-importer.md#function-heating-of-hm-rpc)
  * [Function `blind` of hm-rpc](devices-importer.md#function-blind-of-hm-rpc)
  * [Function `sensor` of hm-rpc](devices-importer.md#function-sensor-of-hm-rpc)
  * [Function `smoke` of hm-rpc](devices-importer.md#function-smoke-of-hm-rpc)
  * [Function `window` of hm-rpc](devices-importer.md#function-window-of-hm-rpc)
  * [Function `socket` of hm-rpc](devices-importer.md#function-socket-of-hm-rpc)
  * [Function `motion` of hm-rpc](devices-importer.md#function-motion-of-hm-rpc)
  * [Function `door` of hm-rpc](devices-importer.md#function-door-of-hm-rpc)
  * [Function `weather-station` of hm-rpc](devices-importer.md#function-weather-station-of-hm-rpc)
  * [Function `other` of hm-rpc](devices-importer.md#function-other-of-hm-rpc)
  * [Function `switch` of hm-rpc](devices-importer.md#function-switch-of-hm-rpc)
  * [Function `CUxD` of hm-rpc](devices-importer.md#function-CUxD-of-hm-rpc)
* [hmip](devices-importer.md#adapter-hmip)
  * [Function `heating` of hmip](devices-importer.md#function-heating-of-hmip)
  * [Function `blind` of hmip](devices-importer.md#function-blind-of-hmip)
  * [Function `window` of hmip](devices-importer.md#function-window-of-hmip)
  * [Function `socket` of hmip](devices-importer.md#function-socket-of-hmip)
  * [Function `motion` of hmip](devices-importer.md#function-motion-of-hmip)
  * [Function `weather-station` of hmip](devices-importer.md#function-weather-station-of-hmip)
* [hue-extended](devices-importer.md#adapter-hue-extended)
  * [Function `light` of hue-extended](devices-importer.md#function-light-of-hue-extended)
* [hue](devices-importer.md#adapter-hue)
  * [Function `light` of hue](devices-importer.md#function-light-of-hue)
* [innogy-smarthome](devices-importer.md#adapter-innogy-smarthome)
* [knx](devices-importer.md#adapter-knx)
* [lifx](devices-importer.md#adapter-lifx)
* [linkeddevices](devices-importer.md#adapter-linkeddevices)
* [mihome-vacuum](devices-importer.md#adapter-mihome-vacuum)
  * [Function `consumableFilter` of mihome-vacuum](devices-importer.md#function-consumableFilter-of-mihome-vacuum)
  * [Function `consumableBrushMain` of mihome-vacuum](devices-importer.md#function-consumableBrushMain-of-mihome-vacuum)
  * [Function `consumableBrushSide` of mihome-vacuum](devices-importer.md#function-consumableBrushSide-of-mihome-vacuum)
  * [Function `consumableSensors` of mihome-vacuum](devices-importer.md#function-consumableSensors-of-mihome-vacuum)
  * [Function `consumableFilterWater` of mihome-vacuum](devices-importer.md#function-consumableFilterWater-of-mihome-vacuum)
  * [Function `controlSoundVolume` of mihome-vacuum](devices-importer.md#function-controlSoundVolume-of-mihome-vacuum)
  * [Function `controlModeCarpet` of mihome-vacuum](devices-importer.md#function-controlModeCarpet-of-mihome-vacuum)
  * [Function `controlFind` of mihome-vacuum](devices-importer.md#function-controlFind-of-mihome-vacuum)
  * [Function `controlHome` of mihome-vacuum](devices-importer.md#function-controlHome-of-mihome-vacuum)
  * [Function `controlPause` of mihome-vacuum](devices-importer.md#function-controlPause-of-mihome-vacuum)
  * [Function `cleanRoomResume` of mihome-vacuum](devices-importer.md#function-cleanRoomResume-of-mihome-vacuum)
  * [Function `cleanZoneResume` of mihome-vacuum](devices-importer.md#function-cleanZoneResume-of-mihome-vacuum)
  * [Function `cleanSpot` of mihome-vacuum](devices-importer.md#function-cleanSpot-of-mihome-vacuum)
  * [Function `cleanZone` of mihome-vacuum](devices-importer.md#function-cleanZone-of-mihome-vacuum)
  * [Function `clean` of mihome-vacuum](devices-importer.md#function-clean-of-mihome-vacuum)
  * [Function `controlFan` of mihome-vacuum](devices-importer.md#function-controlFan-of-mihome-vacuum)
  * [Function `historyTableJson` of mihome-vacuum](devices-importer.md#function-historyTableJson-of-mihome-vacuum)
  * [Function `cleanedTotalArea` of mihome-vacuum](devices-importer.md#function-cleanedTotalArea-of-mihome-vacuum)
  * [Function `cleanedTotalCleanups` of mihome-vacuum](devices-importer.md#function-cleanedTotalCleanups-of-mihome-vacuum)
  * [Function `cleanedTotalTime` of mihome-vacuum](devices-importer.md#function-cleanedTotalTime-of-mihome-vacuum)
  * [Function `cleanedMissionArea` of mihome-vacuum](devices-importer.md#function-cleanedMissionArea-of-mihome-vacuum)
  * [Function `cleanedMissionTime` of mihome-vacuum](devices-importer.md#function-cleanedMissionTime-of-mihome-vacuum)
  * [Function `battery` of mihome-vacuum](devices-importer.md#function-battery-of-mihome-vacuum)
  * [Function `device_fw` of mihome-vacuum](devices-importer.md#function-device_fw-of-mihome-vacuum)
  * [Function `device_model` of mihome-vacuum](devices-importer.md#function-device_model-of-mihome-vacuum)
  * [Function `doNotDisturb` of mihome-vacuum](devices-importer.md#function-doNotDisturb-of-mihome-vacuum)
  * [Function `error` of mihome-vacuum](devices-importer.md#function-error-of-mihome-vacuum)
  * [Function `timer` of mihome-vacuum](devices-importer.md#function-timer-of-mihome-vacuum)
  * [Function `state` of mihome-vacuum](devices-importer.md#function-state-of-mihome-vacuum)
  * [Function `waterBox` of mihome-vacuum](devices-importer.md#function-waterBox-of-mihome-vacuum)
  * [Function `map` of mihome-vacuum](devices-importer.md#function-map-of-mihome-vacuum)
  * [Function `cleanQueue` of mihome-vacuum](devices-importer.md#function-cleanQueue-of-mihome-vacuum)
* [mihome](devices-importer.md#adapter-mihome)
* [mqtt](devices-importer.md#adapter-mqtt)
  * [Function `light` of mqtt](devices-importer.md#function-light-of-mqtt)
  * [Function `other` of mqtt](devices-importer.md#function-other-of-mqtt)
* [nuki-extended](devices-importer.md#adapter-nuki-extended)
  * [Function `openers` of nuki-extended](devices-importer.md#function-openers-of-nuki-extended)
  * [Function `smartlocks` of nuki-extended](devices-importer.md#function-smartlocks-of-nuki-extended)
* [rpi2](devices-importer.md#adapter-rpi2)
* [shelly](devices-importer.md#adapter-shelly)
  * [Function `socket` of shelly](devices-importer.md#function-socket-of-shelly)
  * [Function `blind` of shelly](devices-importer.md#function-blind-of-shelly)
  * [Function `light` of shelly](devices-importer.md#function-light-of-shelly)
  * [Function `switch` of shelly](devices-importer.md#function-switch-of-shelly)
  * [Function `sensor` of shelly](devices-importer.md#function-sensor-of-shelly)
* [sonoff](devices-importer.md#adapter-sonoff)
* [tr-064](devices-importer.md#adapter-tr-064)
  * [Function `calllists` of tr-064](devices-importer.md#function-calllists-of-tr-064)
  * [Function `phonebook` of tr-064](devices-importer.md#function-phonebook-of-tr-064)
  * [Function `states` of tr-064](devices-importer.md#function-states-of-tr-064)
* [unifi](devices-importer.md#adapter-unifi)
  * [Function `health` of unifi](devices-importer.md#function-health-of-unifi)
  * [Function `sysinfo` of unifi](devices-importer.md#function-sysinfo-of-unifi)
* [wifilight](devices-importer.md#adapter-wifilight)
* [yeelight-2](devices-importer.md#adapter-yeelight-2)
* [zigbee](devices-importer.md#adapter-zigbee)
* [zwave2](devices-importer.md#adapter-zwave2)
  * [Function `thermostat` of zwave2](devices-importer.md#function-thermostat-of-zwave2)

## Unterstützte Geräte der Adapter

### Adapter alias

alle Datenpunkte werden übernommen

### Adapter ble

alle Datenpunkte werden übernommen

### Adapter daswetter

alle Datenpunkte werden übernommen

### Adapter deconz

alle Datenpunkte werden übernommen

### Adapter hm-rpc

#### Function `light` of hm-rpc

```text
{
   "HmIP-BSM": {
      "power": {
         "state": ".4.STATE",
         "action": ".4.STATE"
      },
      "powerMeter": {
         "state": ".7.POWER"
      },
      "powerVoltage": {
         "state": ".7.VOLTAGE"
      },
      "powerFrequency": {
         "state": ".7.FREQUENCY"
      }
   },
   "HmIP-BSL": {
      "power": {
         "state": ".4.STATE",
         "action": ".4.STATE"
      },
      "levelTop": {
         "state": ".8.LEVEL",
         "action": ".8.LEVEL"
      },
      "colorTop": {
         "state": ".8.COLOR",
         "action": ".8.COLOR",
         "display": {
            "0": "BLACK",
            "1": "BLUE",
            "2": "GREEN",
            "3": "TURQUOISE",
            "4": "RED",
            "5": "PURPLE",
            "6": "YELLOW",
            "7": "WHITE"
         }
      },
      "levelBottom": {
         "state": ".12.LEVEL",
         "action": ".12.LEVEL"
      },
      "colorBottom": {
         "state": ".12.COLOR",
         "action": ".12.COLOR",
         "display": {
            "0": "BLACK",
            "1": "BLUE",
            "2": "GREEN",
            "3": "TURQUOISE",
            "4": "RED",
            "5": "PURPLE",
            "6": "YELLOW",
            "7": "WHITE"
         }
      }
   },
   "HmIP-BRC2": {
      "power": {
         "state": ".3.STATE",
         "action": ".4.STATE"
      }
   },
   "HmIP-BDT": {
      "level": {
         "state": ".3.LEVEL",
         "action": ".4.LEVEL"
      }
   },
   "HM-LC-Dim1T-FM": {
      "level": {
         "state": ".1.LEVEL",
         "action": ".1.LEVEL"
      },
      "timerOff": {
         "state": ".1.ON_TIME",
         "action": ".1.ON_TIME"
      },
      "timerOn": {
         "state": ".1.RAMP_TIME",
         "action": ".1.RAMP_TIME"
      }
   },
   "HM-LC-RGBW-WM": {
      "level": {
         "state": ".1.LEVEL",
         "action": ".1.LEVEL"
      },
      "timerOff": {
         "state": ".1.ON_TIME",
         "action": ".1.ON_TIME"
      },
      "timerOn": {
         "state": ".1.RAMP_TIME",
         "action": ".1.RAMP_TIME"
      },
      "hue": {
         "state": ".2.COLOR",
         "action": ".2.COLOR"
      }
   },
   "HM-LC-Sw1PBU-FM": {
      "power": {
         "state": ".1.STATE",
         "action": ".1.STATE"
      }
   },
   "HM-LC-Sw1-FM": {
      "power": {
         "state": ".1.STATE",
         "action": ".1.STATE"
      },
      "timerOff": {
         "state": ".1.ON_TIME",
         "action": ".1.ON_TIME"
      },
      "activity": {
         "state": ".1.WORKING",
         "action": ".1.WORKING"
      }
   },
   "HM-LC-Sw1-DR": {
      "power": {
         "state": ".1.STATE",
         "action": ".1.STATE"
      },
      "timerOff": {
         "state": ".1.ON_TIME",
         "action": ".1.ON_TIME"
      }
   },
   "HM-LC-Sw2-FM": {
      "power": {
         "state": ".1.STATE",
         "action": ".1.STATE"
      },
      "timerOff": {
         "state": ".1.ON_TIME",
         "action": ".1.ON_TIME"
      },
      "powerCh2": {
         "state": ".2.STATE",
         "action": ".2.STATE"
      },
      "timerOffCh2": {
         "state": ".2.ON_TIME",
         "action": ".2.ON_TIME"
      }
   },
   "HM-LC-Sw4-DR": {
      "power": {
         "state": ".1.STATE",
         "action": ".1.STATE"
      },
      "timerOff": {
         "state": ".1.ON_TIME",
         "action": ".1.ON_TIME"
      },
      "powerCh2": {
         "state": ".2.STATE",
         "action": ".2.STATE"
      },
      "timerOffCh2": {
         "state": ".2.ON_TIME",
         "action": ".2.ON_TIME"
      },
      "powerCh3": {
         "state": ".3.STATE",
         "action": ".3.STATE"
      },
      "timerOffCh3": {
         "state": ".3.ON_TIME",
         "action": ".3.ON_TIME"
      },
      "powerCh4": {
         "state": ".4.STATE",
         "action": ".4.STATE"
      },
      "timerOffCh4": {
         "state": ".4.ON_TIME",
         "action": ".4.ON_TIME"
      }
   },
   "HM-LC-Dim1TPBU-FM": {
      "level": {
         "state": ".1.LEVEL",
         "action": ".1.LEVEL"
      }
   },
   "HM-LC-Dim1T-Pl-3": {
      "level": {
         "state": ".1.LEVEL",
         "action": ".1.LEVEL"
      },
      "timerOff": {
         "state": ".1.ON_TIME",
         "action": ".1.ON_TIME"
      },
      "timerOn": {
         "state": ".1.RAMP_TIME",
         "action": ".1.RAMP_TIME"
      }
   }
}
```

#### Function `heating` of hm-rpc

```text
{
   "HmIP-STHD": {
      "temperature": {
         "state": ".1.ACTUAL_TEMPERATURE"
      },
      "setTemperature": {
         "state": ".1.SET_POINT_TEMPERATURE",
         "action": ".1.SET_POINT_TEMPERATURE"
      },
      "humidity": {
         "state": ".1.HUMIDITY"
      },
      "frost": {
         "state": ".1.FROST_PROTECTION"
      },
      "boost": {
         "state": ".1.BOOST_MODE",
         "action": ".1.BOOST_MODE"
      },
      "boostTime": {
         "state": ".1.BOOST_TIME",
         "action": ".1.BOOST_TIME"
      },
      "windowState": {
         "state": ".1.WINDOW_STATE"
      },
      "partyMode": {
         "state": ".1.PARTY_MODE",
         "action": ".1.PARTY_MODE"
      }
   },
   "HmIP-eTRV-B": {
      "temperature": {
         "state": ".1.ACTUAL_TEMPERATURE"
      },
      "setTemperature": {
         "state": ".1.SET_POINT_TEMPERATURE",
         "action": ".1.SET_POINT_TEMPERATURE"
      },
      "frost": {
         "state": ".1.FROST_PROTECTION"
      },
      "boost": {
         "state": ".1.BOOST_MODE",
         "action": ".1.BOOST_MODE"
      },
      "boostTime": {
         "state": ".1.BOOST_TIME",
         "action": ".1.BOOST_TIME"
      },
      "windowState": {
         "state": ".1.WINDOW_STATE"
      },
      "partyMode": {
         "state": ".1.PARTY_MODE",
         "action": ".1.PARTY_MODE"
      }
   },
   "HmIP-eTRV": {
      "temperature": {
         "state": ".1.ACTUAL_TEMPERATURE"
      },
      "setTemperature": {
         "state": ".1.SET_POINT_TEMPERATURE",
         "action": ".1.SET_POINT_TEMPERATURE"
      },
      "frost": {
         "state": ".1.FROST_PROTECTION"
      },
      "boost": {
         "state": ".1.BOOST_MODE",
         "action": ".1.BOOST_MODE"
      },
      "boostTime": {
         "state": ".1.BOOST_TIME",
         "action": ".1.BOOST_TIME"
      },
      "windowState": {
         "state": ".1.WINDOW_STATE"
      },
      "partyMode": {
         "state": ".1.PARTY_MODE",
         "action": ".1.PARTY_MODE"
      },
      "level": {
         "state": ".1.LEVEL",
         "action": ".1.LEVEL"
      },
      "valve": {
         "state": ".1.VALVE_STATE",
         "action": ".1.VALVE_STATE"
      }
   },
   "HmIP-eTRV-2": {
      "temperature": {
         "state": ".1.ACTUAL_TEMPERATURE"
      },
      "setTemperature": {
         "state": ".1.SET_POINT_TEMPERATURE",
         "action": ".1.SET_POINT_TEMPERATURE"
      },
      "frost": {
         "state": ".1.FROST_PROTECTION"
      },
      "boost": {
         "state": ".1.BOOST_MODE",
         "action": ".1.BOOST_MODE"
      },
      "boostTime": {
         "state": ".1.BOOST_TIME",
         "action": ".1.BOOST_TIME"
      },
      "windowState": {
         "state": ".1.WINDOW_STATE"
      },
      "partyMode": {
         "state": ".1.PARTY_MODE",
         "action": ".1.PARTY_MODE"
      },
      "level": {
         "state": ".1.LEVEL",
         "action": ".1.LEVEL"
      },
      "valve": {
         "state": ".1.VALVE_STATE",
         "action": ".1.VALVE_STATE"
      }
   },
   "HmIP-BWTH": {
      "temperature": {
         "state": ".1.ACTUAL_TEMPERATURE"
      },
      "setTemperature": {
         "state": ".1.SET_POINT_TEMPERATURE",
         "action": ".1.SET_POINT_TEMPERATURE"
      },
      "humidity": {
         "state": ".1.HUMIDITY"
      },
      "boost": {
         "state": ".1.BOOST_MODE",
         "action": ".1.BOOST_MODE"
      }
   },
   "HmIP-WTH": {
      "temperature": {
         "state": ".1.ACTUAL_TEMPERATURE"
      },
      "setTemperature": {
         "state": ".1.SET_POINT_TEMPERATURE",
         "action": ".1.SET_POINT_TEMPERATURE"
      },
      "humidity": {
         "state": ".1.HUMIDITY"
      },
      "boost": {
         "state": ".1.BOOST_MODE",
         "action": ".1.BOOST_MODE"
      }
   },
   "HmIP-WTH-2": {
      "temperature": {
         "state": ".1.ACTUAL_TEMPERATURE"
      },
      "setTemperature": {
         "state": ".1.SET_POINT_TEMPERATURE",
         "action": ".1.SET_POINT_TEMPERATURE"
      },
      "humidity": {
         "state": ".1.HUMIDITY"
      },
      "boost": {
         "state": ".1.BOOST_MODE",
         "action": ".1.BOOST_MODE"
      }
   },
   "HM-CC-RT-DN": {
      "temperature": {
         "state": ".4.ACTUAL_TEMPERATURE"
      },
      "setTemperature": {
         "state": ".4.SET_TEMPERATURE",
         "action": ".4.SET_TEMPERATURE"
      },
      "boost": {
         "state": ".4.BOOST_MODE",
         "action": ".4.BOOST_MODE"
      },
      "batteryState": {
         "state": ".4.BATTERY_STATE"
      },
      "partyTemperature": {
         "state": ".4.PARTY_TEMPERATURE"
      },
      "modeAuto": {
         "state": ".4.AUTO_MODE",
         "action": ".4.AUTO_MODE"
      },
      "modeManu": {
         "state": ".4.MANU_MODE",
         "action": ".4.MANU_MODE"
      },
      "boostState": {
         "state": ".4.BOOST_STATE",
         "action": ".4.BOOST_STATE"
      },
      "modeCurrent": {
         "state": ".4.COMFORT_MODE",
         "action": ".4.COMFORT_MODE"
      },
      "modeLowering": {
         "state": ".4.LOWERING_MODE",
         "action": ".4.LOWERING_MODE"
      },
      "modeControl": {
         "state": ".4.CONTROL_MODE",
         "action": ".4.CONTROL_MODE",
         "display": {
            "0": "Auto-Mode",
            "1": "Manu-Mode",
            "2": "Party-Mode",
            "3": "Boost-Mode"
         }
      },
      "valve": {
         "state": ".4.VALVE_STATE",
         "action": ".4.VALVE_STATE"
      }
   },
   "HM-TC-IT-WM-W-EU": {
      "temperature": {
         "state": ".1.TEMPERATURE"
      },
      "humidity": {
         "state": ".1.HUMIDITY"
      },
      "actualHumidity": {
         "state": ".2.ACTUAL_HUMIDITY"
      },
      "actualTemperature": {
         "state": ".2.ACTUAL_TEMPERATURE"
      },
      "modeAuto": {
         "state": ".2.AUTO_MODE",
         "action": ".2.AUTO_MODE"
      },
      "batteryState": {
         "state": ".2.BATTERY_STATE"
      },
      "boost": {
         "state": ".2.BOOST_MODE",
         "action": ".2.BOOST_MODE"
      },
      "boostState": {
         "state": ".2.BOOST_STATE",
         "action": ".2.BOOST_STATE"
      },
      "modeControl": {
         "state": ".2.CONTROL_MODE",
         "action": ".2.CONTROL_MODE",
         "display": {
            "0": "Auto-Mode",
            "1": "Manu-Mode",
            "2": "Party-Mode",
            "3": "Boost-Mode"
         }
      },
      "modeCurrent": {
         "state": ".2.COMFORT_MODE",
         "action": ".2.COMFORT_MODE"
      },
      "lowBatteryAlarmReporting": {
         "state": ".2.LOWBAT_REPORTING",
         "action": ".2.LOWBAT_REPORTING"
      },
      "modeManu": {
         "state": ".2.MANU_MODE",
         "action": ".2.MANU_MODE"
      },
      "partyTemperature": {
         "state": ".2.PARTY_TEMPERATURE"
      },
      "setTemperature": {
         "state": ".2.SET_TEMPERATURE",
         "action": ".2.SET_TEMPERATURE"
      },
      "openWindow": {
         "state": ".2.WINDOW_OPEN_REPORTING",
         "action": ".2.WINDOW_OPEN_REPORTING"
      }
   },
   "HM-WDS40-TH-I": {
      "temperature": {
         "state": ".1.TEMPERATURE"
      },
      "humidity": {
         "state": ".1.HUMIDITY"
      }
   },
   "HM-WDS10-TH-O": {
      "temperature": {
         "state": ".1.TEMPERATURE"
      },
      "humidity": {
         "state": ".1.HUMIDITY"
      }
   },
   "HM-WDS30-OT2-SM": {
      "temperatureCh1": {
         "state": ".1.TEMPERATURE"
      },
      "lowBatteryCh1": {
         "state": ".1.LOWBAT"
      },
      "temperatureCh2": {
         "state": ".2.TEMPERATURE"
      },
      "lowBatteryCh2": {
         "state": ".2.LOWBAT"
      },
      "temperatureCh3": {
         "state": ".3.TEMPERATURE"
      },
      "lowBatteryCh3": {
         "state": ".3.LOWBAT"
      },
      "temperatureCh4": {
         "state": ".4.TEMPERATURE"
      },
      "lowBatteryCh4": {
         "state": ".4.LOWBAT"
      },
      "temperatureCh5": {
         "state": ".5.TEMPERATURE"
      },
      "lowBatteryCh5": {
         "state": ".5.LOWBAT"
      },
      "temperatureCh6": {
         "state": ".6.TEMPERATURE"
      },
      "lowBatteryCh6": {
         "state": ".6.LOWBAT"
      }
   }
}
```

#### Function `blind` of hm-rpc

```text
{
   "HmIP-BBL": {
      "level": {
         "state": ".3.LEVEL",
         "action": ".4.LEVEL"
      },
      "level2": {
         "state": ".3.LEVEL2",
         "action": ".4.LEVEL2"
      },
      "activity": {
         "state": ".3.ACTIVITY_STATE"
      },
      "stop": {
         "action": ".4.STOP"
      }
   },
   "HmIP-FROLL": {
      "level": {
         "state": ".3.LEVEL",
         "action": ".4.LEVEL"
      },
      "activity": {
         "state": ".3.ACTIVITY_STATE"
      },
      "stop": {
         "action": ".4.STOP"
      }
   },
   "HmIP-BROLL": {
      "level": {
         "state": ".3.LEVEL",
         "action": ".4.LEVEL"
      },
      "level2": {
         "state": ".3.LEVEL2",
         "action": ".4.LEVEL2"
      },
      "activity": {
         "state": ".3.ACTIVITY_STATE"
      },
      "stop": {
         "action": ".4.STOP"
      }
   },
   "HM-LC-Bl1-FM": {
      "level": {
         "state": ".1.LEVEL",
         "action": ".1.LEVEL"
      },
      "activity": {
         "state": ".1.WORKING"
      },
      "stop": {
         "action": ".1.STOP"
      }
   },
   "HM-LC-Bl1PBU-FM": {
      "level": {
         "state": ".1.LEVEL",
         "action": ".1.LEVEL"
      },
      "activity": {
         "state": ".1.WORKING"
      },
      "stop": {
         "action": ".1.STOP"
      }
   },
   "HmIPW-DRBL4": {
      "levelCh1": {
         "state": ".2.LEVEL",
         "action": ".2.LEVEL"
      },
      "level2Ch1": {
         "state": ".2.LEVEL_2",
         "action": ".2.LEVEL_2"
      },
      "activityCh1": {
         "state": ".2.PROCESS"
      },
      "stopCh1": {
         "action": ".2.STOP"
      },
      "levelCh2": {
         "state": ".6.LEVEL",
         "action": ".6.LEVEL"
      },
      "level2Ch2": {
         "state": ".6.LEVEL_2",
         "action": ".6.LEVEL_2"
      },
      "activityCh2": {
         "state": ".6.PROCESS"
      },
      "stopCh2": {
         "action": ".6.STOP"
      },
      "levelCh3": {
         "state": ".10.LEVEL",
         "action": ".10.LEVEL"
      },
      "level2Ch3": {
         "state": ".10.LEVEL_2",
         "action": ".10.LEVEL_2"
      },
      "activityCh3": {
         "state": ".10.PROCESS"
      },
      "stopCh3": {
         "action": ".10.STOP"
      },
      "levelCh4": {
         "state": ".14.LEVEL",
         "action": ".14.LEVEL"
      },
      "level2Ch4": {
         "state": ".14.LEVEL_2",
         "action": ".14.LEVEL_2"
      },
      "activityCh4": {
         "state": ".14.PROCESS"
      },
      "stopCh4": {
         "action": ".14.STOP"
      }
   }
}
```

#### Function `sensor` of hm-rpc

```text
{
   "HM-Sec-TiS": {
      "power": {
         "state": ".1.STATE"
      }
   },
   "HmIP-SLO": {
      "illuminationAverage": {
         "state": ".1.AVERAGE_ILLUMINATION",
         "unit": " Lux"
      },
      "illuminationCurrent": {
         "state": ".1.CURRENT_ILLUMINATION",
         "unit": " Lux"
      },
      "illuminationHighest": {
         "state": ".1.HIGHEST_ILLUMINATION",
         "unit": " Lux"
      },
      "illuminationLowest": {
         "state": ".1.LOWEST_ILLUMINATION",
         "unit": " Lux"
      }
   },
   "HmIP-SWD": {
      "alarm": {
         "state": ".1.ALARMSTATE"
      },
      "alarmMoisture": {
         "state": ".1.MOISTURE_DETECTED"
      },
      "alarmWaterlevel": {
         "state": ".1.WATERLEVEL_DETECTED"
      }
   },
   "HM-Sec-WDS-2": {
      "alarm": {
         "state": ".1.STATE"
      }
   }
}
```

#### Function `smoke` of hm-rpc

```text
{
   "HmIP-SWSD": {
      "alarm": {
         "state": ".1.SMOKE_DETECTOR_ALARM_STATUS",
         "display": {
            "0": "IDLE_OFF",
            "1": "PRIMARY_ALARM",
            "2": "INTRUSION_ALARM",
            "3": "SECONDARY_ALARM"
         }
      }
   },
   "HM-Sec-SD": {
      "alarm": {
         "state": ".1.STATE"
      },
      "lowBatteryCh1": {
         "state": ".1.LOWBAT"
      }
   },
   "HM-Sec-SD-2": {
      "alarm": {
         "state": ".1.STATE"
      },
      "lowBatteryCh1": {
         "state": ".1.LOWBAT"
      }
   },
   "HM-Sec-SD-2-Team": {
      "alarm": {
         "state": ".1.STATE"
      }
   }
}
```

#### Function `window` of hm-rpc

```text
{
   "HmIP-SWDM": {
      "open": {
         "state": ".1.STATE"
      }
   },
   "HmIP-SWDO-I": {
      "open": {
         "state": ".1.STATE"
      }
   },
   "HmIP-SWDO-PL": {
      "open": {
         "state": ".1.STATE"
      }
   },
   "HmIP-SWDO": {
      "open": {
         "state": ".1.STATE"
      }
   },
   "HmIP-SRH": {
      "open": {
         "state": ".1.STATE",
         "display": {
            "0": "window#open#closed",
            "1": "window#open#tilted",
            "2": "window#open#opened"
         }
      }
   },
   "HM-Sec-RHS": {
      "open": {
         "state": ".1.STATE",
         "display": {
            "0": "window#open#closed",
            "1": "window#open#tilted",
            "2": "window#open#opened"
         }
      }
   },
   "HM-Sec-Sco": {
      "open": {
         "state": ".1.STATE"
      }
   },
   "HM-Sec-SC-2": {
      "open": {
         "state": ".1.STATE"
      }
   }
}
```

#### Function `socket` of hm-rpc

```text
{
   "HmIP-FSM": {
      "power": {
         "state": ".2.STATE",
         "action": ".2.STATE"
      },
      "timerOff": {
         "state": ".2.ON_TIME",
         "action": ".2.ON_TIME"
      },
      "powerCurrent": {
         "state": ".5.CURRENT",
         "unit": " mA"
      },
      "powerFrequency": {
         "state": ".5.FREQUENCY"
      },
      "powerCounter": {
         "state": ".5.ENERGY_COUNTER",
         "unit": " Wh"
      },
      "powerMeter": {
         "state": ".5.POWER",
         "unit": " W"
      },
      "powerVoltage": {
         "state": ".5.VOLTAGE",
         "unit": " V"
      }
   },
   "HmIP-PS": {
      "power": {
         "state": ".3.STATE"
      }
   },
   "HmIP-PSM": {
      "power": {
         "state": ".3.STATE"
      },
      "meter": {
         "state": ".6.POWER"
      }
   },
   "HM-ES-PMSw1-Pl-DN-R1": {
      "power": {
         "state": ".1.STATE",
         "action": ".1.STATE"
      },
      "timerOff": {
         "state": ".1.ON_TIME",
         "action": ".1.ON_TIME"
      },
      "powerCurrent": {
         "state": ".2.CURRENT",
         "unit": " mA"
      },
      "powerFrequency": {
         "state": ".2.FREQUENCY"
      },
      "powerCounter": {
         "state": ".2.ENERGY_COUNTER",
         "unit": " Wh"
      },
      "powerMeter": {
         "state": ".2.POWER",
         "unit": " W"
      },
      "powerVoltage": {
         "state": ".2.VOLTAGE",
         "unit": " V"
      }
   },
   "HM-LC-Sw1-Pl-2": {
      "power": {
         "state": ".1.STATE",
         "action": ".1.STATE"
      },
      "timerOff": {
         "state": ".1.ON_TIME",
         "action": ".1.ON_TIME"
      }
   },
   "HM-LC-Sw1-Pl-DN-R1": {
      "power": {
         "state": ".1.STATE",
         "action": ".1.STATE"
      },
      "timerOff": {
         "state": ".1.ON_TIME",
         "action": ".1.ON_TIME"
      }
   },
   "HM-ES-PMSw1-DR": {
      "power": {
         "state": ".1.STATE",
         "action": ".1.STATE"
      },
      "timerOff": {
         "state": ".1.ON_TIME",
         "action": ".1.ON_TIME"
      },
      "boot": {
         "state": ".2.BOOT",
         "action": ".2.BOOT"
      },
      "powerCurrent": {
         "state": ".2.CURRENT",
         "unit": " mA"
      },
      "powerFrequency": {
         "state": ".2.FREQUENCY"
      },
      "powerCounter": {
         "state": ".2.ENERGY_COUNTER",
         "unit": " Wh"
      },
      "powerMeter": {
         "state": ".2.POWER",
         "unit": " W"
      },
      "powerVoltage": {
         "state": ".2.VOLTAGE",
         "unit": " V"
      }
   },
   "HM-ES-PMSw1-Pl": {
      "power": {
         "state": ".1.STATE",
         "action": ".1.STATE"
      },
      "timerOff": {
         "state": ".1.ON_TIME",
         "action": ".1.ON_TIME"
      },
      "boot": {
         "state": ".2.BOOT",
         "action": ".2.BOOT"
      },
      "powerCurrent": {
         "state": ".2.CURRENT",
         "unit": " mA"
      },
      "powerFrequency": {
         "state": ".2.FREQUENCY"
      },
      "powerCounter": {
         "state": ".2.ENERGY_COUNTER",
         "unit": " Wh"
      },
      "powerMeter": {
         "state": ".2.POWER",
         "unit": " W"
      },
      "powerVoltage": {
         "state": ".2.VOLTAGE",
         "unit": " V"
      }
   }
}
```

#### Function `motion` of hm-rpc

```text
{
   "HmIP-SMI55": {
      "motion": {
         "state": ".3.MOTION"
      },
      "brightness": {
         "state": ".3.BRIGHTNESS"
      }
   },
   "HmIP-SMI": {
      "motion": {
         "state": ".1.MOTION"
      },
      "illumination": {
         "state": ".1.ILLUMINATION"
      }
   },
   "HmIP-SMO-A": {
      "motion": {
         "state": ".1.MOTION"
      },
      "illumination": {
         "state": ".1.ILLUMINATION"
      }
   },
   "HmIP-SAM": {
      "motion": {
         "state": ".1.MOTION"
      },
      "illumination": {
         "state": ".1.ILLUMINATION"
      }
   },
   "HmIP-SPI": {
      "presence": {
         "state": ".1.PRESENCE_DETECTION_STATE"
      },
      "illumination": {
         "state": ".1.ILLUMINATION"
      }
   },
   "HM-PB-6-WM55": {
      "PRESS_LONG1": {
         "state": ".1.PRESS_LONG",
         "action": ".1.PRESS_LONG"
      },
      "PRESS_SHORT1": {
         "state": ".1.PRESS_SHORT",
         "action": ".1.PRESS_SHORT"
      },
      "PRESS_LONG2": {
         "state": ".2.PRESS_LONG",
         "action": ".2.PRESS_LONG"
      },
      "PRESS_SHORT2": {
         "state": ".2.PRESS_SHORT",
         "action": ".2.PRESS_SHORT"
      },
      "PRESS_LONG3": {
         "state": ".3.PRESS_LONG",
         "action": ".3.PRESS_LONG"
      },
      "PRESS_SHORT3": {
         "state": ".3.PRESS_SHORT",
         "action": ".3.PRESS_SHORT"
      },
      "PRESS_LONG4": {
         "state": ".4.PRESS_LONG",
         "action": ".4.PRESS_LONG"
      },
      "PRESS_SHORT4": {
         "state": ".4.PRESS_SHORT",
         "action": ".4.PRESS_SHORT"
      },
      "PRESS_LONG5": {
         "state": ".5.PRESS_LONG",
         "action": ".5.PRESS_LONG"
      },
      "PRESS_SHORT5": {
         "state": ".5.PRESS_SHORT",
         "action": ".5.PRESS_SHORT"
      },
      "PRESS_LONG6": {
         "state": ".6.PRESS_LONG",
         "action": ".6.PRESS_LONG"
      },
      "PRESS_SHORT6": {
         "state": ".6.PRESS_SHORT",
         "action": ".6.PRESS_SHORT"
      }
   },
   "HM-Sen-MDIR-WM55": {
      "PRESS_LONG_BOTTOM": {
         "state": ".1.PRESS_LONG",
         "action": ".1.PRESS_LONG"
      },
      "PRESS_SHORT_BOTTOM": {
         "state": ".1.PRESS_SHORT",
         "action": ".1.PRESS_SHORT"
      },
      "PRESS_LONG_TOP": {
         "state": ".2.PRESS_LONG",
         "action": ".2.PRESS_LONG"
      },
      "PRESS_SHORT_TOP": {
         "state": ".2.PRESS_SHORT",
         "action": ".2.PRESS_SHORT"
      },
      "motion": {
         "state": ".3.MOTION"
      },
      "illumination": {
         "state": ".3.ILLUMINATION"
      }
   },
   "HM-Sen-MDIR-O-2": {
      "motion": {
         "state": ".1.MOTION"
      },
      "brightness": {
         "state": ".1.BRIGHTNESS"
      }
   },
   "HM-Sen-MDIR-O-3": {
      "motion": {
         "state": ".1.MOTION"
      },
      "brightness": {
         "state": ".1.BRIGHTNESS"
      }
   }
}
```

#### Function `door` of hm-rpc

```text
{
   "HM-Sec-Key": {
      "error": {
         "state": ".1.ERROR"
      },
      "lock": {
         "state": ".1.OPEN"
      }
   }
}
```

#### Function `weather-station` of hm-rpc

```text
{
   "HmIP-STHO": {
      "temperature": {
         "state": ".1.ACTUAL_TEMPERATURE"
      },
      "humidity": {
         "state": ".1.HUMIDITY"
      }
   },
   "HmIP-STHO-A": {
      "temperature": {
         "state": ".1.ACTUAL_TEMPERATURE"
      },
      "humidity": {
         "state": ".1.HUMIDITY"
      }
   },
   "HmIP-SWO-B": {
      "humidity": {
         "state": ".1.HUMIDITY"
      },
      "wind": {
         "state": ".1.WIND_SPEED"
      },
      "temperature": {
         "state": ".1.ACTUAL_TEMPERATURE"
      },
      "illumination": {
         "state": ".1.ILLUMINATION"
      },
      "sunshineDuration": {
         "state": ".1.SUNSHINEDURATION"
      }
   },
   "HmIP-SWO-PL": {
      "humidity": {
         "state": ".1.HUMIDITY"
      },
      "wind": {
         "state": ".1.WIND_SPEED"
      },
      "temperature": {
         "state": ".1.ACTUAL_TEMPERATURE"
      },
      "illumination": {
         "state": ".1.ILLUMINATION"
      },
      "sunshineDuration": {
         "state": ".1.SUNSHINEDURATION"
      },
      "raining": {
         "state": ".1.RAINING"
      },
      "rainCounter": {
         "state": ".1.RAIN_COUNTER"
      }
   },
   "HM-WDS40-TH-I-2": {
      "temperature": {
         "state": ".1.TEMPERATURE"
      },
      "humidity": {
         "state": ".1.HUMIDITY"
      }
   }
}
```

#### Function `other` of hm-rpc

```text
{
   "HmIP-FCI1": {
      "power": {
         "state": ".1.STATE",
         "action": ".1.STATE"
      },
      "PRESS_LONG": {
         "state": ".1.PRESS_LONG",
         "action": ".1.PRESS_LONG"
      },
      "PRESS_SHORT": {
         "state": ".1.PRESS_SHORT",
         "action": ".1.PRESS_SHORT"
      }
   },
   "HmIP-PCBS": {
      "powerCh2": {
         "state": ".2.STATE",
         "action": ".2.STATE"
      },
      "powerCh3": {
         "state": ".3.STATE",
         "action": ".3.STATE"
      },
      "powerCh4": {
         "state": ".4.STATE",
         "action": ".4.STATE"
      },
      "powerCh5": {
         "state": ".5.STATE",
         "action": ".5.STATE"
      }
   },
   "HmIP-PCBS2": {
      "powerCh3": {
         "state": ".3.STATE",
         "action": ".3.STATE"
      },
      "powerCh4": {
         "state": ".4.STATE",
         "action": ".4.STATE"
      },
      "powerCh5": {
         "state": ".5.STATE",
         "action": ".5.STATE"
      },
      "powerCh6": {
         "state": ".6.STATE",
         "action": ".6.STATE"
      },
      "powerCh7": {
         "state": ".7.STATE",
         "action": ".7.STATE"
      },
      "powerCh8": {
         "state": ".8.STATE",
         "action": ".8.STATE"
      },
      "powerCh9": {
         "state": ".9.STATE",
         "action": ".9.STATE"
      },
      "powerCh10": {
         "state": ".10.STATE",
         "action": ".10.STATE"
      }
   }
}
```

#### Function `switch` of hm-rpc

```text
{
   "HmIP-WRC2": {
      "PRESS_LONG_BOTTOM": {
         "state": ".1.PRESS_LONG",
         "action": ".1.PRESS_LONG"
      },
      "PRESS_SHORT_BOTTOM": {
         "state": ".1.PRESS_SHORT",
         "action": ".1.PRESS_SHORT"
      },
      "PRESS_LONG_TOP": {
         "state": ".2.PRESS_LONG",
         "action": ".2.PRESS_LONG"
      },
      "PRESS_SHORT_TOP": {
         "state": ".2.PRESS_SHORT",
         "action": ".2.PRESS_SHORT"
      }
   },
   "HM-RC-2-PBU-FM": {
      "PRESS_CONT_BOTTOM": {
         "state": ".1.PRESS_CONT",
         "action": ".1.PRESS_CONT"
      },
      "PRESS_LONG_BOTTOM": {
         "state": ".1.PRESS_LONG",
         "action": ".1.PRESS_LONG"
      },
      "PRESS_LONGRELEASE_BOTTOM": {
         "state": ".1.PRESS_LONG_RELEASE",
         "action": ".1.PRESS_LONG_RELEASE"
      },
      "PRESS_SHORT_BOTTOM": {
         "state": ".1.PRESS_SHORT",
         "action": ".1.PRESS_SHORT"
      },
      "PRESS_CONT_TOP": {
         "state": ".2.PRESS_CONT",
         "action": ".2.PRESS_CONT"
      },
      "PRESS_LONG_TOP": {
         "state": ".2.PRESS_LONG",
         "action": ".2.PRESS_LONG"
      },
      "PRESS_LONGRELEASE_TOP": {
         "state": ".2.PRESS_LONG_RELEASE",
         "action": ".2.PRESS_LONG_RELEASE"
      },
      "PRESS_SHORT_TOP": {
         "state": ".2.PRESS_SHORT",
         "action": ".2.PRESS_SHORT"
      }
   },
   "HM-LC-Sw1-DR": {
      "power": {
         "state": ".1.STATE",
         "action": ".1.STATE"
      }
   },
   "HM-LC-SW1-FM": {
      "power": {
         "state": ".1.STATE",
         "action": ".1.STATE"
      }
   },
   "HM-PB-2-WM55": {
      "lowBatteryCh1": {
         "state": ".1.LOWBAT"
      },
      "PRESS_LONG_BOTTOM": {
         "state": ".1.PRESS_LONG",
         "action": ".1.PRESS_LONG"
      },
      "PRESS_SHORT_BOTTOM": {
         "state": ".1.PRESS_SHORT",
         "action": ".1.PRESS_SHORT"
      },
      "PRESS_LONG_TOP": {
         "state": ".2.PRESS_LONG",
         "action": ".2.PRESS_LONG"
      },
      "PRESS_SHORT_TOP": {
         "state": ".2.PRESS_SHORT",
         "action": ".2.PRESS_SHORT"
      }
   },
   "HB-UNI-SenAct-4-4-RC": {
      "stateCh1": {
         "state": ".1.STATE"
      },
      "stateCh2": {
         "state": ".2.STATE"
      },
      "stateCh3": {
         "state": ".3.STATE"
      },
      "stateCh4": {
         "state": ".4.STATE"
      },
      "PRESS_LONG1": {
         "state": ".5.PRESS_LONG",
         "action": ".5.PRESS_LONG"
      },
      "PRESS_SHORT1": {
         "state": ".5.PRESS_SHORT",
         "action": ".5.PRESS_SHORT"
      },
      "PRESS_LONG2": {
         "state": ".6.PRESS_LONG",
         "action": ".6.PRESS_LONG"
      },
      "PRESS_SHORT2": {
         "state": ".6.PRESS_SHORT",
         "action": ".6.PRESS_SHORT"
      },
      "PRESS_LONG3": {
         "state": ".7.PRESS_LONG",
         "action": ".7.PRESS_LONG"
      },
      "PRESS_SHORT3": {
         "state": ".7.PRESS_SHORT",
         "action": ".7.PRESS_SHORT"
      },
      "PRESS_LONG4": {
         "state": ".8.PRESS_LONG",
         "action": ".8.PRESS_LONG"
      },
      "PRESS_SHORT4": {
         "state": ".8.PRESS_SHORT",
         "action": ".8.PRESS_SHORT"
      }
   }
}
```

#### Function `CUxD` of hm-rpc

```text
{
   "HM-LC-Sw1PBU-FM": {
      "powerCh1": {
         "state": ".1.STATE",
         "action": ".1.STATE"
      },
      "powerCh2": {
         "state": ".2.STATE",
         "action": ".2.STATE"
      },
      "powerCh3": {
         "state": ".3.STATE",
         "action": ".3.STATE"
      },
      "powerCh4": {
         "state": ".4.STATE",
         "action": ".4.STATE"
      },
      "powerCh5": {
         "state": ".5.STATE",
         "action": ".5.STATE"
      },
      "powerCh6": {
         "state": ".6.STATE",
         "action": ".6.STATE"
      },
      "powerCh7": {
         "state": ".7.STATE",
         "action": ".7.STATE"
      },
      "powerCh8": {
         "state": ".8.STATE",
         "action": ".8.STATE"
      },
      "powerCh9": {
         "state": ".9.STATE",
         "action": ".9.STATE"
      },
      "powerCh10": {
         "state": ".10.STATE",
         "action": ".10.STATE"
      },
      "powerCh11": {
         "state": ".11.STATE",
         "action": ".11.STATE"
      },
      "powerCh12": {
         "state": ".12.STATE",
         "action": ".12.STATE"
      },
      "powerCh13": {
         "state": ".13.STATE",
         "action": ".13.STATE"
      },
      "powerCh14": {
         "state": ".14.STATE",
         "action": ".14.STATE"
      },
      "powerCh15": {
         "state": ".15.STATE",
         "action": ".15.STATE"
      },
      "powerCh16": {
         "state": ".16.STATE",
         "action": ".16.STATE"
      }
   }
}
```

### Adapter hmip

#### Function `heating` of hmip

```text
{
   "HmIP-STH": {
      "temperature": {
         "state": ".channels.1.actualTemperature"
      },
      "humidity": {
         "state": ".channels.1.humidity"
      },
      "setTemperature": {
         "state": ".channels.1.setPointTemperature",
         "action": ".channels.1.setPointTemperature"
      }
   },
   "HmIP-eTRV-B": {
      "temperature": {
         "state": ".channels.1.valveActualTemperature"
      },
      "setTemperature": {
         "state": ".channels.1.setPointTemperature",
         "action": ".channels.1.setPointTemperature"
      },
      "valvePosition": {
         "state": ".channels.1.valvePosition"
      },
      "valveState": {
         "state": ".channels.1.valveState"
      }
   },
   "HmIP-eTRV-2": {
      "temperature": {
         "state": ".channels.1.valveActualTemperature"
      },
      "setTemperature": {
         "state": ".channels.1.setPointTemperature",
         "action": ".channels.1.setPointTemperature"
      }
   },
   "HmIP-WTH-2": {
      "temperature": {
         "state": ".channels.1.actualTemperature"
      },
      "humidity": {
         "state": ".channels.1.humidity"
      },
      "setTemperature": {
         "state": ".channels.1.setPointTemperature",
         "action": ".channels.1.setPointTemperature"
      },
      "vapor": {
         "state": ".channels.1.vaporAmount"
      }
   }
}
```

#### Function `blind` of hmip

```text
{
   "HmIP-BBL": {
      "level": {
         "state": ".channels.1.shutterLevel",
         "action": ".channels.1.shutterLevel"
      },
      "activity": {
         "state": ".channels.1.processing"
      },
      "stop": {
         "action": ".channels.1.stop"
      }
   },
   "HmIP-BROLL": {
      "level": {
         "state": ".channels.1.shutterLevel",
         "action": ".channels.1.shutterLevel"
      },
      "activity": {
         "state": ".channels.1.processing"
      },
      "stop": {
         "action": ".channels.1.stop"
      }
   }
}
```

#### Function `window` of hmip

```text
{
   "HmIP-SWDO": {
      "open": {
         "state": ".channels.1.windowOpen"
      }
   },
   "HmIP-SWDO-I": {
      "open": {
         "state": ".channels.1.windowOpen"
      }
   },
   "HmIP-SRH": {
      "open": {
         "state": ".channels.1.windowOpen"
      },
      "state": {
         "state": ".channels.1.windowState",
         "display": {
            "CLOSED": "window#open#closed",
            "TILTED": "window#open#tilted",
            "OPEN": "window#open#opened"
         }
      }
   }
}
```

#### Function `socket` of hmip

```text
{
   "HmIP-PS": {
      "power": {
         "state": ".channels.1.on",
         "action": ".channels.1.on"
      }
   }
}
```

#### Function `motion` of hmip

```text
{
   "HmIP-SMI": {
      "motion": {
         "state": ".channels.1.motionDetected"
      },
      "illumination": {
         "state": ".channels.1.illumination"
      }
   }
}
```

#### Function `weather-station` of hmip

```text
{
   "HmIP-STHO": {
      "temperature": {
         "state": ".channels.1.actualTemperature"
      },
      "humidity": {
         "state": ".channels.1.humidity"
      },
      "vapor": {
         "state": ".channels.1.vaporAmount"
      },
      "display": {
         "state": ".channels.1.display"
      }
   },
   "HmIP-STHO-A": {
      "temperature": {
         "state": ".1.ACTUAL_TEMPERATURE"
      },
      "humidity": {
         "state": ".1.HUMIDITY"
      }
   },
   "HmIP-SWO-B": {
      "humidity": {
         "state": ".1.HUMIDITY"
      },
      "wind": {
         "state": ".1.WIND_SPEED"
      },
      "temperature": {
         "state": ".1.ACTUAL_TEMPERATURE"
      },
      "illumination": {
         "state": ".1.ILLUMINATION"
      },
      "sunshineduration": {
         "state": ".1.SUNSHINEDURATION"
      }
   }
}
```

### Adapter hue-extended

#### Function `light` of hue-extended

```text
{
   "power": {
      "state": ".action.on",
      "action": ".action.on"
   },
   "level": {
      "state": ".action.level",
      "action": ".action.level"
   },
   "colorTemperature": {
      "state": ".action.colorTemperature",
      "action": ".action.colorTemperature"
   },
   "hue": {
      "state": ".action.hue",
      "action": ".action.hue"
   },
   "hex": {
      "state": ".action.hex",
      "action": ".action.hex"
   }
}
```

### Adapter hue

#### Function `light` of hue

```text
{
   "power": {
      "state": ".on",
      "action": ".on"
   },
   "level": {
      "state": ".level",
      "action": ".level"
   },
   "colorTemperature": {
      "state": ".ct",
      "action": ".ct"
   },
   "hue": {
      "state": ".hue",
      "action": ".hue"
   },
   "reachability": {
      "state": ".reachable"
   }
}
```

### Adapter innogy-smarthome

alle Datenpunkte werden übernommen

### Adapter knx

alle Datenpunkte werden übernommen

### Adapter lifx

alle Datenpunkte werden übernommen

### Adapter linkeddevices

alle Datenpunkte werden übernommen

### Adapter mihome-vacuum

#### Function `consumableFilter` of mihome-vacuum

```text
{
   "state": ".consumable.filter",
   "action": ".consumable.filter_reset",
   "actionElement": "IconButtonAction"
}
```

#### Function `consumableBrushMain` of mihome-vacuum

```text
{
   "state": ".consumable.main_brush",
   "action": ".consumable.main_brush_reset",
   "actionElement": "IconButtonAction"
}
```

#### Function `consumableBrushSide` of mihome-vacuum

```text
{
   "state": ".consumable.side_brush",
   "action": ".consumable.side_brush_reset",
   "actionElement": "IconButtonAction"
}
```

#### Function `consumableSensors` of mihome-vacuum

```text
{
   "state": ".consumable.sensors",
   "action": ".consumable.sensors_reset",
   "actionElement": "IconButtonAction"
}
```

#### Function `consumableFilterWater` of mihome-vacuum

```text
{
   "state": ".consumable.water_filter",
   "action": ".consumable.water_filter_reset",
   "actionElement": "IconButtonAction"
}
```

#### Function `controlSoundVolume` of mihome-vacuum

```text
{
   "state": ".control.sound_volume",
   "action": ".control.sound_volume",
   "actionElement": "InputAction"
}
```

#### Function `controlModeCarpet` of mihome-vacuum

```text
{
   "action": ".control.carpet_mode",
   "actionElement": "IconButtonAction"
}
```

#### Function `controlFind` of mihome-vacuum

```text
{
   "action": ".control.find",
   "actionElement": "IconButtonAction"
}
```

#### Function `controlHome` of mihome-vacuum

```text
{
   "action": ".control.home",
   "actionElement": "IconButtonAction"
}
```

#### Function `controlPause` of mihome-vacuum

```text
{
   "action": ".control.pause",
   "actionElement": "IconButtonAction"
}
```

#### Function `cleanRoomResume` of mihome-vacuum

```text
{
   "action": ".control.resumeRoomClean",
   "actionElement": "IconButtonAction"
}
```

#### Function `cleanZoneResume` of mihome-vacuum

```text
{
   "action": ".control.resumeZoneClean",
   "actionElement": "IconButtonAction"
}
```

#### Function `cleanSpot` of mihome-vacuum

```text
{
   "action": ".control.spotclean",
   "actionElement": "IconButtonAction"
}
```

#### Function `cleanZone` of mihome-vacuum

```text
{
   "action": ".control.zoneClean",
   "actionElement": "InputAction"
}
```

#### Function `clean` of mihome-vacuum

```text
{
   "action": ".control.clean",
   "actionElement": "IconButtonAction"
}
```

#### Function `controlFan` of mihome-vacuum

```text
{
   "action": ".control.fan_power",
   "display": {
      "101": "QUIET",
      "102": "BALANCED",
      "103": "TURBO",
      "104": "MAXIMUM",
      "105": "MOP",
      "106": "CUSTOM"
   }
}
```

#### Function `historyTableJson` of mihome-vacuum

```text
{
   "state": ".history.allTableJSON"
}
```

#### Function `cleanedTotalArea` of mihome-vacuum

```text
{
   "state": ".history.total_area"
}
```

#### Function `cleanedTotalCleanups` of mihome-vacuum

```text
{
   "state": ".history.cleanups"
}
```

#### Function `cleanedTotalTime` of mihome-vacuum

```text
{
   "state": ".history.total_time"
}
```

#### Function `cleanedMissionArea` of mihome-vacuum

```text
{
   "state": ".info.cleanedarea"
}
```

#### Function `cleanedMissionTime` of mihome-vacuum

```text
{
   "state": ".info.cleanedtime"
}
```

#### Function `battery` of mihome-vacuum

```text
{
   "state": ".info.battery"
}
```

#### Function `device_fw` of mihome-vacuum

```text
{
   "state": ".info.device_fw"
}
```

#### Function `device_model` of mihome-vacuum

```text
{
   "state": ".info.device_model"
}
```

#### Function `doNotDisturb` of mihome-vacuum

```text
{
   "state": ".info.dnd"
}
```

#### Function `error` of mihome-vacuum

```text
{
   "state": ".info.error"
}
```

#### Function `timer` of mihome-vacuum

```text
{
   "state": ".info.nextTimer"
}
```

#### Function `state` of mihome-vacuum

```text
{
   "state": ".info.state"
}
```

#### Function `waterBox` of mihome-vacuum

```text
{
   "state": ".info.water_box"
}
```

#### Function `map` of mihome-vacuum

```text
{
   "state": ".map.map64",
   "action": ".map.loadMap"
}
```

#### Function `cleanQueue` of mihome-vacuum

```text
{
   "state": ".info.queue",
   "action": ".control.clearQueue"
}
```

### Adapter mihome

alle Datenpunkte werden übernommen

### Adapter mqtt

#### Function `light` of mqtt

```text
{
   "dimmer": {
      "state": ".Dimmer",
      "action": ".Dimmer"
   },
   "ct": {
      "state": ".CT",
      "action": ".CT",
      "properties": {
         "min": 153,
         "max": 500
      }
   },
   "hue": {
      "state": ".Hue",
      "action": ".Hue"
   },
   "sat": {
      "state": ".Saturation",
      "action": ".Saturation"
   }
}
```

#### Function `other` of mqtt

```text
{
   "version": [
      ".Version",
      ".INFO.Version"
   ],
   "reachability": ".alive",
   "ip": ".INFO.IPAddress",
   "signal": ".Wifi_Signal",
   "dataReceived": ".RfReceived_Data",
   "power": {
      "state": ".POWER",
      "action": ".POWER"
   },
   "powerCurrent": {
      "state": ".ENERGY_Current",
      "unit": " A"
   },
   "powerMeter": {
      "state": ".ENERGY_Power",
      "unit": " W"
   },
   "powerConsumption": {
      "state": ".ENERGY_Total",
      "unit": " kWh"
   },
   "powerConsumptionToday": {
      "state": ".ENERGY_Today",
      "unit": " kWh"
   },
   "powerConsumptionYesterday": {
      "state": ".ENERGY_Yesterday",
      "unit": " kWh"
   },
   "power1": {
      "state": ".POWER1",
      "action": ".POWER1"
   },
   "power2": {
      "state": ".POWER2",
      "action": ".POWER2"
   },
   "power3": {
      "state": ".POWER3",
      "action": ".POWER3"
   },
   "power4": {
      "state": ".POWER4",
      "action": ".POWER4"
   },
   "power5": {
      "state": ".POWER5",
      "action": ".POWER5"
   },
   "power6": {
      "state": ".POWER6",
      "action": ".POWER6"
   },
   "power7": {
      "state": ".POWER7",
      "action": ".POWER7"
   },
   "power8": {
      "state": ".POWER8",
      "action": ".POWER8"
   },
   "power9": {
      "state": ".POWER9",
      "action": ".POWER9"
   }
}
```

### Adapter nuki-extended

#### Function `openers` of nuki-extended

```text
{
   "door": {
      "state": ".state.doorState"
   },
   "ring": {
      "state": ".state.ringState"
   },
   "ringUpdate": {
      "state": ".state.ringStateUpdate"
   },
   "state": {
      "state": ".state.lockState",
      "display": {
         "0": "UNTRAINED",
         "1": "ONLINE",
         "3": "RING_TO_OPEN",
         "5": "OPEN",
         "7": "OPENING",
         "253": "BOOT_RUN",
         "255": "UNDEFINED"
      }
   },
   "lowbattery": {
      "state": ".state.batteryCritical"
   },
   "ACTIONS": {
      "action": "._ACTION",
      "display": {
         "0": "NO_ACTION",
         "1": "ACTIVE RTO",
         "2": "DEACTIVATE RTO",
         "3": "ELECTRIC STRIKE ACTUATION",
         "4": "ACTIVATE CM",
         "5": "DEACTIVATE CM"
      },
      "actionElement": "DropdownAction"
   },
   "ACTIVATE_CM": {
      "action": "._ACTION.ACTIVATE_CM",
      "actionElement": "IconButtonAction"
   },
   "ACTIVE_RTO": {
      "action": "._ACTION.ACTIVE_RTO",
      "actionElement": "IconButtonAction"
   },
   "DEACTIVATE_CM": {
      "action": "._ACTION.DEACTIVATE_CM",
      "actionElement": "IconButtonAction"
   },
   "DEACTIVATE_RTO": {
      "action": "._ACTION.DEACTIVATE_RTO",
      "actionElement": "IconButtonAction"
   },
   "ELECTRIC_STRIKE_ACTUATION": {
      "action": "._ACTION.ELECTRIC_STRIKE_ACTUATION",
      "actionElement": "IconButtonAction"
   }
}
```

#### Function `smartlocks` of nuki-extended

```text
{
   "door": {
      "state": ".state.closed"
   },
   "doorState": {
      "state": ".state.doorState",
      "display": {
         "0": "UNAVAILABLE",
         "1": "DEACTIVATED",
         "2": "DOOR_CLOSED",
         "3": "DOOR_OPENED",
         "4": "DOOR_STATE_UNKNOWN",
         "5": "CALIBRATING"
      }
   },
   "lock": {
      "state": ".state.locked"
   },
   "lockState": {
      "state": ".state.lockState",
      "display": {
         "0": "UNCALIBRATED",
         "1": "LOCKED",
         "2": "UNLOCKING",
         "3": "UNLOCKED",
         "4": "LOCKING",
         "5": "UNLATCHED",
         "6": "UNLOCKED_LOCK_N_GO",
         "7": "UNLATCHING",
         "254": "MOTOR_BLOCKED",
         "255": "UNDEFINED"
      }
   },
   "lockUpdate": {
      "state": ".state.lastStateUpdate"
   },
   "lowbattery": {
      "state": ".state.batteryCritical"
   },
   "ACTIONS": {
      "action": "._ACTION",
      "display": {
         "0": "NO_ACTION",
         "1": "UNLOCK",
         "2": "LOCK",
         "3": "UNLATCH",
         "4": "LOCK_N_GO",
         "5": "LOCK_N_GO_WITH_UNLATCH"
      },
      "actionElement": "DropdownAction"
   },
   "LOCK": {
      "action": "._ACTION.LOCK",
      "actionElement": "IconButtonAction"
   },
   "LOCK_N_GO": {
      "action": "._ACTION.LOCK_N_GO",
      "actionElement": "IconButtonAction"
   },
   "LOCK_N_GO_WITH_UNLATCH": {
      "action": "._ACTION.LOCK_N_GO_WITH_UNLATCH",
      "actionElement": "IconButtonAction"
   },
   "UNLATCH": {
      "action": "._ACTION.UNLATCH",
      "actionElement": "IconButtonAction"
   },
   "UNLOCK": {
      "action": "._ACTION.UNLOCK",
      "actionElement": "IconButtonAction"
   }
}
```

### Adapter rpi2

alle Datenpunkte werden übernommen

### Adapter shelly

#### Function `socket` of shelly

```text
{
   "power": {
      "state": ".Relay0.Switch",
      "action": ".Relay0.Switch",
      "actionElement": "SwitchAction"
   },
   "powerCounter": {
      "state": ".Relay0.Energy",
      "unit": " Wh"
   },
   "powerMeter": {
      "state": ".Relay0.Power",
      "unit": " W"
   }
}
```

#### Function `blind` of shelly

```text
{
   "level": {
      "state": ".Shutter.Position",
      "action": ".Shutter.Position"
   },
   "activity": {
      "state": ".Shutter.state"
   },
   "stop": {
      "action": ".Shutter.Pause"
   }
}
```

#### Function `light` of shelly

```text
{
   "power": [
      {
         "state": ".lights.Switch",
         "action": ".lights.Switch",
         "actionElement": "SwitchAction"
      },
      {
         "state": ".white0.Switch",
         "action": ".white0.Switch",
         "actionElement": "SwitchAction"
      }
   ],
   "powerCh1": {
      "state": ".white1.Switch",
      "action": ".white1.Switch",
      "actionElement": "SwitchAction"
   },
   "powerCh2": {
      "state": ".white2.Switch",
      "action": ".white2.Switch",
      "actionElement": "SwitchAction"
   },
   "powerCh3": {
      "state": ".white3.Switch",
      "action": ".white3.Switch",
      "actionElement": "SwitchAction"
   },
   "colorTemperature": {
      "state": ".lights.white",
      "action": ".lights.white",
      "actionElement": "LightTemperatureBody",
      "properties": {
         "min": 0,
         "max": 100
      }
   },
   "level": [
      {
         "state": ".lights.brightness",
         "action": ".lights.brightness"
      },
      {
         "state": ".white0.brightness",
         "action": ".white0.brightness"
      }
   ],
   "levelCh1": {
      "state": ".white1.brightness",
      "action": ".white1.brightness"
   },
   "levelCh2": {
      "state": ".white2.brightness",
      "action": ".white2.brightness"
   },
   "levelCh3": {
      "state": ".white3.brightness",
      "action": ".white3.brightness"
   },
   "hex": {
      "state": ".lights.rgbw",
      "action": ".lights.rgbw"
   },
   "hue": {
      "state": ".lights.hue",
      "action": ".lights.hue"
   },
   "powerMeter": [
      {
         "state": ".Relay0.Power",
         "unit": " W"
      },
      {
         "state": ".lights.Power",
         "unit": " W"
      },
      {
         "state": ".white0.Power",
         "unit": " W"
      },
      {
         "state": ".Emeter0.Power",
         "unit": " W"
      }
   ],
   "powerMeterCh1": [
      {
         "state": ".Relay1.Power",
         "unit": " W"
      },
      {
         "state": ".white1.Power",
         "unit": " W"
      },
      {
         "state": ".Emeter1.Power",
         "unit": " W"
      }
   ],
   "powerMeterCh2": [
      {
         "state": ".Relay2.Power",
         "unit": " W"
      },
      {
         "state": ".white2.Power",
         "unit": " W"
      },
      {
         "state": ".Emeter2.Power",
         "unit": " W"
      }
   ],
   "powerMeterCh3": [
      {
         "state": ".Relay3.Power",
         "unit": " W"
      },
      {
         "state": ".white3.Power",
         "unit": " W"
      }
   ],
   "powerCounter": [
      {
         "state": ".Relay0.Energy",
         "unit": " Wh"
      },
      {
         "state": ".lights.Energy",
         "unit": " Wh"
      },
      {
         "state": ".white0.Energy",
         "unit": " Wh"
      },
      {
         "state": ".Emeter0.Total",
         "unit": " Wh"
      }
   ],
   "powerCounterCh1": [
      {
         "state": ".Relay1.Energy",
         "unit": " Wh"
      },
      {
         "state": ".white1.Energy",
         "unit": " Wh"
      },
      {
         "state": ".Emeter1.Total",
         "unit": " Wh"
      }
   ],
   "powerCounterCh2": [
      {
         "state": ".Relay2.Energy",
         "unit": " Wh"
      },
      {
         "state": ".white2.Energy",
         "unit": " Wh"
      },
      {
         "state": ".Emeter2.Total",
         "unit": " Wh"
      }
   ],
   "powerCounterCh3": [
      {
         "state": ".Relay3.Energy",
         "unit": " Wh"
      },
      {
         "state": ".white3.Energy",
         "unit": " Wh"
      }
   ],
   "powerCurrent": {
      "state": ".Emeter0.Current",
      "unit": " A"
   },
   "powerCurrentCh1": {
      "state": ".Emeter1.Current",
      "unit": " A"
   },
   "powerCurrentCh2": {
      "state": ".Emeter2.Current",
      "unit": " A"
   },
   "powerVoltage": {
      "state": ".Emeter0.Voltage",
      "unit": " V"
   },
   "powerVoltageCh1": {
      "state": ".Emeter1.Voltage",
      "unit": " V"
   },
   "powerVoltageCh2": {
      "state": ".Emeter2.Voltage",
      "unit": " V"
   },
   "powerCounterReturned": {
      "state": ".Emeter0.Total_Returned",
      "unit": " Wh"
   },
   "powerCounterReturnedCh1": {
      "state": ".Emeter1.Total_Returned",
      "unit": " Wh"
   },
   "powerCounterReturnedCh2": {
      "state": ".Emeter2.Total_Returned",
      "unit": " Wh"
   },
   "powerTotalCurrent": {
      "state": ".Total.Current",
      "unit": " A"
   },
   "powerTotalConsumed": {
      "state": ".Total.ConsumedPower",
      "unit": " Wh"
   },
   "powerTotalInstant": {
      "state": ".Total.InstantPower",
      "unit": " W"
   },
   "powerTotalVoltage": {
      "state": ".Total.Voltage",
      "unit": " V"
   },
   "powerTotalVoltageMean": {
      "state": ".Total.VoltageMean",
      "unit": " V"
   }
}
```

#### Function `switch` of shelly

```text
{
   "input": {
      "state": ".Relay0.Input"
   },
   "inputCh2": {
      "state": ".Relay1.Input"
   },
   "inputCh3": {
      "state": ".Relay2.Input"
   },
   "event": {
      "state": ".Relay0.Event"
   },
   "eventCh2": {
      "state": ".Relay1.Event"
   },
   "eventCh3": {
      "state": ".Relay2.Event"
   },
   "eventCount": {
      "state": ".Relay0.EventCount"
   },
   "eventCountCh2": {
      "state": ".Relay1.EventCount"
   },
   "eventCountCh3": {
      "state": ".Relay2.EventCount"
   }
}
```

#### Function `sensor` of shelly

```text
{
   "battery": [
      {
         "state": ".sensor.battery"
      },
      {
         "state": ".bat.value"
      }
   ],
   "humidity": {
      "state": ".hum.value"
   },
   "flood": {
      "state": ".sensor.flood"
   },
   "door": {
      "state": ".sensor.door"
   },
   "illumination": {
      "state": ".sensor.lux"
   },
   "tilt": {
      "state": ".sensor.tilt"
   },
   "vibration": {
      "state": ".sensor.vibration"
   },
   "temperature": [
      {
         "state": ".sensor.temperatureC"
      },
      {
         "state": ".tmp.temperatureC"
      }
   ]
}
```

### Adapter sonoff

alle Datenpunkte werden übernommen

### Adapter tr-064

#### Function `calllists` of tr-064

```text
{
   "allCount": {
      "state": ".all.count"
   },
   "allHTML": {
      "state": ".all.html"
   },
   "allJson": {
      "state": ".all.json"
   },
   "inboundCount": {
      "state": ".inbound.count"
   },
   "inboundHTML": {
      "state": ".inbound.html"
   },
   "inboundJson": {
      "state": ".inbound.json"
   },
   "missedCount": {
      "state": ".missed.count"
   },
   "missedHTML": {
      "state": ".missed.html"
   },
   "missedJson": {
      "state": ".missed.json"
   },
   "outboundCount": {
      "state": ".outbound.count"
   },
   "outboundHTML": {
      "state": ".outbound.html"
   },
   "outboundJson": {
      "state": ".outbound.json"
   }
}
```

#### Function `phonebook` of tr-064

```text
{
   "image": {
      "state": ".image"
   },
   "name": {
      "state": ".name"
   },
   "number": {
      "state": ".number"
   }
}
```

#### Function `states` of tr-064

```text
{
   "ab": {
      "state": ".ab"
   },
   "ip": {
      "state": ".externalIP"
   },
   "ipv6": {
      "state": ".externalIPv6"
   },
   "reboot": {
      "action": ".reboot",
      "actionElement": "IconButtonAction"
   },
   "reconnect": {
      "action": ".reconnectInternet",
      "actionElement": "IconButtonAction"
   },
   "wlan24": {
      "state": ".wlan24"
   },
   "wlan50": {
      "state": ".wlan50"
   }
}
```

### Adapter unifi

#### Function `health` of unifi

```text
{
   "lan.lan_ip": {
      "state": ".lan.lan_ip"
   },
   "lan.num_guest": {
      "state": ".lan.num_guest"
   },
   "lan.num_iot": {
      "state": ".lan.num_iot"
   },
   "lan.num_user": {
      "state": ".lan.num_user"
   },
   "lan.rx_bytes": {
      "state": ".lan.rx_bytes-r"
   },
   "lan.status": {
      "state": ".lan.status"
   },
   "lan.subsystem": {
      "state": ".lan.subsystem"
   },
   "lan.tx_bytes": {
      "state": ".lan.tx_bytes-r"
   },
   "vpn.status": {
      "state": ".vpn.status"
   },
   "vpn.subsystem": {
      "state": ".vpn.subsystem"
   },
   "wan.wan_ip": {
      "state": ".wan.wan_ip"
   },
   "wan.rx_bytes": {
      "state": ".wan.rx_bytes-r"
   },
   "wan.status": {
      "state": ".wan.status"
   },
   "wan.subsystem": {
      "state": ".wan.subsystem"
   },
   "wan.tx_bytes": {
      "state": ".wan.tx_bytes-r"
   },
   "wlan.num_guest": {
      "state": ".wlan.num_guest"
   },
   "wlan.num_iot": {
      "state": ".wlan.num_iot"
   },
   "wlan.num_user": {
      "state": ".wlan.num_user"
   },
   "wlan.rx_bytes": {
      "state": ".wlan.rx_bytes-r"
   },
   "wlan.status": {
      "state": ".wlan.status"
   },
   "wlan.subsystem": {
      "state": ".wlan.subsystem"
   },
   "wlan.tx_bytes": {
      "state": ".wlan.tx_bytes-r"
   },
   "www.latency": {
      "state": ".www.latency"
   },
   "www.rx_bytes": {
      "state": ".www.rx_bytes-r"
   },
   "www.status": {
      "state": ".www.status"
   },
   "www.subsystem": {
      "state": ".www.subsystem"
   },
   "www.tx_bytes": {
      "state": ".www.tx_bytes-r"
   },
   "www.uptime": {
      "state": ".www.uptime"
   },
   "www.xput_down": {
      "state": ".www.xput_down"
   },
   "www.xput_up": {
      "state": ".www.xput_up"
   },
   "www.speedtest.lastrun": {
      "state": ".www.speedtest.lastrun"
   },
   "www.speedtest.ping": {
      "state": ".www.speedtest.ping"
   },
   "www.speedtest.status": {
      "state": ".www.speedtest.status"
   }
}
```

#### Function `sysinfo` of unifi

```text
{
   "update_available": {
      "state": ".update_available"
   },
   "version": {
      "state": ".version"
   }
}
```

### Adapter wifilight

alle Datenpunkte werden übernommen

### Adapter yeelight-2

alle Datenpunkte werden übernommen

### Adapter zigbee

alle Datenpunkte werden übernommen

### Adapter zwave2

#### Function `thermostat` of zwave2

```text
{
   "valve": {
      "state": ".Multilevel_Switch.currentValue",
      "unit": "%",
      "icon": "rotate-right"
   },
   "mode": {
      "state": ".Thermostat_Mode.mode",
      "action": ".Thermostat_Mode.mode",
      "icon": {
         "0": "radiator-off",
         "1": "radiator",
         "11": "radiator-disabled",
         "15": "radiator"
      }
   },
   "setTemperatureEnergySave": {
      "state": ".Thermostat_Setpoint.setpoint_energySaveHeating",
      "action": ".Thermostat_Setpoint.setpoint_energySaveHeating",
      "unit": "°C",
      "icon": "radiator-disabled"
   },
   "temperature": {
      "state": ".Multilevel_Sensor.airTemperature"
   },
   "setTemperature": {
      "state": ".Thermostat_Setpoint.setpoint_heating",
      "action": ".Thermostat_Setpoint.setpoint_heating"
   }
}
```

