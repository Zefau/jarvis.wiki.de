
# Gewerk Sensor (`sensor`)

## vordefinierte Datenpunkte

<table><thead><tr><th>Datenpunkt Bezeichner</th><th>Datenpunkt Stil</th><th>Anzeige</th><th>Einheit</th><th>Icon</th><th>Icon Stil</th></tr></thead>
<tbody><tr><td><code>temperature</code></td><td>-</td><td>-</td><td><code>&quot;&nbsp;°C&quot;</code></td><td><code>&quot;mdi-thermometer&quot;</code></td><td>-</td></tr></tbody>
<tbody><tr><td><code>humidity</code></td><td>-</td><td>-</td><td><code>&quot;&nbsp;%&quot;</code></td><td>-</td><td>-</td></tr></tbody>
<tbody><tr><td><code>illumination</code></td><td>-</td><td>-</td><td><code>&quot;&nbsp;lux&quot;</code></td><td><code>&quot;mdi-brightness-7&quot;</code></td><td>-</td></tr></tbody>
<tbody><tr><td><code>pressure</code></td><td>-</td><td>-</td><td><code>&quot;&nbsp;hPa&quot;</code></td><td><code>&quot;mdi-air-purifier&quot;</code></td><td>-</td></tr></tbody>
</table>

## Beispielkonfiguration


### Adapter hm-rpc


#### HM-Sec-TiS

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

#### HmIP-SLO

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

#### HmIP-SWD

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

#### HM-Sec-WDS-2

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