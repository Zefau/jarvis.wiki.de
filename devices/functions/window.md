
# Gewerk Fenster (`window`)

## vordefinierte Datenpunkte

<table><thead><tr><th>Datenpunkt Bezeichner</th><th>Datenpunkt Stil</th><th>Anzeige</th><th>Einheit</th><th>Icon</th><th>Icon Stil</th></tr></thead>
<tbody><tr><td><code>open</code></td><td>-</td><td><code>{<br />&nbsp;&quot;0&quot;:&nbsp;&quot;geschlossen&quot;,<br />&nbsp;&quot;1&quot;:&nbsp;&quot;offen&quot;,<br />&nbsp;&quot;2&quot;:&nbsp;&quot;offen&quot;,<br />&nbsp;&quot;false&quot;:&nbsp;&quot;geschlossen&quot;,<br />&nbsp;&quot;true&quot;:&nbsp;&quot;offen&quot;<br />}</code></td><td>-</td><td><code>{<br />&nbsp;&quot;0&quot;:&nbsp;&quot;window-closed-variant&quot;,<br />&nbsp;&quot;1&quot;:&nbsp;&quot;window-open-variant&quot;,<br />&nbsp;&quot;false&quot;:&nbsp;&quot;window-closed-variant&quot;,<br />&nbsp;&quot;true&quot;:&nbsp;&quot;window-open-variant&quot;<br />}</code></td><td>-</td></tr></tbody>
</table>

## Beispielkonfiguration


### Adapter hm-rpc


#### HmIP-SWDM

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

#### HmIP-SWDO-I

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

#### HmIP-SWDO-PL

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

#### HmIP-SWDO

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

#### HmIP-SRH

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
<td><code>{<br />&nbsp;&quot;0&quot;:&nbsp;&quot;window#open#closed&quot;,<br />&nbsp;&quot;1&quot;:&nbsp;&quot;window#open#tilted&quot;,<br />&nbsp;&quot;2&quot;:&nbsp;&quot;window#open#opened&quot;<br />}</code></td>
<td><code></code></td>
</tr>
</tbody></table>

#### HM-Sec-RHS

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
<td><code>{<br />&nbsp;&quot;0&quot;:&nbsp;&quot;window#open#closed&quot;,<br />&nbsp;&quot;1&quot;:&nbsp;&quot;window#open#tilted&quot;,<br />&nbsp;&quot;2&quot;:&nbsp;&quot;window#open#opened&quot;<br />}</code></td>
<td><code></code></td>
</tr>
</tbody></table>

#### HM-Sec-Sco

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

#### HM-Sec-SC-2

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

### Adapter hmip


#### HmIP-SWDO

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

#### HmIP-SWDO-I

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

#### HmIP-SRH

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
<td><code>{<br />&nbsp;&quot;CLOSED&quot;:&nbsp;&quot;window#open#closed&quot;,<br />&nbsp;&quot;TILTED&quot;:&nbsp;&quot;window#open#tilted&quot;,<br />&nbsp;&quot;OPEN&quot;:&nbsp;&quot;window#open#opened&quot;<br />}</code></td>
<td><code></code></td>
</tr>
</tbody></table>