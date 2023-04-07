<h1><a href="https://sonoff.tech/product/central-control-panel/nspanel/">SONOFF NSPanel</a> <a href="https://esphome.io/">ESPHome</a> <a href="https://github.com/velijv/esphome-project-template">configuration</a> by <a href="https://veli.ee/">Veli</a></h1>

<blockquote>Looks like stock, works locally and has more controls!</blockquote>

<table>
	<tr>
		<td>
			<img alt="Sonoff" src="https://raw.githubusercontent.com/velijv/esphome-project-template/main/static/logos/sonoff.svg" height="100">
		</td>
		<td><img alt="NSpanel" src="https://raw.githubusercontent.com/velijv/esphome-project-template/main/static/icons/nspanel86.svg" height="100">
		</td>
		<td><img alt="Made for ESPHome" src="https://raw.githubusercontent.com/velijv/esphome-project-template/main/static/logos/made-for-esphome.svg" height="100">
		</td>
		<td><img alt="NSpanel White" src="https://raw.githubusercontent.com/velijv/esphome-project-template/main/static/icons/nspanel86w.svg" height="100"> 
		</td>
	</tr>
</table>

<h2> 🔥 Features </h2>

<details open>
<summary><b>✨ That make this project special</b></summary>

<blockquote><h4>versatility, uniqueness</h4></blockquote>

- use **stock** UI (HMI/TFT)
	- 🌧️ get weather information from Home Assistant
	- 💦 show Humidity (RHI%) on screen
	- 🔥 toggle between weather and ❄️ thermostat screensaver
	- 📟 enter **Factory Test Mode** (for fun)
- API:
	- control screen with  `send_json_command `
	- send beeps with  `rtttl.play`
	- send `weather_data`
- Control relays
	- Control relay indicators (on screen) independently of relays 
</details>



<h2> Installation </h2>

<blockquote> You can use the button below to install the pre-built firmware directly to your device via USB from the browser. </blockquote>

<esp-web-install-button manifest="./manifest.json"></esp-web-install-button>
<script type="module" src="https://unpkg.com/esp-web-tools@9.1.0/dist/web/install-button.js?module"></script>

<hr>

<h2>✨ Demo</h2>

<details open>
<summary>🔲 NSpanel</summary>
<img src="https://raw.githubusercontent.com/velijv/esphome-project-template/main/static/screens/nspanel.jpeg" alt="Screenshot">
</details>

<details open>
<summary>🖥️ Home Assistant device page</summary>
<img src="https://raw.githubusercontent.com/velijv/esphome-project-template/main/static/screens/homeassistant-device.jpeg" alt="Home Assistant Device">
</details>

<details>
<summary><h3>🤜🏻 Attributions</h3></summary>

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
