
## Gewerk Rauchmelder (`smoke`)

### vordefinierte Datenpunkte

<table><thead><tr><th>Datenpunkt Bezeichner</th><th>Datenpunkt Stil</th><th>Anzeige</th><th>Einheit</th><th>Icon</th><th>Icon Stil</th></tr></thead>
<tbody><tr><td><code>alarm</code></td><td>-</td><td>-</td><td>-</td><td><code>{<br />&nbsp;"0":&nbsp;"mdi-alarm-light-outline",<br />&nbsp;"1":&nbsp;"mdi-alarm-light",<br />&nbsp;"2":&nbsp;"mdi-alarm-light",<br />&nbsp;"3":&nbsp;"mdi-alarm-light",<br />&nbsp;"true":&nbsp;"mdi-alarm-light",<br />&nbsp;"false":&nbsp;"mdi-alarm-light-outline"<br />}</code></td><td>-</td></tr></tbody>
</table>

<h3>Beispielkonfiguration


#### Adapter hm-rpc

<h5>HmIP-SWSD</h5>
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
<td><code>{<br />&nbsp;"0":&nbsp;"IDLE_OFF",<br />&nbsp;"1":&nbsp;"PRIMARY_ALARM",<br />&nbsp;"2":&nbsp;"INTRUSION_ALARM",<br />&nbsp;"3":&nbsp;"SECONDARY_ALARM"<br />}</code></td>
<td><code></code></td>
</tr>
</tbody></table>
<h5>HM-Sec-SD</h5>
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
<h5>HM-Sec-SD-2</h5>
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
<h5>HM-Sec-SD-2-Team</h5>
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