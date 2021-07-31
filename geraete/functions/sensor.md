# Sensor

## vordefinierte Datenpunkte

| Datenpunkt Bezeichner | Datenpunkt Stil | Anzeige | Einheit | Icon | Icon Stil |
| :--- | :--- | :--- | :--- | :--- | :--- |
| `temperature` | - | - | `" °C"` | `"mdi-thermometer"` | - |
| `humidity` | - | - | `" %"` | - | - |
| `illumination` | - | - | `" lux"` | `"mdi-brightness-7"` | - |
| `pressure` | - | - | `" hPa"` | `"mdi-air-purifier"` | - |

## Beispielkonfiguration

### Adapter hm-rpc

#### HM-Sec-TiS

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `power` | `.1.STATE` |  |  |  |

#### HmIP-SLO

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `illuminationAverage` | `.1.AVERAGE_ILLUMINATION` |  `Lux` |  |  |
| `illuminationCurrent` | `.1.CURRENT_ILLUMINATION` |  `Lux` |  |  |
| `illuminationHighest` | `.1.HIGHEST_ILLUMINATION` |  `Lux` |  |  |
| `illuminationLowest` | `.1.LOWEST_ILLUMINATION` |  `Lux` |  |  |

#### HmIP-SWD

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `alarm` | `.1.ALARMSTATE` |  |  |  |
| `alarmMoisture` | `.1.MOISTURE_DETECTED` |  |  |  |
| `alarmWaterlevel` | `.1.WATERLEVEL_DETECTED` |  |  |  |

#### HM-Sec-WDS-2

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `alarm` | `.1.STATE` |  |  |  |

### Adapter shelly

#### battery

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `0` | `.sensor.battery` |  |  |  |
| `1` | `.bat.value` |  |  |  |

#### humidity

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `state` |  |  |  |  |

#### flood

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `state` |  |  |  |  |

#### door

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `state` |  |  |  |  |

#### illumination

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `state` |  |  |  |  |

#### tilt

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `state` |  |  |  |  |

#### vibration

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `state` |  |  |  |  |

#### temperature

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `0` | `.sensor.temperatureC` |  |  |  |
| `1` | `.tmp.temperatureC` |  |  |  |

