
## Gewerk Fenster (`window`)

### vordefinierte Datenpunkte

<table><thead><tr><th>Datenpunkt Bezeichner</th><th>Datenpunkt Stil</th><th>Anzeige</th><th>Einheit</th><th>Icon</th><th>Icon Stil</th></tr></thead>
<tbody><tr><td><code>open</code></td><td>-</td><td><code>{<br />&nbsp;"0":&nbsp;"geschlossen",<br />&nbsp;"1":&nbsp;"offen",<br />&nbsp;"2":&nbsp;"offen",<br />&nbsp;"false":&nbsp;"geschlossen",<br />&nbsp;"true":&nbsp;"offen"<br />}</code></td><td>-</td><td><code>{<br />&nbsp;"0":&nbsp;"window-closed-variant",<br />&nbsp;"1":&nbsp;"window-open-variant",<br />&nbsp;"false":&nbsp;"window-closed-variant",<br />&nbsp;"true":&nbsp;"window-open-variant"<br />}</code></td><td>-</td></tr></tbody>
</table>

<h3>Beispielkonfiguration


#### Adapter hm-rpc

<h5>HmIP-SWDM</h5>
<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>open</td>
<td><code>.1.STATE</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>
<h5>HmIP-SWDO-I</h5>
<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>open</td>
<td><code>.1.STATE</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>
<h5>HmIP-SWDO</h5>
<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>open</td>
<td><code>.1.STATE</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>
<h5>HmIP-SRH</h5>
<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>open</td>
<td><code>.1.STATE</code></td>
<td><code></code></td>
<td><code>{<br />&nbsp;"0":&nbsp;"window#open#closed",<br />&nbsp;"1":&nbsp;"window#open#tilted",<br />&nbsp;"2":&nbsp;"window#open#opened"<br />}</code></td>
<td><code></code></td>
</tr>
</tbody></table>
<h5>HM-Sec-RHS</h5>
<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>open</td>
<td><code>.1.STATE</code></td>
<td><code></code></td>
<td><code>{<br />&nbsp;"0":&nbsp;"window#open#closed",<br />&nbsp;"1":&nbsp;"window#open#tilted",<br />&nbsp;"2":&nbsp;"window#open#opened"<br />}</code></td>
<td><code></code></td>
</tr>
</tbody></table>
<h5>HM-Sec-Sco</h5>
<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>open</td>
<td><code>.1.STATE</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>
<h5>HM-Sec-SC-2</h5>
<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>open</td>
<td><code>.1.STATE</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>

#### Adapter hmip

<h5>HmIP-SWDO</h5>
<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>open</td>
<td><code>.channels.1.windowOpen</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>
<h5>HmIP-SWDO-I</h5>
<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>open</td>
<td><code>.channels.1.windowOpen</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>
<h5>HmIP-SRH</h5>
<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>open</td>
<td><code>.channels.1.windowOpen</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>state</td>
<td><code>.channels.1.windowState</code></td>
<td><code></code></td>
<td><code>{<br />&nbsp;"CLOSED":&nbsp;"window#open#closed",<br />&nbsp;"TILTED":&nbsp;"window#open#tilted",<br />&nbsp;"OPEN":&nbsp;"window#open#opened"<br />}</code></td>
<td><code></code></td>
</tr>
</tbody></table>