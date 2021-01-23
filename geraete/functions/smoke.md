# Rauchmelder

## vordefinierte Datenpunkte

| Datenpunkt Bezeichner | Datenpunkt Stil | Anzeige | Einheit | Icon | Icon Stil |
| :--- | :--- | :--- | :--- | :--- | :--- |
| `alarm` | - | - | - | `{  "0": "mdi-alarm-light-outline",  "1": "mdi-alarm-light",  "2": "mdi-alarm-light",  "3": "mdi-alarm-light",  "true": "mdi-alarm-light",  "false": "mdi-alarm-light-outline" }` | - |

## Beispielkonfiguration

### Adapter hm-rpc

#### HmIP-SWSD

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `alarm` | `.1.SMOKE_DETECTOR_ALARM_STATUS` |  | `{  "0": "IDLE_OFF",  "1": "PRIMARY_ALARM",  "2": "INTRUSION_ALARM",  "3": "SECONDARY_ALARM" }` |  |

#### HM-Sec-SD

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `alarm` | `.1.STATE` |  |  |  |
| `lowBatteryCh1` | `.1.LOWBAT` |  |  |  |

#### HM-Sec-SD-2

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `alarm` | `.1.STATE` |  |  |  |
| `lowBatteryCh1` | `.1.LOWBAT` |  |  |  |

#### HM-Sec-SD-2-Team

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `alarm` | `.1.STATE` |  |  |  |

