# Fenster

## vordefinierte Datenpunkte

| Datenpunkt Bezeichner | Datenpunkt Stil | Anzeige | Einheit | Icon | Icon Stil |
| :--- | :--- | :--- | :--- | :--- | :--- |
| `open` | - | `{  "0": "geschlossen",  "1": "offen",  "2": "offen",  "false": "geschlossen",  "true": "offen" }` | - | `{  "0": "window-closed-variant",  "1": "window-open-variant",  "false": "window-closed-variant",  "true": "window-open-variant" }` | - |

## Beispielkonfiguration

### Adapter hm-rpc

#### HmIP-SWDM

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `open` | `.1.STATE` |  |  |  |

#### HmIP-SWDO-I

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `open` | `.1.STATE` |  |  |  |

#### HmIP-SWDO-PL

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `open` | `.1.STATE` |  |  |  |

#### HmIP-SWDO

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `open` | `.1.STATE` |  |  |  |

#### HmIP-SRH

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `open` | `.1.STATE` |  | `{  "0": "window#open#closed",  "1": "window#open#tilted",  "2": "window#open#opened" }` |  |

#### HM-Sec-RHS

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `open` | `.1.STATE` |  | `{  "0": "window#open#closed",  "1": "window#open#tilted",  "2": "window#open#opened" }` |  |

#### HM-Sec-Sco

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `open` | `.1.STATE` |  |  |  |

#### HM-Sec-SC-2

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `open` | `.1.STATE` |  |  |  |

### Adapter hmip

#### HmIP-SWDO

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `open` | `.channels.1.windowOpen` |  |  |  |

#### HmIP-SWDO-I

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `open` | `.channels.1.windowOpen` |  |  |  |

#### HmIP-SRH

| State Key | State | Einheit | Anzeige | Action |
| :--- | :--- | :--- | :--- | :--- |
| `open` | `.channels.1.windowOpen` |  |  |  |
| `state` | `.channels.1.windowState` |  | `{  "CLOSED": "window#open#closed",  "TILTED": "window#open#tilted",  "OPEN": "window#open#opened" }` |  |

