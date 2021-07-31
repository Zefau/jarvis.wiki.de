# Schalter

## vordefinierte Datenpunkte

| Datenpunkt Bezeichner | Datenpunkt Stil | Anzeige | Einheit | Icon | Icon Stil |
| :--- | :--- | :--- | :--- | :--- | :--- |
| `power` | - | - | - | - | - |

## Beispielkonfiguration

### Adapter hm-rpc

#### HmIP-WRC2

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `PRESS_LONG_BOTTOM` | `.1.PRESS_LONG` |  |  | `.1.PRESS_LONG` |
| `PRESS_SHORT_BOTTOM` | `.1.PRESS_SHORT` |  |  | `.1.PRESS_SHORT` |
| `PRESS_LONG_TOP` | `.2.PRESS_LONG` |  |  | `.2.PRESS_LONG` |
| `PRESS_SHORT_TOP` | `.2.PRESS_SHORT` |  |  | `.2.PRESS_SHORT` |

#### HM-RC-2-PBU-FM

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `PRESS_CONT_BOTTOM` | `.1.PRESS_CONT` |  |  | `.1.PRESS_CONT` |
| `PRESS_LONG_BOTTOM` | `.1.PRESS_LONG` |  |  | `.1.PRESS_LONG` |
| `PRESS_LONGRELEASE_BOTTOM` | `.1.PRESS_LONG_RELEASE` |  |  | `.1.PRESS_LONG_RELEASE` |
| `PRESS_SHORT_BOTTOM` | `.1.PRESS_SHORT` |  |  | `.1.PRESS_SHORT` |
| `PRESS_CONT_TOP` | `.2.PRESS_CONT` |  |  | `.2.PRESS_CONT` |
| `PRESS_LONG_TOP` | `.2.PRESS_LONG` |  |  | `.2.PRESS_LONG` |
| `PRESS_LONGRELEASE_TOP` | `.2.PRESS_LONG_RELEASE` |  |  | `.2.PRESS_LONG_RELEASE` |
| `PRESS_SHORT_TOP` | `.2.PRESS_SHORT` |  |  | `.2.PRESS_SHORT` |

#### HM-LC-Sw1-DR

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `power` | `.1.STATE` |  |  | `.1.STATE` |

#### HM-LC-SW1-FM

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `power` | `.1.STATE` |  |  | `.1.STATE` |

#### HM-PB-2-WM55

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `lowBatteryCh1` | `.1.LOWBAT` |  |  |  |
| `PRESS_LONG_BOTTOM` | `.1.PRESS_LONG` |  |  | `.1.PRESS_LONG` |
| `PRESS_SHORT_BOTTOM` | `.1.PRESS_SHORT` |  |  | `.1.PRESS_SHORT` |
| `PRESS_LONG_TOP` | `.2.PRESS_LONG` |  |  | `.2.PRESS_LONG` |
| `PRESS_SHORT_TOP` | `.2.PRESS_SHORT` |  |  | `.2.PRESS_SHORT` |

#### HB-UNI-SenAct-4-4-RC

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `stateCh1` | `.1.STATE` |  |  |  |
| `stateCh2` | `.2.STATE` |  |  |  |
| `stateCh3` | `.3.STATE` |  |  |  |
| `stateCh4` | `.4.STATE` |  |  |  |
| `PRESS_LONG1` | `.5.PRESS_LONG` |  |  | `.5.PRESS_LONG` |
| `PRESS_SHORT1` | `.5.PRESS_SHORT` |  |  | `.5.PRESS_SHORT` |
| `PRESS_LONG2` | `.6.PRESS_LONG` |  |  | `.6.PRESS_LONG` |
| `PRESS_SHORT2` | `.6.PRESS_SHORT` |  |  | `.6.PRESS_SHORT` |
| `PRESS_LONG3` | `.7.PRESS_LONG` |  |  | `.7.PRESS_LONG` |
| `PRESS_SHORT3` | `.7.PRESS_SHORT` |  |  | `.7.PRESS_SHORT` |
| `PRESS_LONG4` | `.8.PRESS_LONG` |  |  | `.8.PRESS_LONG` |
| `PRESS_SHORT4` | `.8.PRESS_SHORT` |  |  | `.8.PRESS_SHORT` |

### Adapter shelly

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `input` | `.Relay0.Input` |  |  |  |
| `inputCh2` | `.Relay1.Input` |  |  |  |
| `inputCh3` | `.Relay2.Input` |  |  |  |
| `event` | `.Relay0.Event` |  |  |  |
| `eventCh2` | `.Relay1.Event` |  |  |  |
| `eventCh3` | `.Relay2.Event` |  |  |  |
| `eventCount` | `.Relay0.EventCount` |  |  |  |
| `eventCountCh2` | `.Relay1.EventCount` |  |  |  |
| `eventCountCh3` | `.Relay2.EventCount` |  |  |  |

