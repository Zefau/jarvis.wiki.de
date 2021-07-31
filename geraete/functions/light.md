# Licht

## vordefinierte Datenpunkte

| Datenpunkt Bezeichner | Datenpunkt Stil | Anzeige | Einheit | Icon | Icon Stil |
| :--- | :--- | :--- | :--- | :--- | :--- |
| `on` | - | - | - | `{  "true": "lightbulb-on",  "false": "lightbulb-off-outline" }` | - |
| `power` | - | - | - | `{  "true": "lightbulb-on",  "false": "lightbulb-off-outline" }` | - |
| `dimmer` | `{  "0": {   "color": "#999"  } }` | `{  "0": "aus" }` | `"val => val > 0 ? \" %\" : null"` | `{  "0": "lightbulb-off-outline",  "default": "lightbulb-on" }` | - |
| `level` | `{  "0": {   "color": "#999"  } }` | `{  "0": "aus" }` | `"val => val > 0 ? \" %\" : null"` | `{  "0": "lightbulb-off-outline",  "default": "lightbulb-on" }` | - |
| `ct` | - | - | `" °K"` | `{  "default": "thermometer" }` | - |
| `colortemperature` | - | - | `" °K"` | `{  "default": "thermometer" }` | - |
| `hue` | - | - | `" °"` | `{  "default": "palette" }` | - |
| `rgb` | - | - | - | `{  "default": "palette" }` | - |
| `hsv` | - | - | - | `{  "default": "palette" }` | - |
| `hex` | - | - | - | `{  "default": "palette" }` | - |

## Beispielkonfiguration

### Adapter hm-rpc

#### HmIP-BSM

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `power` | `.4.STATE` |  |  | `.4.STATE` |
| `powerMeter` | `.7.POWER` |  |  |  |
| `powerVoltage` | `.7.VOLTAGE` |  |  |  |
| `powerFrequency` | `.7.FREQUENCY` |  |  |  |

#### HmIP-BSL

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `power` | `.4.STATE` |  |  | `.4.STATE` |
| `levelTop` | `.8.LEVEL` |  |  | `.8.LEVEL` |
| `colorTop` | `.8.COLOR` |  | `{  "0": "BLACK",  "1": "BLUE",  "2": "GREEN",  "3": "TURQUOISE",  "4": "RED",  "5": "PURPLE",  "6": "YELLOW",  "7": "WHITE" }` | `.8.COLOR` |
| `levelBottom` | `.12.LEVEL` |  |  | `.12.LEVEL` |
| `colorBottom` | `.12.COLOR` |  | `{  "0": "BLACK",  "1": "BLUE",  "2": "GREEN",  "3": "TURQUOISE",  "4": "RED",  "5": "PURPLE",  "6": "YELLOW",  "7": "WHITE" }` | `.12.COLOR` |

#### HmIP-BRC2

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `power` | `.3.STATE` |  |  | `.4.STATE` |

#### HmIP-BDT

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `level` | `.3.LEVEL` |  |  | `.4.LEVEL` |

#### HM-LC-Dim1T-FM

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `level` | `.1.LEVEL` |  |  | `.1.LEVEL` |
| `timerOff` | `.1.ON_TIME` |  |  | `.1.ON_TIME` |
| `timerOn` | `.1.RAMP_TIME` |  |  | `.1.RAMP_TIME` |

#### HM-LC-RGBW-WM

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `level` | `.1.LEVEL` |  |  | `.1.LEVEL` |
| `timerOff` | `.1.ON_TIME` |  |  | `.1.ON_TIME` |
| `timerOn` | `.1.RAMP_TIME` |  |  | `.1.RAMP_TIME` |
| `hue` | `.2.COLOR` |  |  | `.2.COLOR` |

#### HM-LC-Sw1PBU-FM

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `power` | `.1.STATE` |  |  | `.1.STATE` |

#### HM-LC-Sw1-FM

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `power` | `.1.STATE` |  |  | `.1.STATE` |
| `timerOff` | `.1.ON_TIME` |  |  | `.1.ON_TIME` |
| `activity` | `.1.WORKING` |  |  | `.1.WORKING` |

#### HM-LC-Sw1-DR

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `power` | `.1.STATE` |  |  | `.1.STATE` |
| `timerOff` | `.1.ON_TIME` |  |  | `.1.ON_TIME` |

#### HM-LC-Sw2-FM

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `power` | `.1.STATE` |  |  | `.1.STATE` |
| `timerOff` | `.1.ON_TIME` |  |  | `.1.ON_TIME` |
| `powerCh2` | `.2.STATE` |  |  | `.2.STATE` |
| `timerOffCh2` | `.2.ON_TIME` |  |  | `.2.ON_TIME` |

#### HM-LC-Sw4-DR

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `power` | `.1.STATE` |  |  | `.1.STATE` |
| `timerOff` | `.1.ON_TIME` |  |  | `.1.ON_TIME` |
| `powerCh2` | `.2.STATE` |  |  | `.2.STATE` |
| `timerOffCh2` | `.2.ON_TIME` |  |  | `.2.ON_TIME` |
| `powerCh3` | `.3.STATE` |  |  | `.3.STATE` |
| `timerOffCh3` | `.3.ON_TIME` |  |  | `.3.ON_TIME` |
| `powerCh4` | `.4.STATE` |  |  | `.4.STATE` |
| `timerOffCh4` | `.4.ON_TIME` |  |  | `.4.ON_TIME` |

#### HM-LC-Dim1TPBU-FM

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `level` | `.1.LEVEL` |  |  | `.1.LEVEL` |

#### HM-LC-Dim1T-Pl-3

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `level` | `.1.LEVEL` |  |  | `.1.LEVEL` |
| `timerOff` | `.1.ON_TIME` |  |  | `.1.ON_TIME` |
| `timerOn` | `.1.RAMP_TIME` |  |  | `.1.RAMP_TIME` |

### Adapter hue-extended

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `power` | `.action.on` |  |  | `.action.on` |
| `level` | `.action.level` |  |  | `.action.level` |
| `colorTemperature` | `.action.colorTemperature` |  |  | `.action.colorTemperature` |
| `hue` | `.action.hue` |  |  | `.action.hue` |
| `hex` | `.action.hex` |  |  | `.action.hex` |

### Adapter hue

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `power` | `.on` |  |  | `.on` |
| `level` | `.level` |  |  | `.level` |
| `colorTemperature` | `.ct` |  |  | `.ct` |
| `hue` | `.hue` |  |  | `.hue` |
| `reachability` | `.reachable` |  |  |  |

### Adapter mqtt

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `dimmer` | `.Dimmer` |  |  | `.Dimmer` |
| `ct` | `.CT` |  |  | `.CT` |
| `hue` | `.Hue` |  |  | `.Hue` |
| `sat` | `.Saturation` |  |  | `.Saturation` |

### Adapter shelly

#### power

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `0` | `.lights.Switch` |  |  | `.lights.Switch` |
| `1` | `.white0.Switch` |  |  | `.white0.Switch` |

#### powerCh1

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `state` |  |  |  |  |
| `action` |  |  |  |  |
| `actionElement` |  |  |  |  |

#### powerCh2

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `state` |  |  |  |  |
| `action` |  |  |  |  |
| `actionElement` |  |  |  |  |

#### powerCh3

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `state` |  |  |  |  |
| `action` |  |  |  |  |
| `actionElement` |  |  |  |  |

#### colorTemperature

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `state` |  |  |  |  |
| `action` |  |  |  |  |
| `actionElement` |  |  |  |  |
| `properties` |  |  |  |  |

#### level

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `0` | `.lights.brightness` |  |  | `.lights.brightness` |
| `1` | `.white0.brightness` |  |  | `.white0.brightness` |

#### levelCh1

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `state` |  |  |  |  |
| `action` |  |  |  |  |

#### levelCh2

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `state` |  |  |  |  |
| `action` |  |  |  |  |

#### levelCh3

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `state` |  |  |  |  |
| `action` |  |  |  |  |

#### hex

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `state` |  |  |  |  |
| `action` |  |  |  |  |

#### hue

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `state` |  |  |  |  |
| `action` |  |  |  |  |

#### powerMeter

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `0` | `.Relay0.Power` |  `W` |  |  |
| `1` | `.lights.Power` |  `W` |  |  |
| `2` | `.white0.Power` |  `W` |  |  |
| `3` | `.Emeter0.Power` |  `W` |  |  |

#### powerMeterCh1

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `0` | `.Relay1.Power` |  `W` |  |  |
| `1` | `.white1.Power` |  `W` |  |  |
| `2` | `.Emeter1.Power` |  `W` |  |  |

#### powerMeterCh2

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `0` | `.Relay2.Power` |  `W` |  |  |
| `1` | `.white2.Power` |  `W` |  |  |
| `2` | `.Emeter2.Power` |  `W` |  |  |

#### powerMeterCh3

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `0` | `.Relay3.Power` |  `W` |  |  |
| `1` | `.white3.Power` |  `W` |  |  |

#### powerCounter

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `0` | `.Relay0.Energy` |  `Wh` |  |  |
| `1` | `.lights.Energy` |  `Wh` |  |  |
| `2` | `.white0.Energy` |  `Wh` |  |  |
| `3` | `.Emeter0.Total` |  `Wh` |  |  |

#### powerCounterCh1

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `0` | `.Relay1.Energy` |  `Wh` |  |  |
| `1` | `.white1.Energy` |  `Wh` |  |  |
| `2` | `.Emeter1.Total` |  `Wh` |  |  |

#### powerCounterCh2

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `0` | `.Relay2.Energy` |  `Wh` |  |  |
| `1` | `.white2.Energy` |  `Wh` |  |  |
| `2` | `.Emeter2.Total` |  `Wh` |  |  |

#### powerCounterCh3

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `0` | `.Relay3.Energy` |  `Wh` |  |  |
| `1` | `.white3.Energy` |  `Wh` |  |  |

#### powerCurrent

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `state` |  |  |  |  |
| `unit` |  |  |  |  |

#### powerCurrentCh1

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `state` |  |  |  |  |
| `unit` |  |  |  |  |

#### powerCurrentCh2

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `state` |  |  |  |  |
| `unit` |  |  |  |  |

#### powerVoltage

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `state` |  |  |  |  |
| `unit` |  |  |  |  |

#### powerVoltageCh1

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `state` |  |  |  |  |
| `unit` |  |  |  |  |

#### powerVoltageCh2

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `state` |  |  |  |  |
| `unit` |  |  |  |  |

#### powerCounterReturned

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `state` |  |  |  |  |
| `unit` |  |  |  |  |

#### powerCounterReturnedCh1

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `state` |  |  |  |  |
| `unit` |  |  |  |  |

#### powerCounterReturnedCh2

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `state` |  |  |  |  |
| `unit` |  |  |  |  |

#### powerTotalCurrent

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `state` |  |  |  |  |
| `unit` |  |  |  |  |

#### powerTotalConsumed

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `state` |  |  |  |  |
| `unit` |  |  |  |  |

#### powerTotalInstant

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `state` |  |  |  |  |
| `unit` |  |  |  |  |

#### powerTotalVoltage

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `state` |  |  |  |  |
| `unit` |  |  |  |  |

#### powerTotalVoltageMean

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `state` |  |  |  |  |
| `unit` |  |  |  |  |

