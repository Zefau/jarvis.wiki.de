
# Gewerk Rauchmelder (`smoke`)

## vordefinierte Datenpunkte

<table><thead><tr><th>Datenpunkt Bezeichner</th><th>Datenpunkt Stil</th><th>Anzeige</th><th>Einheit</th><th>Icon</th><th>Icon Stil</th></tr></thead>
<tbody><tr><td><code>alarm</code></td><td>-</td><td>-</td><td>-</td><td><code>{<br />&nbsp;&quot;0&quot;:&nbsp;&quot;mdi-alarm-light-outline&quot;,<br />&nbsp;&quot;1&quot;:&nbsp;&quot;mdi-alarm-light&quot;,<br />&nbsp;&quot;2&quot;:&nbsp;&quot;mdi-alarm-light&quot;,<br />&nbsp;&quot;3&quot;:&nbsp;&quot;mdi-alarm-light&quot;,<br />&nbsp;&quot;true&quot;:&nbsp;&quot;mdi-alarm-light&quot;,<br />&nbsp;&quot;false&quot;:&nbsp;&quot;mdi-alarm-light-outline&quot;<br />}</code></td><td>-</td></tr></tbody>
</table>

## Beispielkonfiguration


### Adapter hm-rpc


#### HmIP-SWSD

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>alarm</td>
<td><code>.1.SMOKE_DETECTOR_ALARM_STATUS</code></td>
<td><code></code></td>
<td><code>{<br />&nbsp;&quot;0&quot;:&nbsp;&quot;IDLE_OFF&quot;,<br />&nbsp;&quot;1&quot;:&nbsp;&quot;PRIMARY_ALARM&quot;,<br />&nbsp;&quot;2&quot;:&nbsp;&quot;INTRUSION_ALARM&quot;,<br />&nbsp;&quot;3&quot;:&nbsp;&quot;SECONDARY_ALARM&quot;<br />}</code></td>
<td><code></code></td>
</tr>
</tbody></table>

#### HM-Sec-SD

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>alarm</td>
<td><code>.1.STATE</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>lowBatteryCh1</td>
<td><code>.1.LOWBAT</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### HM-Sec-SD-2

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>alarm</td>
<td><code>.1.STATE</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>lowBatteryCh1</td>
<td><code>.1.LOWBAT</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### HM-Sec-SD-2-Team

<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>alarm</td>
<td><code>.1.STATE</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>