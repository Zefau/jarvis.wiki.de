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

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `power` | `.lights.Switch` |  |  | `.lights.Switch` |
| `level` | `.lights.brightness` |  |  | `.lights.brightness` |

