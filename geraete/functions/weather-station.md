# Wetter-Station

## vordefinierte Datenpunkte

| Datenpunkt Bezeichner | Datenpunkt Stil | Anzeige | Einheit | Icon | Icon Stil |
| :--- | :--- | :--- | :--- | :--- | :--- |
| `humidity` | - | - | - | - | - |
| `wind` | - | - | - | - | - |
| `temperature` | - | - | - | - | - |
| `illumination` | - | - | - | `"mdi-brightness-7"` | - |
| `sunshineduration` | - | - | - | `"mdi-weather-sunny"` | - |

## Beispielkonfiguration

### Adapter hm-rpc

#### HmIP-STHO

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `temperature` | `.1.ACTUAL_TEMPERATURE` |  |  |  |
| `humidity` | `.1.HUMIDITY` |  |  |  |

#### HmIP-STHO-A

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `temperature` | `.1.ACTUAL_TEMPERATURE` |  |  |  |
| `humidity` | `.1.HUMIDITY` |  |  |  |

#### HmIP-SWO-B

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `humidity` | `.1.HUMIDITY` |  |  |  |
| `wind` | `.1.WIND_SPEED` |  |  |  |
| `temperature` | `.1.ACTUAL_TEMPERATURE` |  |  |  |
| `illumination` | `.1.ILLUMINATION` |  |  |  |
| `sunshineDuration` | `.1.SUNSHINEDURATION` |  |  |  |

#### HmIP-SWO-PL

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `humidity` | `.1.HUMIDITY` |  |  |  |
| `wind` | `.1.WIND_SPEED` |  |  |  |
| `temperature` | `.1.ACTUAL_TEMPERATURE` |  |  |  |
| `illumination` | `.1.ILLUMINATION` |  |  |  |
| `sunshineDuration` | `.1.SUNSHINEDURATION` |  |  |  |
| `raining` | `.1.RAINING` |  |  |  |
| `rainCounter` | `.1.RAIN_COUNTER` |  |  |  |

#### HM-WDS40-TH-I-2

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `temperature` | `.1.TEMPERATURE` |  |  |  |
| `humidity` | `.1.HUMIDITY` |  |  |  |

### Adapter hmip

#### HmIP-STHO

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `temperature` | `.channels.1.actualTemperature` |  |  |  |
| `humidity` | `.channels.1.humidity` |  |  |  |
| `vapor` | `.channels.1.vaporAmount` |  |  |  |
| `display` | `.channels.1.display` |  |  |  |

#### HmIP-STHO-A

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `temperature` | `.1.ACTUAL_TEMPERATURE` |  |  |  |
| `humidity` | `.1.HUMIDITY` |  |  |  |

#### HmIP-SWO-B

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `humidity` | `.1.HUMIDITY` |  |  |  |
| `wind` | `.1.WIND_SPEED` |  |  |  |
| `temperature` | `.1.ACTUAL_TEMPERATURE` |  |  |  |
| `illumination` | `.1.ILLUMINATION` |  |  |  |
| `sunshineduration` | `.1.SUNSHINEDURATION` |  |  |  |

