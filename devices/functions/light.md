
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


#### power

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>0</td>
<td><code>.lights.Switch</code></td>
<td><code></code></td>
<td></td>
<td><code>.lights.Switch</code></td>
</tr>
<tr>
<td><code>1</td>
<td><code>.white0.Switch</code></td>
<td><code></code></td>
<td></td>
<td><code>.white0.Switch</code></td>
</tr>
</tbody></table>

#### powerCh1

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>state</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>action</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>actionElement</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### powerCh2

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>state</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>action</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>actionElement</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### powerCh3

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>state</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>action</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>actionElement</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### colorTemperature

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>state</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>action</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>actionElement</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>properties</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### level

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>0</td>
<td><code>.lights.brightness</code></td>
<td><code></code></td>
<td></td>
<td><code>.lights.brightness</code></td>
</tr>
<tr>
<td><code>1</td>
<td><code>.white0.brightness</code></td>
<td><code></code></td>
<td></td>
<td><code>.white0.brightness</code></td>
</tr>
</tbody></table>

#### levelCh1

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>state</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>action</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### levelCh2

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>state</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>action</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### levelCh3

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>state</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>action</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### hex

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>state</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>action</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### hue

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>state</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>action</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### powerMeter

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>0</td>
<td><code>.Relay0.Power</code></td>
<td><code> W</code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>1</td>
<td><code>.lights.Power</code></td>
<td><code> W</code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>2</td>
<td><code>.white0.Power</code></td>
<td><code> W</code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>3</td>
<td><code>.Emeter0.Power</code></td>
<td><code> W</code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### powerMeterCh1

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>0</td>
<td><code>.Relay1.Power</code></td>
<td><code> W</code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>1</td>
<td><code>.white1.Power</code></td>
<td><code> W</code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>2</td>
<td><code>.Emeter1.Power</code></td>
<td><code> W</code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### powerMeterCh2

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>0</td>
<td><code>.Relay2.Power</code></td>
<td><code> W</code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>1</td>
<td><code>.white2.Power</code></td>
<td><code> W</code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>2</td>
<td><code>.Emeter2.Power</code></td>
<td><code> W</code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### powerMeterCh3

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>0</td>
<td><code>.Relay3.Power</code></td>
<td><code> W</code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>1</td>
<td><code>.white3.Power</code></td>
<td><code> W</code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### powerCounter

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>0</td>
<td><code>.Relay0.Energy</code></td>
<td><code> Wh</code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>1</td>
<td><code>.lights.Energy</code></td>
<td><code> Wh</code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>2</td>
<td><code>.white0.Energy</code></td>
<td><code> Wh</code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>3</td>
<td><code>.Emeter0.Total</code></td>
<td><code> Wh</code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### powerCounterCh1

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>0</td>
<td><code>.Relay1.Energy</code></td>
<td><code> Wh</code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>1</td>
<td><code>.white1.Energy</code></td>
<td><code> Wh</code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>2</td>
<td><code>.Emeter1.Total</code></td>
<td><code> Wh</code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### powerCounterCh2

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>0</td>
<td><code>.Relay2.Energy</code></td>
<td><code> Wh</code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>1</td>
<td><code>.white2.Energy</code></td>
<td><code> Wh</code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>2</td>
<td><code>.Emeter2.Total</code></td>
<td><code> Wh</code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### powerCounterCh3

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>0</td>
<td><code>.Relay3.Energy</code></td>
<td><code> Wh</code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>1</td>
<td><code>.white3.Energy</code></td>
<td><code> Wh</code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### powerCurrent

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>state</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>unit</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### powerCurrentCh1

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>state</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>unit</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### powerCurrentCh2

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>state</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>unit</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### powerVoltage

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>state</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>unit</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### powerVoltageCh1

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>state</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>unit</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### powerVoltageCh2

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>state</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>unit</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### powerCounterReturned

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>state</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>unit</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### powerCounterReturnedCh1

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>state</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>unit</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### powerCounterReturnedCh2

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>state</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>unit</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### powerTotalCurrent

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>state</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>unit</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### powerTotalConsumed

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>state</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>unit</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### powerTotalInstant

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>state</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>unit</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### powerTotalVoltage

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>state</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>unit</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### powerTotalVoltageMean

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>state</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>unit</td>
<td><code></code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>