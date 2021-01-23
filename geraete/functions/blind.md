# Rollladen / Jalousie

## vordefinierte Datenpunkte

| Datenpunkt Bezeichner | Datenpunkt Stil | Anzeige | Einheit | Icon | Icon Stil |
| :--- | :--- | :--- | :--- | :--- | :--- |
| `level` | - | - | `" %"` | `{  "default": "window-shutter-open",  ">90": "window-shutter-open",  "}` | - |
| `level2` | - | - | `" %"` | `{  "default": "window-shutter-open",  ">90": "window-shutter-open",  "}` | - |
| `activity` | - | `{  "true": "in Bewegung",  "false": "keine" }` | - | `{  "true": "pan-vertical",  "false": "dots-vertical" }` | - |

## Beispielkonfiguration

### Adapter hm-rpc

#### HmIP-BBL

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `level` | `.3.LEVEL` |  |  | `.4.LEVEL` |
| `level2` | `.3.LEVEL2` |  |  | `.4.LEVEL2` |
| `activity` | `.3.ACTIVITY_STATE` |  |  |  |
| `stop` |  |  |  | `.4.STOP` |

#### HmIP-FROLL

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `level` | `.3.LEVEL` |  |  | `.4.LEVEL` |
| `activity` | `.3.ACTIVITY_STATE` |  |  |  |
| `stop` |  |  |  | `.4.STOP` |

#### HmIP-BROLL

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `level` | `.3.LEVEL` |  |  | `.4.LEVEL` |
| `level2` | `.3.LEVEL2` |  |  | `.4.LEVEL2` |
| `activity` | `.3.ACTIVITY_STATE` |  |  |  |
| `stop` |  |  |  | `.4.STOP` |

#### HM-LC-Bl1-FM

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `level` | `.1.LEVEL` |  |  | `.1.LEVEL` |
| `activity` | `.1.WORKING` |  |  |  |
| `stop` |  |  |  | `.1.STOP` |

#### HM-LC-Bl1PBU-FM

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `level` | `.1.LEVEL` |  |  | `.1.LEVEL` |
| `activity` | `.1.WORKING` |  |  |  |
| `stop` |  |  |  | `.1.STOP` |

#### HmIPW-DRBL4

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `levelCh1` | `.2.LEVEL` |  |  | `.2.LEVEL` |
| `level2Ch1` | `.2.LEVEL_2` |  |  | `.2.LEVEL_2` |
| `activityCh1` | `.2.PROCESS` |  |  |  |
| `stopCh1` |  |  |  | `.2.STOP` |
| `levelCh2` | `.6.LEVEL` |  |  | `.6.LEVEL` |
| `level2Ch2` | `.6.LEVEL_2` |  |  | `.6.LEVEL_2` |
| `activityCh2` | `.6.PROCESS` |  |  |  |
| `stopCh2` |  |  |  | `.6.STOP` |
| `levelCh3` | `.10.LEVEL` |  |  | `.10.LEVEL` |
| `level2Ch3` | `.10.LEVEL_2` |  |  | `.10.LEVEL_2` |
| `activityCh3` | `.10.PROCESS` |  |  |  |
| `stopCh3` |  |  |  | `.10.STOP` |
| `levelCh4` | `.14.LEVEL` |  |  | `.14.LEVEL` |
| `level2Ch4` | `.14.LEVEL_2` |  |  | `.14.LEVEL_2` |
| `activityCh4` | `.14.PROCESS` |  |  |  |
| `stopCh4` |  |  |  | `.14.STOP` |

### Adapter hmip

#### HmIP-BBL

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `level` | `.channels.1.shutterLevel` |  |  | `.channels.1.shutterLevel` |
| `activity` | `.channels.1.processing` |  |  |  |
| `stop` |  |  |  | `.channels.1.stop` |

#### HmIP-BROLL

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `level` | `.channels.1.shutterLevel` |  |  | `.channels.1.shutterLevel` |
| `activity` | `.channels.1.processing` |  |  |  |
| `stop` |  |  |  | `.channels.1.stop` |

### Adapter shelly

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `level` | `.Shutter.Position` |  |  | `.Shutter.Position` |
| `activity` | `.Shutter.state` |  |  | `.Shutter.Pause` |

