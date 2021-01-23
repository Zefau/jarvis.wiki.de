# Bewegungs-/Präsenzmelder

## vordefinierte Datenpunkte

| Datenpunkt Bezeichner | Datenpunkt Stil | Anzeige | Einheit | Icon | Icon Stil |
| :--- | :--- | :--- | :--- | :--- | :--- |
| `motion` | - | - | - | `{  "true": "motion-sensor",  "false": "motion-sensor-off" }` | - |
| `presence` | - | - | - | `{  "true": "motion-sensor",  "false": "motion-sensor-off" }` | - |

## Beispielkonfiguration

### Adapter hm-rpc

#### HmIP-SMI55

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `motion` | `.3.MOTION` |  |  |  |
| `brightness` | `.3.BRIGHTNESS` |  |  |  |

#### HmIP-SMI

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `motion` | `.1.MOTION` |  |  |  |
| `illumination` | `.1.ILLUMINATION` |  |  |  |

#### HmIP-SMO-A

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `motion` | `.1.MOTION` |  |  |  |
| `illumination` | `.1.ILLUMINATION` |  |  |  |

#### HmIP-SAM

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `motion` | `.1.MOTION` |  |  |  |
| `illumination` | `.1.ILLUMINATION` |  |  |  |

#### HmIP-SPI

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `presence` | `.1.PRESENCE_DETECTION_STATE` |  |  |  |
| `illumination` | `.1.ILLUMINATION` |  |  |  |

#### HM-PB-6-WM55

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `PRESS_LONG1` | `.1.PRESS_LONG` |  |  | `.1.PRESS_LONG` |
| `PRESS_SHORT1` | `.1.PRESS_SHORT` |  |  | `.1.PRESS_SHORT` |
| `PRESS_LONG2` | `.2.PRESS_LONG` |  |  | `.2.PRESS_LONG` |
| `PRESS_SHORT2` | `.2.PRESS_SHORT` |  |  | `.2.PRESS_SHORT` |
| `PRESS_LONG3` | `.3.PRESS_LONG` |  |  | `.3.PRESS_LONG` |
| `PRESS_SHORT3` | `.3.PRESS_SHORT` |  |  | `.3.PRESS_SHORT` |
| `PRESS_LONG4` | `.4.PRESS_LONG` |  |  | `.4.PRESS_LONG` |
| `PRESS_SHORT4` | `.4.PRESS_SHORT` |  |  | `.4.PRESS_SHORT` |
| `PRESS_LONG5` | `.5.PRESS_LONG` |  |  | `.5.PRESS_LONG` |
| `PRESS_SHORT5` | `.5.PRESS_SHORT` |  |  | `.5.PRESS_SHORT` |
| `PRESS_LONG6` | `.6.PRESS_LONG` |  |  | `.6.PRESS_LONG` |
| `PRESS_SHORT6` | `.6.PRESS_SHORT` |  |  | `.6.PRESS_SHORT` |

#### HM-Sen-MDIR-WM55

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `PRESS_LONG_BOTTOM` | `.1.PRESS_LONG` |  |  | `.1.PRESS_LONG` |
| `PRESS_SHORT_BOTTOM` | `.1.PRESS_SHORT` |  |  | `.1.PRESS_SHORT` |
| `PRESS_LONG_TOP` | `.2.PRESS_LONG` |  |  | `.2.PRESS_LONG` |
| `PRESS_SHORT_TOP` | `.2.PRESS_SHORT` |  |  | `.2.PRESS_SHORT` |
| `motion` | `.3.MOTION` |  |  |  |
| `illumination` | `.3.ILLUMINATION` |  |  |  |

#### HM-Sen-MDIR-O-2

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `motion` | `.1.MOTION` |  |  |  |
| `brightness` | `.1.BRIGHTNESS` |  |  |  |

#### HM-Sen-MDIR-O-3

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `motion` | `.1.MOTION` |  |  |  |
| `brightness` | `.1.BRIGHTNESS` |  |  |  |

### Adapter hmip

#### HmIP-SMI

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `motion` | `.channels.1.motionDetected` |  |  |  |
| `illumination` | `.channels.1.illumination` |  |  |  |

