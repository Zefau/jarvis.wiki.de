
# Gewerk Rollladen / Jalousie (`blind`)

## vordefinierte Datenpunkte

<table><thead><tr><th>Datenpunkt Bezeichner</th><th>Datenpunkt Stil</th><th>Anzeige</th><th>Einheit</th><th>Icon</th><th>Icon Stil</th></tr></thead>
<tbody><tr><td><code>level</code></td><td>-</td><td>-</td><td><code>&quot;&nbsp;%&quot;</code></td><td><code>{<br />&nbsp;&quot;default&quot;:&nbsp;&quot;window-shutter-open&quot;,<br />&nbsp;&quot;&gt;90&quot;:&nbsp;&quot;window-shutter-open&quot;,<br />&nbsp;&quot;&lt;=90&quot;:&nbsp;&quot;window-shutter&quot;<br />}</code></td><td>-</td></tr></tbody>
<tbody><tr><td><code>level2</code></td><td>-</td><td>-</td><td><code>&quot;&nbsp;%&quot;</code></td><td><code>{<br />&nbsp;&quot;default&quot;:&nbsp;&quot;window-shutter-open&quot;,<br />&nbsp;&quot;&gt;90&quot;:&nbsp;&quot;window-shutter-open&quot;,<br />&nbsp;&quot;&lt;=90&quot;:&nbsp;&quot;window-shutter&quot;<br />}</code></td><td>-</td></tr></tbody>
<tbody><tr><td><code>activity</code></td><td>-</td><td><code>{<br />&nbsp;&quot;true&quot;:&nbsp;&quot;in&nbsp;Bewegung&quot;,<br />&nbsp;&quot;false&quot;:&nbsp;&quot;keine&quot;<br />}</code></td><td>-</td><td><code>{<br />&nbsp;&quot;true&quot;:&nbsp;&quot;pan-vertical&quot;,<br />&nbsp;&quot;false&quot;:&nbsp;&quot;dots-vertical&quot;<br />}</code></td><td>-</td></tr></tbody>
<tbody><tr><td><code>stop</code></td><td>-</td><td>-</td><td>-</td><td><code>{<br />&nbsp;&quot;default&quot;:&nbsp;&quot;mdi-stop-circle&quot;<br />}</code></td><td>-</td></tr></tbody>
</table>

## Beispielkonfiguration


### Adapter hm-rpc


#### HmIP-BBL

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>level</td>
<td><code>.3.LEVEL</code></td>
<td><code></code></td>
<td></td>
<td><code>.4.LEVEL</code></td>
</tr>
<tr>
<td><code>level2</td>
<td><code>.3.LEVEL2</code></td>
<td><code></code></td>
<td></td>
<td><code>.4.LEVEL2</code></td>
</tr>
<tr>
<td><code>activity</td>
<td><code>.3.ACTIVITY_STATE</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>stop</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code>.4.STOP</code></td>
</tr>
</tbody></table>

#### HmIP-FROLL

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>level</td>
<td><code>.3.LEVEL</code></td>
<td><code></code></td>
<td></td>
<td><code>.4.LEVEL</code></td>
</tr>
<tr>
<td><code>activity</td>
<td><code>.3.ACTIVITY_STATE</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>stop</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code>.4.STOP</code></td>
</tr>
</tbody></table>

#### HmIP-BROLL

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>level</td>
<td><code>.3.LEVEL</code></td>
<td><code></code></td>
<td></td>
<td><code>.4.LEVEL</code></td>
</tr>
<tr>
<td><code>level2</td>
<td><code>.3.LEVEL2</code></td>
<td><code></code></td>
<td></td>
<td><code>.4.LEVEL2</code></td>
</tr>
<tr>
<td><code>activity</td>
<td><code>.3.ACTIVITY_STATE</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>stop</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code>.4.STOP</code></td>
</tr>
</tbody></table>

#### HM-LC-Bl1-FM

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>level</td>
<td><code>.1.LEVEL</code></td>
<td><code></code></td>
<td></td>
<td><code>.1.LEVEL</code></td>
</tr>
<tr>
<td><code>activity</td>
<td><code>.1.WORKING</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>stop</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code>.1.STOP</code></td>
</tr>
</tbody></table>

#### HM-LC-Bl1PBU-FM

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>level</td>
<td><code>.1.LEVEL</code></td>
<td><code></code></td>
<td></td>
<td><code>.1.LEVEL</code></td>
</tr>
<tr>
<td><code>activity</td>
<td><code>.1.WORKING</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>stop</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code>.1.STOP</code></td>
</tr>
</tbody></table>

#### HmIPW-DRBL4

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>levelCh1</td>
<td><code>.2.LEVEL</code></td>
<td><code></code></td>
<td></td>
<td><code>.2.LEVEL</code></td>
</tr>
<tr>
<td><code>level2Ch1</td>
<td><code>.2.LEVEL_2</code></td>
<td><code></code></td>
<td></td>
<td><code>.2.LEVEL_2</code></td>
</tr>
<tr>
<td><code>activityCh1</td>
<td><code>.2.PROCESS</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>stopCh1</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code>.2.STOP</code></td>
</tr>
<tr>
<td><code>levelCh2</td>
<td><code>.6.LEVEL</code></td>
<td><code></code></td>
<td></td>
<td><code>.6.LEVEL</code></td>
</tr>
<tr>
<td><code>level2Ch2</td>
<td><code>.6.LEVEL_2</code></td>
<td><code></code></td>
<td></td>
<td><code>.6.LEVEL_2</code></td>
</tr>
<tr>
<td><code>activityCh2</td>
<td><code>.6.PROCESS</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>stopCh2</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code>.6.STOP</code></td>
</tr>
<tr>
<td><code>levelCh3</td>
<td><code>.10.LEVEL</code></td>
<td><code></code></td>
<td></td>
<td><code>.10.LEVEL</code></td>
</tr>
<tr>
<td><code>level2Ch3</td>
<td><code>.10.LEVEL_2</code></td>
<td><code></code></td>
<td></td>
<td><code>.10.LEVEL_2</code></td>
</tr>
<tr>
<td><code>activityCh3</td>
<td><code>.10.PROCESS</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>stopCh3</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code>.10.STOP</code></td>
</tr>
<tr>
<td><code>levelCh4</td>
<td><code>.14.LEVEL</code></td>
<td><code></code></td>
<td></td>
<td><code>.14.LEVEL</code></td>
</tr>
<tr>
<td><code>level2Ch4</td>
<td><code>.14.LEVEL_2</code></td>
<td><code></code></td>
<td></td>
<td><code>.14.LEVEL_2</code></td>
</tr>
<tr>
<td><code>activityCh4</td>
<td><code>.14.PROCESS</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>stopCh4</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code>.14.STOP</code></td>
</tr>
</tbody></table>

### Adapter hmip


#### HmIP-BBL

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>level</td>
<td><code>.channels.1.shutterLevel</code></td>
<td><code></code></td>
<td></td>
<td><code>.channels.1.shutterLevel</code></td>
</tr>
<tr>
<td><code>activity</td>
<td><code>.channels.1.processing</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>stop</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code>.channels.1.stop</code></td>
</tr>
</tbody></table>

#### HmIP-BROLL

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>level</td>
<td><code>.channels.1.shutterLevel</code></td>
<td><code></code></td>
<td></td>
<td><code>.channels.1.shutterLevel</code></td>
</tr>
<tr>
<td><code>activity</td>
<td><code>.channels.1.processing</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>stop</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code>.channels.1.stop</code></td>
</tr>
</tbody></table>

### Adapter shelly

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>level</td>
<td><code>.Shutter.Position</code></td>
<td><code></code></td>
<td></td>
<td><code>.Shutter.Position</code></td>
</tr>
<tr>
<td><code>activity</td>
<td><code>.Shutter.state</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>stop</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code>.Shutter.Pause</code></td>
</tr>
</tbody></table>