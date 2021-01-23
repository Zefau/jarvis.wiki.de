
## Gewerk Sensor (`sensor`)

### vordefinierte Datenpunkte

<table><thead><tr><th>Datenpunkt Bezeichner</th><th>Datenpunkt Stil</th><th>Anzeige</th><th>Einheit</th><th>Icon</th><th>Icon Stil</th></tr></thead>
<tbody><tr><td><code>temperature</code></td><td>-</td><td>-</td><td><code>"&nbsp;°C"</code></td><td><code>"mdi-thermometer"</code></td><td>-</td></tr></tbody>
<tbody><tr><td><code>humidity</code></td><td>-</td><td>-</td><td><code>"&nbsp;%"</code></td><td>-</td><td>-</td></tr></tbody>
<tbody><tr><td><code>illumination</code></td><td>-</td><td>-</td><td><code>"&nbsp;lux"</code></td><td><code>"mdi-brightness-7"</code></td><td>-</td></tr></tbody>
<tbody><tr><td><code>pressure</code></td><td>-</td><td>-</td><td><code>"&nbsp;hPa"</code></td><td><code>"mdi-air-purifier"</code></td><td>-</td></tr></tbody>
</table>

<h3>Beispielkonfiguration


#### Adapter hm-rpc

<h5>HM-Sec-TiS</h5>
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
<td><code></code></td>
</tr>
</tbody></table>
<h5>HmIP-SLO</h5>
<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>illuminationAverage</td>
<td><code>.1.AVERAGE_ILLUMINATION</code></td>
<td><code> Lux</code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>illuminationCurrent</td>
<td><code>.1.CURRENT_ILLUMINATION</code></td>
<td><code> Lux</code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>illuminationHighest</td>
<td><code>.1.HIGHEST_ILLUMINATION</code></td>
<td><code> Lux</code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>illuminationLowest</td>
<td><code>.1.LOWEST_ILLUMINATION</code></td>
<td><code> Lux</code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>
<h5>HmIP-SWD</h5>
<table><thead><tr>
<th>State Key</th>
<th>State</th>
<th>Einheit</th>
<th>Anzeige</th>
<th>Action</th>
</thead><tbody>
<tr>
<td><code>alarm</td>
<td><code>.1.ALARMSTATE</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>alarmMoisture</td>
<td><code>.1.MOISTURE_DETECTED</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
<tr>
<td><code>alarmWaterlevel</td>
<td><code>.1.WATERLEVEL_DETECTED</code></td>
<td><code></code></td>
<td></td>
<td><code></code></td>
</tr>
</tbody></table>
<h5>HM-Sec-WDS-2</h5>
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