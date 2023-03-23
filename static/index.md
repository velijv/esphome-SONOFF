# [SONOFF NSPanel](https://sonoff.tech/product/central-control-panel/nspanel/) [ESPHome configuration by Veli](https://github.com/velijv/esphome-project-template)

> ## Looks like stock version, works even better! 

| <img alt="Sonoff" src="https://raw.githubusercontent.com/velijv/esphome-project-template/main/static/logos/sonoff.svg" height="100"> | <img alt="NSpanel" src="https://raw.githubusercontent.com/velijv/esphome-project-template/main/static/icons/nspanel86.svg" height="100"> | <img alt="Made for ESPHome" src="https://raw.githubusercontent.com/velijv/esphome-project-template/main/static/logos/made-for-esphome.svg" height="100"> | <img alt="NSpanel White" src="https://raw.githubusercontent.com/velijv/esphome-project-template/main/static/icons/nspanel86w.svg" height="100"> 
|------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------|


## 🔥 Features

<details open>
<summary><h3>✨ That make this project special</h3></summary>

> #### versatility, uniqueness

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



## Installation

> You can use the button below to install the pre-built firmware directly to your device via USB from the browser.

<esp-web-install-button manifest="./manifest.json"></esp-web-install-button>
<script type="module" src="https://unpkg.com/esp-web-tools@9.1.0/dist/web/install-button.js?module"></script>

*** 

## ✨ Demo 

<details open>
<summary>🔲 NSpanel</summary>

![Screenshot](https://raw.githubusercontent.com/velijv/esphome-project-template/main/static/screens/nspanel.jpeg)

</details>

<details>
<summary>🖥️ Home Assistant device page</summary>

![Home Assistant Device](https://raw.githubusercontent.com/velijv/esphome-project-template/main/static/screens/homeassistant-device.jpeg)

</details>

<details>
<summary><h3>🤜🏻 Attributions</h3></summary>

> ### Component author
> - [Create initial NSPanel component #2702](https://github.com/esphome/esphome/pull/2702) by @jesserockz
> 
> #### Some code gathered from / inspired by
> - https://community.home-assistant.io/t/sonoff-nspanel-by-itead-smart-scene-wall-switch-based-on-esp32-and-custom-nextion-touch-screen-panel-display-non-pro-variant/332962/356
> - https://github.com/sairon/esphome-nspanel-lovelace-ui
> - https://github.com/DeanoXX/esphome-config/blob/main/esp-nsp01.yaml
> - https://github.com/esphome/esphome/pull/2702
> - https://github.com/esphome/feature-requests/issues/1469
> - https://blakadder.github.io/nspanel/ 
> - https://gist.github.com/blakadder/7928279bd95ad47b54f705b7a121a7e1


</details>

***

ESPHome Projects by [Veli](https://veli.ee) - [Github](https://github.com/velijv)
