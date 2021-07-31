# Steckdose

## vordefinierte Datenpunkte

| Datenpunkt Bezeichner | Datenpunkt Stil | Anzeige | Einheit | Icon | Icon Stil |
| :--- | :--- | :--- | :--- | :--- | :--- |
| `power` | - | - | - | - | - |
| `consumption` | - | - | `" W"` | `{  "default": "mdi-power-plug-off-outline",  ">0": "mdi-power-plug" }` | - |
| `meter` | - | - | `" W"` | `{  "default": "mdi-power-plug-off-outline",  ">0": "mdi-power-plug" }` | - |

## Beispielkonfiguration

### Adapter hm-rpc

#### HmIP-FSM

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `power` | `.2.STATE` |  |  | `.2.STATE` |
| `timerOff` | `.2.ON_TIME` |  |  | `.2.ON_TIME` |
| `powerCurrent` | `.5.CURRENT` |  `mA` |  |  |
| `powerFrequency` | `.5.FREQUENCY` |  |  |  |
| `powerCounter` | `.5.ENERGY_COUNTER` |  `Wh` |  |  |
| `powerMeter` | `.5.POWER` |  `W` |  |  |
| `powerVoltage` | `.5.VOLTAGE` |  `V` |  |  |

#### HmIP-PS

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `power` | `.3.STATE` |  |  |  |

#### HmIP-PSM

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `power` | `.3.STATE` |  |  |  |
| `meter` | `.6.POWER` |  |  |  |

#### HM-ES-PMSw1-Pl-DN-R1

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `power` | `.1.STATE` |  |  | `.1.STATE` |
| `timerOff` | `.1.ON_TIME` |  |  | `.1.ON_TIME` |
| `powerCurrent` | `.2.CURRENT` |  `mA` |  |  |
| `powerFrequency` | `.2.FREQUENCY` |  |  |  |
| `powerCounter` | `.2.ENERGY_COUNTER` |  `Wh` |  |  |
| `powerMeter` | `.2.POWER` |  `W` |  |  |
| `powerVoltage` | `.2.VOLTAGE` |  `V` |  |  |

#### HM-LC-Sw1-Pl-2

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `power` | `.1.STATE` |  |  | `.1.STATE` |
| `timerOff` | `.1.ON_TIME` |  |  | `.1.ON_TIME` |

#### HM-LC-Sw1-Pl-DN-R1

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `power` | `.1.STATE` |  |  | `.1.STATE` |
| `timerOff` | `.1.ON_TIME` |  |  | `.1.ON_TIME` |

#### HM-ES-PMSw1-DR

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `power` | `.1.STATE` |  |  | `.1.STATE` |
| `timerOff` | `.1.ON_TIME` |  |  | `.1.ON_TIME` |
| `boot` | `.2.BOOT` |  |  | `.2.BOOT` |
| `powerCurrent` | `.2.CURRENT` |  `mA` |  |  |
| `powerFrequency` | `.2.FREQUENCY` |  |  |  |
| `powerCounter` | `.2.ENERGY_COUNTER` |  `Wh` |  |  |
| `powerMeter` | `.2.POWER` |  `W` |  |  |
| `powerVoltage` | `.2.VOLTAGE` |  `V` |  |  |

#### HM-ES-PMSw1-Pl

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `power` | `.1.STATE` |  |  | `.1.STATE` |
| `timerOff` | `.1.ON_TIME` |  |  | `.1.ON_TIME` |
| `boot` | `.2.BOOT` |  |  | `.2.BOOT` |
| `powerCurrent` | `.2.CURRENT` |  `mA` |  |  |
| `powerFrequency` | `.2.FREQUENCY` |  |  |  |
| `powerCounter` | `.2.ENERGY_COUNTER` |  `Wh` |  |  |
| `powerMeter` | `.2.POWER` |  `W` |  |  |
| `powerVoltage` | `.2.VOLTAGE` |  `V` |  |  |

### Adapter hmip

#### HmIP-PS

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `power` | `.channels.1.on` |  |  | `.channels.1.on` |

### Adapter shelly

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `power` | `.Relay0.Switch` |  |  | `.Relay0.Switch` |
| `powerCounter` | `.Relay0.Energy` |  `Wh` |  |  |
| `powerMeter` | `.Relay0.Power` |  `W` |  |  |

