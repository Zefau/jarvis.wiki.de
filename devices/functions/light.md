
# Gewerk Licht (`light`)

## vordefinierte Datenpunkte

<table><thead><tr><th>Datenpunkt Bezeichner</th><th>Datenpunkt Stil</th><th>Anzeige</th><th>Einheit</th><th>Icon</th><th>Icon Stil</th></tr></thead>
<tbody><tr><td><code>on</code></td><td>-</td><td>-</td><td>-</td><td><code>{<br />&nbsp;&quot;true&quot;:&nbsp;&quot;lightbulb-on&quot;,<br />&nbsp;&quot;false&quot;:&nbsp;&quot;lightbulb-off-outline&quot;<br />}</code></td><td>-</td></tr></tbody>
<tbody><tr><td><code>power</code></td><td>-</td><td>-</td><td>-</td><td><code>{<br />&nbsp;&quot;true&quot;:&nbsp;&quot;lightbulb-on&quot;,<br />&nbsp;&quot;false&quot;:&nbsp;&quot;lightbulb-off-outline&quot;<br />}</code></td><td>-</td></tr></tbody>
<tbody><tr><td><code>dimmer</code></td><td><code>{<br />&nbsp;&quot;0&quot;:&nbsp;{<br />&nbsp;&nbsp;&quot;color&quot;:&nbsp;&quot;#999&quot;<br />&nbsp;}<br />}</code></td><td><code>{<br />&nbsp;&quot;0&quot;:&nbsp;&quot;aus&quot;<br />}</code></td><td><code>&quot;val&nbsp;=&gt;&nbsp;val&nbsp;&gt;&nbsp;0&nbsp;?&nbsp;\&quot;&nbsp;%\&quot;&nbsp;:&nbsp;null&quot;</code></td><td><code>{<br />&nbsp;&quot;0&quot;:&nbsp;&quot;lightbulb-off-outline&quot;,<br />&nbsp;&quot;default&quot;:&nbsp;&quot;lightbulb-on&quot;<br />}</code></td><td>-</td></tr></tbody>
<tbody><tr><td><code>level</code></td><td><code>{<br />&nbsp;&quot;0&quot;:&nbsp;{<br />&nbsp;&nbsp;&quot;color&quot;:&nbsp;&quot;#999&quot;<br />&nbsp;}<br />}</code></td><td><code>{<br />&nbsp;&quot;0&quot;:&nbsp;&quot;aus&quot;<br />}</code></td><td><code>&quot;val&nbsp;=&gt;&nbsp;val&nbsp;&gt;&nbsp;0&nbsp;?&nbsp;\&quot;&nbsp;%\&quot;&nbsp;:&nbsp;null&quot;</code></td><td><code>{<br />&nbsp;&quot;0&quot;:&nbsp;&quot;lightbulb-off-outline&quot;,<br />&nbsp;&quot;default&quot;:&nbsp;&quot;lightbulb-on&quot;<br />}</code></td><td>-</td></tr></tbody>
<tbody><tr><td><code>ct</code></td><td>-</td><td>-</td><td><code>&quot;&nbsp;°K&quot;</code></td><td><code>{<br />&nbsp;&quot;default&quot;:&nbsp;&quot;thermometer&quot;<br />}</code></td><td>-</td></tr></tbody>
<tbody><tr><td><code>colortemperature</code></td><td>-</td><td>-</td><td><code>&quot;&nbsp;°K&quot;</code></td><td><code>{<br />&nbsp;&quot;default&quot;:&nbsp;&quot;thermometer&quot;<br />}</code></td><td>-</td></tr></tbody>
<tbody><tr><td><code>hue</code></td><td>-</td><td>-</td><td><code>&quot;&nbsp;°&quot;</code></td><td><code>{<br />&nbsp;&quot;default&quot;:&nbsp;&quot;palette&quot;<br />}</code></td><td>-</td></tr></tbody>
<tbody><tr><td><code>rgb</code></td><td>-</td><td>-</td><td>-</td><td><code>{<br />&nbsp;&quot;default&quot;:&nbsp;&quot;palette&quot;<br />}</code></td><td>-</td></tr></tbody>
<tbody><tr><td><code>hsv</code></td><td>-</td><td>-</td><td>-</td><td><code>{<br />&nbsp;&quot;default&quot;:&nbsp;&quot;palette&quot;<br />}</code></td><td>-</td></tr></tbody>
<tbody><tr><td><code>hex</code></td><td>-</td><td>-</td><td>-</td><td><code>{<br />&nbsp;&quot;default&quot;:&nbsp;&quot;palette&quot;<br />}</code></td><td>-</td></tr></tbody>
</table>

## Beispielkonfiguration


### Adapter hm-rpc


#### HmIP-BSM

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>power</td>
<td><code>.4.STATE</code></td>
<td><code></code></td>
<td></td>
<td><code>.4.STATE</code></td>
</tr>
<tr>
<td><code>powerMeter</td>
<td><code>.7.POWER</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>powerVoltage</td>
<td><code>.7.VOLTAGE</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>powerFrequency</td>
<td><code>.7.FREQUENCY</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### HmIP-BSL

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>power</td>
<td><code>.4.STATE</code></td>
<td><code></code></td>
<td></td>
<td><code>.4.STATE</code></td>
</tr>
<tr>
<td><code>levelTop</td>
<td><code>.8.LEVEL</code></td>
<td><code></code></td>
<td></td>
<td><code>.8.LEVEL</code></td>
</tr>
<tr>
<td><code>colorTop</td>
<td><code>.8.COLOR</code></td>
<td><code></code></td>
<td><code>{<br />&nbsp;&quot;0&quot;:&nbsp;&quot;BLACK&quot;,<br />&nbsp;&quot;1&quot;:&nbsp;&quot;BLUE&quot;,<br />&nbsp;&quot;2&quot;:&nbsp;&quot;GREEN&quot;,<br />&nbsp;&quot;3&quot;:&nbsp;&quot;TURQUOISE&quot;,<br />&nbsp;&quot;4&quot;:&nbsp;&quot;RED&quot;,<br />&nbsp;&quot;5&quot;:&nbsp;&quot;PURPLE&quot;,<br />&nbsp;&quot;6&quot;:&nbsp;&quot;YELLOW&quot;,<br />&nbsp;&quot;7&quot;:&nbsp;&quot;WHITE&quot;<br />}</code></td>
<td><code>.8.COLOR</code></td>
</tr>
<tr>
<td><code>levelBottom</td>
<td><code>.12.LEVEL</code></td>
<td><code></code></td>
<td></td>
<td><code>.12.LEVEL</code></td>
</tr>
<tr>
<td><code>colorBottom</td>
<td><code>.12.COLOR</code></td>
<td><code></code></td>
<td><code>{<br />&nbsp;&quot;0&quot;:&nbsp;&quot;BLACK&quot;,<br />&nbsp;&quot;1&quot;:&nbsp;&quot;BLUE&quot;,<br />&nbsp;&quot;2&quot;:&nbsp;&quot;GREEN&quot;,<br />&nbsp;&quot;3&quot;:&nbsp;&quot;TURQUOISE&quot;,<br />&nbsp;&quot;4&quot;:&nbsp;&quot;RED&quot;,<br />&nbsp;&quot;5&quot;:&nbsp;&quot;PURPLE&quot;,<br />&nbsp;&quot;6&quot;:&nbsp;&quot;YELLOW&quot;,<br />&nbsp;&quot;7&quot;:&nbsp;&quot;WHITE&quot;<br />}</code></td>
<td><code>.12.COLOR</code></td>
</tr>
</tbody></table>

#### HmIP-BRC2

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>power</td>
<td><code>.3.STATE</code></td>
<td><code></code></td>
<td></td>
<td><code>.4.STATE</code></td>
</tr>
</tbody></table>

#### HmIP-BDT

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
</tbody></table>

#### HM-LC-Dim1T-FM

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
<td><code>timerOff</td>
<td><code>.1.ON_TIME</code></td>
<td><code></code></td>
<td></td>
<td><code>.1.ON_TIME</code></td>
</tr>
<tr>
<td><code>timerOn</td>
<td><code>.1.RAMP_TIME</code></td>
<td><code></code></td>
<td></td>
<td><code>.1.RAMP_TIME</code></td>
</tr>
</tbody></table>

#### HM-LC-RGBW-WM

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
<td><code>timerOff</td>
<td><code>.1.ON_TIME</code></td>
<td><code></code></td>
<td></td>
<td><code>.1.ON_TIME</code></td>
</tr>
<tr>
<td><code>timerOn</td>
<td><code>.1.RAMP_TIME</code></td>
<td><code></code></td>
<td></td>
<td><code>.1.RAMP_TIME</code></td>
</tr>
<tr>
<td><code>hue</td>
<td><code>.2.COLOR</code></td>
<td><code></code></td>
<td></td>
<td><code>.2.COLOR</code></td>
</tr>
</tbody></table>

#### HM-LC-Sw1PBU-FM

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>power</td>
<td><code>.1.STATE</code></td>
<td><code></code></td>
<td></td>
<td><code>.1.STATE</code></td>
</tr>
</tbody></table>

#### HM-LC-Sw1-FM

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>power</td>
<td><code>.1.STATE</code></td>
<td><code></code></td>
<td></td>
<td><code>.1.STATE</code></td>
</tr>
<tr>
<td><code>timerOff</td>
<td><code>.1.ON_TIME</code></td>
<td><code></code></td>
<td></td>
<td><code>.1.ON_TIME</code></td>
</tr>
<tr>
<td><code>activity</td>
<td><code>.1.WORKING</code></td>
<td><code></code></td>
<td></td>
<td><code>.1.WORKING</code></td>
</tr>
</tbody></table>

#### HM-LC-Sw1-DR

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>power</td>
<td><code>.1.STATE</code></td>
<td><code></code></td>
<td></td>
<td><code>.1.STATE</code></td>
</tr>
<tr>
<td><code>timerOff</td>
<td><code>.1.ON_TIME</code></td>
<td><code></code></td>
<td></td>
<td><code>.1.ON_TIME</code></td>
</tr>
</tbody></table>

#### HM-LC-Sw2-FM

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>power</td>
<td><code>.1.STATE</code></td>
<td><code></code></td>
<td></td>
<td><code>.1.STATE</code></td>
</tr>
<tr>
<td><code>timerOff</td>
<td><code>.1.ON_TIME</code></td>
<td><code></code></td>
<td></td>
<td><code>.1.ON_TIME</code></td>
</tr>
<tr>
<td><code>powerCh2</td>
<td><code>.2.STATE</code></td>
<td><code></code></td>
<td></td>
<td><code>.2.STATE</code></td>
</tr>
<tr>
<td><code>timerOffCh2</td>
<td><code>.2.ON_TIME</code></td>
<td><code></code></td>
<td></td>
<td><code>.2.ON_TIME</code></td>
</tr>
</tbody></table>

#### HM-LC-Sw4-DR

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>power</td>
<td><code>.1.STATE</code></td>
<td><code></code></td>
<td></td>
<td><code>.1.STATE</code></td>
</tr>
<tr>
<td><code>timerOff</td>
<td><code>.1.ON_TIME</code></td>
<td><code></code></td>
<td></td>
<td><code>.1.ON_TIME</code></td>
</tr>
<tr>
<td><code>powerCh2</td>
<td><code>.2.STATE</code></td>
<td><code></code></td>
<td></td>
<td><code>.2.STATE</code></td>
</tr>
<tr>
<td><code>timerOffCh2</td>
<td><code>.2.ON_TIME</code></td>
<td><code></code></td>
<td></td>
<td><code>.2.ON_TIME</code></td>
</tr>
<tr>
<td><code>powerCh3</td>
<td><code>.3.STATE</code></td>
<td><code></code></td>
<td></td>
<td><code>.3.STATE</code></td>
</tr>
<tr>
<td><code>timerOffCh3</td>
<td><code>.3.ON_TIME</code></td>
<td><code></code></td>
<td></td>
<td><code>.3.ON_TIME</code></td>
</tr>
<tr>
<td><code>powerCh4</td>
<td><code>.4.STATE</code></td>
<td><code></code></td>
<td></td>
<td><code>.4.STATE</code></td>
</tr>
<tr>
<td><code>timerOffCh4</td>
<td><code>.4.ON_TIME</code></td>
<td><code></code></td>
<td></td>
<td><code>.4.ON_TIME</code></td>
</tr>
</tbody></table>

#### HM-LC-Dim1TPBU-FM

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
</tbody></table>

#### HM-LC-Dim1T-Pl-3

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
<td><code>timerOff</td>
<td><code>.1.ON_TIME</code></td>
<td><code></code></td>
<td></td>
<td><code>.1.ON_TIME</code></td>
</tr>
<tr>
<td><code>timerOn</td>
<td><code>.1.RAMP_TIME</code></td>
<td><code></code></td>
<td></td>
<td><code>.1.RAMP_TIME</code></td>
</tr>
</tbody></table>

### Adapter hue-extended

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>power</td>
<td><code>.action.on</code></td>
<td><code></code></td>
<td></td>
<td><code>.action.on</code></td>
</tr>
<tr>
<td><code>level</td>
<td><code>.action.level</code></td>
<td><code></code></td>
<td></td>
<td><code>.action.level</code></td>
</tr>
<tr>
<td><code>colorTemperature</td>
<td><code>.action.colorTemperature</code></td>
<td><code></code></td>
<td></td>
<td><code>.action.colorTemperature</code></td>
</tr>
<tr>
<td><code>hue</td>
<td><code>.action.hue</code></td>
<td><code></code></td>
<td></td>
<td><code>.action.hue</code></td>
</tr>
<tr>
<td><code>hex</td>
<td><code>.action.hex</code></td>
<td><code></code></td>
<td></td>
<td><code>.action.hex</code></td>
</tr>
</tbody></table>

### Adapter hue

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>power</td>
<td><code>.on</code></td>
<td><code></code></td>
<td></td>
<td><code>.on</code></td>
</tr>
<tr>
<td><code>level</td>
<td><code>.level</code></td>
<td><code></code></td>
<td></td>
<td><code>.level</code></td>
</tr>
<tr>
<td><code>colorTemperature</td>
<td><code>.ct</code></td>
<td><code></code></td>
<td></td>
<td><code>.ct</code></td>
</tr>
<tr>
<td><code>hue</td>
<td><code>.hue</code></td>
<td><code></code></td>
<td></td>
<td><code>.hue</code></td>
</tr>
<tr>
<td><code>reachability</td>
<td><code>.reachable</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

### Adapter mqtt

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>dimmer</td>
<td><code>.Dimmer</code></td>
<td><code></code></td>
<td></td>
<td><code>.Dimmer</code></td>
</tr>
<tr>
<td><code>ct</td>
<td><code>.CT</code></td>
<td><code></code></td>
<td></td>
<td><code>.CT</code></td>
</tr>
<tr>
<td><code>hue</td>
<td><code>.Hue</code></td>
<td><code></code></td>
<td></td>
<td><code>.Hue</code></td>
</tr>
<tr>
<td><code>sat</td>
<td><code>.Saturation</code></td>
<td><code></code></td>
<td></td>
<td><code>.Saturation</code></td>
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
<td><code>power</td>
<td><code>.lights.Switch</code></td>
<td><code></code></td>
<td></td>
<td><code>.lights.Switch</code></td>
</tr>
<tr>
<td><code>level</td>
<td><code>.lights.brightness</code></td>
<td><code></code></td>
<td></td>
<td><code>.lights.brightness</code></td>
</tr>
</tbody></table>