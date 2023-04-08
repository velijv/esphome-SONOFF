<h1>
	<a href="https://sonoff.tech/product/smart-wall-switches/m5/">SONOFF SwitchMan-M5 (1C, 2C, 3C)</a>
	<a href="https://github.com/velijv/esphome-configs">ESPHome configuration</a></a>
</h1>

<h1>
	<a href="https://sonoff.tech/product/central-control-panel/nspanel/">SONOFF NSPanel</a>
	<a href="https://esphome.io/">ESPHome</a>
	<a href="https://github.com/velijv/esphome-configs">configuration</a></a>
</h1>

<blockquote>Looks like stock, works locally and has more controls!</blockquote>

<table>
	<tr>
		<td>
			<img alt="NSpanel White" src="https://raw.githubusercontent.com/velijv/esphome-configs/main/static/icons/nspanel86w.svg" height="100">
		</td>
		<td>
			<img alt="Sonoff" src="https://raw.githubusercontent.com/velijv/esphome-configs/main/static/logos/sonoff.svg" height="100">
		</td>
		<td>
			<img alt="NSpanel" src="https://raw.githubusercontent.com/velijv/esphome-configs/main/static/icons/nspanel86.svg" height="100">
		</td>
		<td>
			<img alt="M5-1C-86" src="https://raw.githubusercontent.com/velijv/esphome-configs/main/static/icons/m5-1c-86.svg" height="100">
		</td>
		<td>
			<img alt="M5-2C-86" src="https://raw.githubusercontent.com/velijv/esphome-configs/main/static/icons/m5-2c-86.svg" height="100">
		</td>
		<td>
			<img alt="M5-3C-86" src="https://raw.githubusercontent.com/velijv/esphome-configs/main/static/icons/m5-3c-86.svg" height="100">
		</td>
		<td>
			<img alt="Made for ESPHome" src="https://raw.githubusercontent.com/velijv/esphome-configs/main/static/logos/made-for-esphome.svg" height="100">
		</td>
	</tr>
</table>


<h2> 🔥 Features </h2>

<details open>
<summary><b>✨ That make this project special</b></summary>

<blockquote>versatility, uniqueness</blockquote>

<ul>
<li> use <b>stock</b> UI (HMI/TFT)
	<ul>
		<li>🌧️ get weather information from Home Assistant</li>
		<li>💦 show Humidity (RHI%) on screen</li>
		<li>🔥 toggle between weather and ❄️ thermostat screensaver</li>
		<li>📟 enter **Factory Test Mode** (for fun)</li>
	</ul>
</li>
<li>API
	<ul>	
		<li>control screen with <code>send_json_command</code></li>
		<li>send beeps with <code>rtttl.play</code></li>
		<li>send <code>weather_data</code></li>
	</ul>
</li>
<li>Control relays
	<ul>
		<li>Control relay indicators (on screen) independently of relays</li>
	</ul>
</li>
</ul>
</details>

<h2> Installation </h2>

<blockquote> You can use the button below to install the pre-built firmware directly to your device via USB from the browser. </blockquote>

<esp-web-install-button manifest="./manifest.json"></esp-web-install-button>
<script type="module" src="https://unpkg.com/esp-web-tools@9.1.0/dist/web/install-button.js?module"></script>

<hr>

<h2>✨ Demo</h2>

<details open>
<summary><b>🔲 NSpanel</b></summary>
<img src="https://raw.githubusercontent.com/velijv/esphome-configs/main/static/screens/nspanel.jpeg" alt="Screenshot">
</details>

<details open>
<summary><b>🖥️ Home Assistant device page</b></summary>
<img src="https://raw.githubusercontent.com/velijv/esphome-configs/main/static/screens/homeassistant-device.jpeg" alt="Home Assistant Device">
</details>

<details>
<summary><b>🤜🏻 Attributions</b></summary>

<ul>
	<li><h4> Component author:</h4> <a href="https://github.com/esphome/esphome/pull/2702">Create initial NSPanel component #2702</a> by @jesserockz</li>
	<li><h4>Some code gathered from / inspired by</h4></li>
	<li>https://community.home-assistant.io/t/</li>sonoff-nspanel-by-itead-smart-scene-wall-switch-based-on-esp32-and-custom-nextion-touch-screen-panel-display-non-pro-variant/332962/356</li>
	<li>https://github.com/sairon/esphome-nspanel-lovelace-ui</li>
	<li>https://github.com/DeanoXX/esphome-config/blob/main/esp-nsp01.yaml</li>
	<li>https://github.com/esphome/esphome/pull/2702</li>
	<li>https://github.com/esphome/feature-requests/issues/1469</li>
	<li>https://blakadder.github.io/nspanel/ </li>
	<li>https://gist.github.com/blakadder/7928279bd95ad47b54f705b7a121a7e1</li>
</ul>

</details>

<hr>

ESPHome Projects by [Veli](https://veli.ee) - [Github](https://github.com/velijv)
