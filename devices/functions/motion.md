
# Gewerk Bewegungs-/Präsenzmelder (`motion`)

## vordefinierte Datenpunkte

<table><thead><tr><th>Datenpunkt Bezeichner</th><th>Datenpunkt Stil</th><th>Anzeige</th><th>Einheit</th><th>Icon</th><th>Icon Stil</th></tr></thead>
<tbody><tr><td><code>motion</code></td><td>-</td><td>-</td><td>-</td><td><code>{<br />&nbsp;&quot;true&quot;:&nbsp;&quot;motion-sensor&quot;,<br />&nbsp;&quot;false&quot;:&nbsp;&quot;motion-sensor-off&quot;<br />}</code></td><td>-</td></tr></tbody>
<tbody><tr><td><code>presence</code></td><td>-</td><td>-</td><td>-</td><td><code>{<br />&nbsp;&quot;true&quot;:&nbsp;&quot;motion-sensor&quot;,<br />&nbsp;&quot;false&quot;:&nbsp;&quot;motion-sensor-off&quot;<br />}</code></td><td>-</td></tr></tbody>
</table>

## Beispielkonfiguration


### Adapter hm-rpc


#### HmIP-SMI55

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>motion</td>
<td><code>.3.MOTION</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>brightness</td>
<td><code>.3.BRIGHTNESS</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### HmIP-SMI

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>motion</td>
<td><code>.1.MOTION</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>illumination</td>
<td><code>.1.ILLUMINATION</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### HmIP-SMO-A

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>motion</td>
<td><code>.1.MOTION</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>illumination</td>
<td><code>.1.ILLUMINATION</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### HmIP-SAM

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>motion</td>
<td><code>.1.MOTION</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>illumination</td>
<td><code>.1.ILLUMINATION</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### HmIP-SPI

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>presence</td>
<td><code>.1.PRESENCE_DETECTION_STATE</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>illumination</td>
<td><code>.1.ILLUMINATION</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### HM-PB-6-WM55

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>PRESS_LONG1</td>
<td><code>.1.PRESS_LONG</code></td>
<td><code></code></td>
<td></td>
<td><code>.1.PRESS_LONG</code></td>
</tr>
<tr>
<td><code>PRESS_SHORT1</td>
<td><code>.1.PRESS_SHORT</code></td>
<td><code></code></td>
<td></td>
<td><code>.1.PRESS_SHORT</code></td>
</tr>
<tr>
<td><code>PRESS_LONG2</td>
<td><code>.2.PRESS_LONG</code></td>
<td><code></code></td>
<td></td>
<td><code>.2.PRESS_LONG</code></td>
</tr>
<tr>
<td><code>PRESS_SHORT2</td>
<td><code>.2.PRESS_SHORT</code></td>
<td><code></code></td>
<td></td>
<td><code>.2.PRESS_SHORT</code></td>
</tr>
<tr>
<td><code>PRESS_LONG3</td>
<td><code>.3.PRESS_LONG</code></td>
<td><code></code></td>
<td></td>
<td><code>.3.PRESS_LONG</code></td>
</tr>
<tr>
<td><code>PRESS_SHORT3</td>
<td><code>.3.PRESS_SHORT</code></td>
<td><code></code></td>
<td></td>
<td><code>.3.PRESS_SHORT</code></td>
</tr>
<tr>
<td><code>PRESS_LONG4</td>
<td><code>.4.PRESS_LONG</code></td>
<td><code></code></td>
<td></td>
<td><code>.4.PRESS_LONG</code></td>
</tr>
<tr>
<td><code>PRESS_SHORT4</td>
<td><code>.4.PRESS_SHORT</code></td>
<td><code></code></td>
<td></td>
<td><code>.4.PRESS_SHORT</code></td>
</tr>
<tr>
<td><code>PRESS_LONG5</td>
<td><code>.5.PRESS_LONG</code></td>
<td><code></code></td>
<td></td>
<td><code>.5.PRESS_LONG</code></td>
</tr>
<tr>
<td><code>PRESS_SHORT5</td>
<td><code>.5.PRESS_SHORT</code></td>
<td><code></code></td>
<td></td>
<td><code>.5.PRESS_SHORT</code></td>
</tr>
<tr>
<td><code>PRESS_LONG6</td>
<td><code>.6.PRESS_LONG</code></td>
<td><code></code></td>
<td></td>
<td><code>.6.PRESS_LONG</code></td>
</tr>
<tr>
<td><code>PRESS_SHORT6</td>
<td><code>.6.PRESS_SHORT</code></td>
<td><code></code></td>
<td></td>
<td><code>.6.PRESS_SHORT</code></td>
</tr>
</tbody></table>

#### HM-Sen-MDIR-WM55

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>PRESS_LONG_BOTTOM</td>
<td><code>.1.PRESS_LONG</code></td>
<td><code></code></td>
<td></td>
<td><code>.1.PRESS_LONG</code></td>
</tr>
<tr>
<td><code>PRESS_SHORT_BOTTOM</td>
<td><code>.1.PRESS_SHORT</code></td>
<td><code></code></td>
<td></td>
<td><code>.1.PRESS_SHORT</code></td>
</tr>
<tr>
<td><code>PRESS_LONG_TOP</td>
<td><code>.2.PRESS_LONG</code></td>
<td><code></code></td>
<td></td>
<td><code>.2.PRESS_LONG</code></td>
</tr>
<tr>
<td><code>PRESS_SHORT_TOP</td>
<td><code>.2.PRESS_SHORT</code></td>
<td><code></code></td>
<td></td>
<td><code>.2.PRESS_SHORT</code></td>
</tr>
<tr>
<td><code>motion</td>
<td><code>.3.MOTION</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>illumination</td>
<td><code>.3.ILLUMINATION</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### HM-Sen-MDIR-O-2

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>motion</td>
<td><code>.1.MOTION</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>brightness</td>
<td><code>.1.BRIGHTNESS</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### HM-Sen-MDIR-O-3

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>motion</td>
<td><code>.1.MOTION</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>brightness</td>
<td><code>.1.BRIGHTNESS</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

### Adapter hmip


#### HmIP-SMI

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>motion</td>
<td><code>.channels.1.motionDetected</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>illumination</td>
<td><code>.channels.1.illumination</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>