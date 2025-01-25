<h1 align="center">HomeAssistant config</h1>


<p align="center">
  This is a project focused on sharing ideas and solutions for the use of <a href="https://www.home-assistant.io/">Home Assistant</a> and home automation in general.
</p>

<p align="center">
  <img alt="Stars" src="https://img.shields.io/github/stars/JoaquinBeceiro/Home-Assistant-Config.svg?style=plasticr"/>
  <img alt="Last Commit" src="https://img.shields.io/github/last-commit/JoaquinBeceiro/Home-Assistant-Config.svg?style=plasticr"/>
  <img alt="Commit activity" src="https://img.shields.io/github/commit-activity/m/JoaquinBeceiro/home-assistant-config"/>
  <img alt="Maintenance" src="https://img.shields.io/maintenance/yes/2021"/>
</p>

<p align="center">
  <img alt="HA Version" src="https://img.shields.io/badge/HA--Version-2021.3.2-9cf"/>
  <img alt="Mosquitto Version" src="https://img.shields.io/badge/Mosquitto--Version-1.6.9-9cf"/>
  <img alt="VSCode Version" src="https://img.shields.io/badge/VSCode--Version-3.0.2-9cf"/>
  <img alt="MariaDB Version" src="https://img.shields.io/badge/MariaDB--Version-10.4-9cf"/>
</p>

## Table of Contents

- [Screenshots](#screenshots)
- [Software](#software)
- [Integrations](#integrations)
- [Lovelace Cards](#lovelace-cards)
- [Addons](#addons)
- [Devices](#devices)
- [Automations](#automations)
- [Secrets](#secrets)
- [ToDo list](#todo-list)
- [Authors](#authors)

## Screenshots

### Dashboard Home

![Dashboard personal](images/screenshots/personal-dashboard.png)

- Device tracker
- Phone status (location)

## Software

- [HomeAssistant](https://www.home-assistant.io/) MQTT server to communicate with devices
- [MariaDB](https://mariadb.org/) database to save all information
- [VSCode](https://code.visualstudio.com/) server to code in browser

## Integrations

<details>
  <summary>Show full list</summary>
  
<br>

- [rpi_power](https://www.home-assistant.io/integrations/rpi_power/)
- [google_translate](https://www.home-assistant.io/integrations/google_translate/)
- [HACS](https://www.home-assistant.io/integrations/hacs/)
- [local_calendar](https://www.home-assistant.io/integrations/local_calendar/)
- [mobile_app](https://www.home-assistant.io/integrations/mobile_app/)
- [cast](https://www.home-assistant.io/integrations/cast/)
- [cloud](https://www.home-assistant.io/integrations/cloud/)
- [webostv](https://www.home-assistant.io/integrations/webostv/)
- [tessie](https://www.home-assistant.io/integrations/tessie/)
- [samsungtv](https://www.home-assistant.io/integrations/samsungtv/)
- [dlna_dmr](https://www.home-assistant.io/integrations/dlna_dmr/)
- [mqtt](https://www.home-assistant.io/integrations/mqtt/)
- [zha](https://www.home-assistant.io/integrations/zha/)
- [local_todo](https://www.home-assistant.io/integrations/local_todo/)
- [template](https://www.home-assistant.io/integrations/template/)
- [shopping_list](https://www.home-assistant.io/integrations/shopping_list/)
- [scheduler](https://www.home-assistant.io/integrations/scheduler/)
- [systemmonitor](https://www.home-assistant.io/integrations/systemmonitor/)
- [octopus_energy](https://www.home-assistant.io/integrations/octopus_energy/)
- [spook](https://www.home-assistant.io/integrations/spook/)
- [ibeacon](https://www.home-assistant.io/integrations/ibeacon/)
- [openai_conversation](https://www.home-assistant.io/integrations/openai_conversation/)
- [go2rtc](https://www.home-assistant.io/integrations/go2rtc/)
- [chore_helper](https://www.home-assistant.io/integrations/chore_helper/)
- [pantry_tracker](https://www.home-assistant.io/integrations/pantry_tracker/)
- [music_assistant](https://www.home-assistant.io/integrations/music_assistant/)
- [asusrouter](https://www.home-assistant.io/integrations/asusrouter/)
- [ping](https://www.home-assistant.io/integrations/ping/)
- [unraid](https://www.home-assistant.io/integrations/unraid/)
- [google_generative_ai_conversation](https://www.home-assistant.io/integrations/google_generative_ai_conversation/)


</details>

## Lovelace Cards

<details>
  <summary>Show full list</summary>
  
<br>

- [anchor-card](https://github.com/ShadowAya/anchor-card)
- [android-tv-card](https://github.com/ShadowAya/android-tv-card)
- [apexcharts-card](https://github.com/ShadowAya/apexcharts-card)
- [atomic-calendar-revive](https://github.com/ShadowAya/atomic-calendar-revive)
- [bar-card](https://github.com/ShadowAya/bar-card)
- [better-thermostat-ui-card](https://github.com/ShadowAya/better-thermostat-ui-card)
- [bootstrap-grid-card](https://github.com/ShadowAya/bootstrap-grid-card)
- [Bubble-Card](https://github.com/ShadowAya/Bubble-Card)
- [button-card](https://github.com/ShadowAya/button-card)
- [channel-pad](https://github.com/ShadowAya/channel-pad)
- [charger-card](https://github.com/ShadowAya/charger-card)
- [clock-weather-card](https://github.com/ShadowAya/clock-weather-card)
- [config-template-card](https://github.com/ShadowAya/config-template-card)
- [css-swipe-card](https://github.com/ShadowAya/css-swipe-card)
- [custom-brand-icons](https://github.com/ShadowAya/custom-brand-icons)
- [custom-icons](https://github.com/ShadowAya/custom-icons)
- [custom-more-info](https://github.com/ShadowAya/custom-more-info)
- [decluttering-card](https://github.com/ShadowAya/decluttering-card)
- [energy-gauge-bundle-card](https://github.com/ShadowAya/energy-gauge-bundle-card)
- [hass-room-card](https://github.com/ShadowAya/hass-room-card)
- [honeycomb-menu](https://github.com/ShadowAya/honeycomb-menu)
- [kiosk-mode](https://github.com/ShadowAya/kiosk-mode)
- [LG-WebOS-Remote-Control](https://github.com/ShadowAya/LG-WebOS-Remote-Control)
- [light-entity-card](https://github.com/ShadowAya/light-entity-card)
- [lovelace-auto-entities](https://github.com/ShadowAya/lovelace-auto-entities)
- [lovelace-card-mod](https://github.com/ShadowAya/lovelace-card-mod)
- [lovelace-collapsable-cards](https://github.com/ShadowAya/lovelace-collapsable-cards)
- [lovelace-expander-card](https://github.com/ShadowAya/lovelace-expander-card)
- [lovelace-fold-entity-row](https://github.com/ShadowAya/lovelace-fold-entity-row)
- [lovelace-horizon-card](https://github.com/ShadowAya/lovelace-horizon-card)
- [lovelace-layout-card](https://github.com/ShadowAya/lovelace-layout-card)
- [lovelace-mushroom](https://github.com/ShadowAya/lovelace-mushroom)
- [lovelace-paper-buttons-row](https://github.com/ShadowAya/lovelace-paper-buttons-row)
- [lovelace-plotly-graph-card](https://github.com/ShadowAya/lovelace-plotly-graph-card)
- [lovelace-slider-entity-row](https://github.com/ShadowAya/lovelace-slider-entity-row)
- [lovelace-template-entity-row](https://github.com/ShadowAya/lovelace-template-entity-row)
- [lovelace-time-picker-card](https://github.com/ShadowAya/lovelace-time-picker-card)
- [mini-graph-card](https://github.com/ShadowAya/mini-graph-card)
- [mini-media-player](https://github.com/ShadowAya/mini-media-player)
- [octopus-energy-rates-card](https://github.com/ShadowAya/octopus-energy-rates-card)
- [pantry_tracker_card](https://github.com/ShadowAya/pantry_tracker_card)
- [scheduler-card](https://github.com/ShadowAya/scheduler-card)
- [sidebar-card](https://github.com/ShadowAya/sidebar-card)
- [simple-weather-card](https://github.com/ShadowAya/simple-weather-card)
- [stack-in-card](https://github.com/ShadowAya/stack-in-card)
- [surveillance-card](https://github.com/ShadowAya/surveillance-card)
- [swipe-card](https://github.com/ShadowAya/swipe-card)
- [swiper-slider](https://github.com/ShadowAya/swiper-slider)
- [tv-card](https://github.com/ShadowAya/tv-card)
- [Ultra-Vehicle-Card](https://github.com/ShadowAya/Ultra-Vehicle-Card)
- [uptime-card](https://github.com/ShadowAya/uptime-card)
- [vertical-stack-in-card](https://github.com/ShadowAya/vertical-stack-in-card)
- [weather-card](https://github.com/ShadowAya/weather-card)

</details>


## Addons

<details>
  <summary>Show full list</summary>
  
<br>

- [Advanced SSH & Web Terminal](https://github.com/hassio-addons/addon-ssh)
- [Cloudflared](https://github.com/brenner-tobias/addon-cloudflared/)
- [Samba share](https://github.com/home-assistant/addons/tree/master/samba)
- [Home Assistant Google Drive Backup](https://github.com/sabeechen/hassio-google-drive-backup)
- [Mosquitto broker](https://github.com/home-assistant/addons/tree/master/mosquitto)
- [Zigbee2MQTT](https://github.com/zigbee2mqtt/hassio-zigbee2mqtt/tree/master/zigbee2mqtt)
- [File editor](https://github.com/home-assistant/addons/tree/master/configurator)
- [Vaultwarden (Bitwarden)](https://github.com/hassio-addons/addon-bitwarden)
- [Uptime Kuma](https://github.com/hassio-addons/addon-uptime-kuma)
- [Node-RED](https://github.com/hassio-addons/addon-node-red)
- [Piper](https://github.com/home-assistant/addons/blob/master/piper)
- [RPC Shutdown](https://github.com/home-assistant/addons/tree/master/rpc_shutdown)
- [MariaDB](https://github.com/home-assistant/addons/tree/master/mariadb)
- [Duck DNS](https://github.com/home-assistant/addons/tree/master/duckdns)
- [Portainer](https://github.com/alexbelgium/hassio-addons)
- [Terminal & SSH](https://github.com/home-assistant/addons/tree/master/ssh)
- [Pantry Tracker](https://github.com/mintcreg/pantry_tracker)
- [Whisper](https://github.com/home-assistant/addons/blob/master/whisper)
- [Assist Microphone](https://github.com/home-assistant/addons/blob/master/assist_microphone)
- [openWakeWord](https://github.com/home-assistant/addons/blob/master/openwakeword)
- [Music Assistant Server (beta)](https://music-assistant.io)
- [MQTT Explorer](https://github.com/GollumDom/addon-repository) *(No URL provided)*




</details>


## Devices

<table align="center" border="0" width="100%">
  <thead>
    <tr>
      <th>Quantity</th>
      <th>Device</th>
      <th>Use</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>
        <img src="images/devices/nuc-j3455.jpg" alt="drawing" width="200" />
        <h3>Intel NUC J3455</h3>
      </td>
      <td>
        <p>Ubuntu server running Docker</p>
      </td>
    </tr>
    <tr>
      <td>2</td>
      <td>
        <img src="images/devices/google-home.jpg" alt="drawing" width="200" />
        <h3>Google Home Mini</h3>
      </td>
      <td>
        <p>Voice Assistant</p>
      </td>
    </tr>
    <tr>
      <td>1</td>
      <td>
        <img src="images/devices/echo-show.jpg" alt="drawing" width="200" />
        <h3>Echo show</h3>
      </td>
      <td>
        <p>Voice Assistant</p>
      </td>
    </tr>
    <tr>
      <td>2</td>
      <td>
        <img src="images/devices/led-controller.jpg" alt="drawing" width="200" />
        <h3>LED strip controller</h3>
      </td>
      <td>
        <p>Lights</p>
      </td>
    </tr>
    <tr>
      <td>2</td>
      <td>
        <img src="images/devices/mi-box-s.jpg" alt="drawing" width="200" />
        <h3>Mi Box S</h3>
      </td>
      <td>
        <p>TV</p>
      </td>
    </tr>
    <tr>
      <td>1</td>
      <td>
        <img src="images/devices/mi-wifi-3.jpg" alt="drawing" width="200" />
        <h3>Mi WiFi 3</h3>
      </td>
      <td>
        <p>WiFi router</p>
      </td>
    </tr>
    <tr>
      <td>1</td>
      <td>
        <img src="images/devices/rmmini.jpg" alt="drawing" width="200" />
        <h3>RM mini</h3>
      </td>
      <td>
        <p>IR Blaster</p>
      </td>
    </tr>
    <tr>
      <td>1</td>
      <td>
        <img src="images/devices/pzem.jpg" alt="drawing" width="200" />
        <h3>PZEM</h3>
      </td>
      <td>
        <p>Home power meter</p>
      </td>
    </tr>
    <tr>
      <td>3</td>
      <td>
        <img src="images/devices/sonoff-pow.jpg" alt="drawing" width="200" />
        <h3>Sonoff POW</h3>
      </td>
      <td>
        <p>Switch / Power meter</p>
      </td>
    </tr>
    <tr>
      <td>4</td>
      <td>
        <img src="images/devices/sonoff.jpg" alt="drawing" width="200" />
        <h3>Sonoff</h3>
      </td>
      <td>
        <p>Switch</p>
      </td>
    </tr>
    <tr>
      <td>1</td>
      <td>
        <img src="images/devices/sonoff-switch-2.jpg" alt="drawing" width="200" />
        <h3>Sonoff wall 2 gang</h3>
      </td>
      <td>
        <p>Lights switch</p>
      </td>
    </tr>
    <tr>
      <td>1</td>
      <td>
        <img src="images/devices/wemos.jpg" alt="drawing" width="200" />
        <h3>Wemos</h3>
      </td>
      <td>
        <p>Generic</p>
      </td>
    </tr>
    <tr>
      <td>1</td>
      <td>
        <img src="images/devices/xiaomi-bulb.jpeg" alt="drawing" width="200" />
        <h3>Xiaomi Bulb</h3>
      </td>
      <td>
        <p>Light</p>
      </td>
    </tr>
    <tr>
      <td>2</td>
      <td>
        <img src="images/devices/xiaomi-button.jpg" alt="drawing" width="200" />
        <h3>Xiaomi button</h3>
      </td>
      <td>
        <p>Action button</p>
      </td>
    </tr>
    <tr>
      <td>2</td>
      <td>
        <img src="images/devices/xiaomi-door.jpg" alt="drawing" width="200" />
        <h3>Xiaomi door sensor</h3>
      </td>
      <td>
        <p>Door sensor</p>
      </td>
    </tr>
    <tr>
      <td>3</td>
      <td>
        <img src="images/devices/xiaomi-motion.jpg" alt="drawing" width="200" />
        <h3>Xiaomi motion sensor</h3>
      </td>
      <td>
        <p>Motion sensor</p>
      </td>
    </tr>
    <tr>
      <td>2</td>
      <td>
        <img src="images/devices/xiaomi-temperature.jpg" alt="Xiaomi temperature sensor" width="200" />
        <h3>Xiaomi temperature/humidity sensor</h3>
      </td>
      <td>
        <p>Temperature and humidity sensor</p>
      </td>
    </tr>
    <tr>
      <td>1</td>
      <td>
        <img src="images/devices/cc2531.jpg" alt="Sniffer" width="200" />
        <h3>CC2531 USB</h3>
      </td>
      <td>
        <p>Sniffer - Zigbee to MQTT</p>
      </td>
    </tr>
    <tr>
      <td>1</td>
      <td>
        <img src="images/devices/yi_dome.jpg" alt="Yi dome camera" width="200" />
        <h3>Yi Dome 1080p</h3>
      </td>
      <td>
        <p>Camera and movement detection</p>
      </td>
    </tr>
    <tr>
      <td>1</td>
      <td>
        <img src="images/devices/sonoff-4ch.jpg" alt="Sonoff 4ch" width="200" />
        <h3>Sonoff 4 channel</h3>
      </td>
      <td>
        <p>4 channel switch</p>
      </td>
    </tr>
    <tr>
      <td>1</td>
      <td>
        <img src="images/devices/amazon-fire-7.jpg" alt="Sonoff 4ch" width="200" />
        <h3>Tablet Fire 7</h3>
      </td>
      <td>
        <p>Dashboard mounted on wall with <a href="https://www.etsy.com/" target="_blank">etsy</a> wall mount</p>
      </td>
    </tr>
    <tr>
      <td>1</td>
      <td>
        <img src="images/devices/aqara-cube.jpeg" alt="Sonoff 4ch" width="200" />
        <h3>Xiaomi Aqara cube</h3>
      </td>
      <td>
        <p>Remote controller</p>
      </td>
    </tr>
    <tr>
      <td>1</td>
      <td>
        <img src="images/devices/aqara-temperature.jpg" alt="Aqara temperature" width="200" />
        <h3>Aqara temperature/humidity sensor</h3>
      </td>
      <td>
        <p>Outside temperature and humidity</p>
      </td>
    </tr>
    <tr>
      <td>1</td>
      <td>
        <img src="images/devices/xiaomi-vacuum.jpg" alt="Xiaomi vacuum" width="200" />
        <h3>Xiaomi Mi Robot Vacuum-Mop Pro</h3>
      </td>
      <td>
        <p>Clean</p>
      </td>
    </tr>
        <tr>
      <td>1</td>
      <td>
        <img src="images/devices/shelly-25.jpg" alt="Shelly 2.5" width="200" />
        <h3>Shelly 2.5 double relay</h3>
      </td>
      <td>
        <p>Roller Shutter</p>
      </td>
    </tr>
  <tbody>
</table>

## Automations

### Most important automations

<details>
  <summary>Notify when the water heater is ready</summary>

  [Go to code!](https://github.com/JoaquinBeceiro/home-assistant-config/blob/c82da612f44ed7adee008f6d876e8560fad946e4/config/automations/bathroom.yaml#L20-L68)

  ## Automation trigger

  Every time Water Heater is turned on, this automation turns on.
  The Water Heater has a power meter. When this power meter reads 0w and the switch is on, this automations trigers. This automation only run if time is between **09:00HS** and **05:00HS**.

  ## Automation tasks

  - Play on Google Home with TTS
  - Text notification with Telegram
</details>

<details>
  <summary>Notify power consumption daily</summary>

  [Go to code!](https://github.com/JoaquinBeceiro/home-assistant-config/blob/41c0525266fa52f0d7c0c3110407299596538b52/config/automations/energy.yaml#L5-L33)

  ### Automation trigger

  Every day at **23:59HS**

  ### Automation tasks

  - Notify each power consumption reads (Heater, WaterHeater and Refrigerator) and total of the current day to Telegram
  - [Save power consumptions to Google Spreadsheet](https://github.com/JoaquinBeceiro/home-assistant-config/blob/4cc6b108339242588ebe53619984bc27602b5cb2/config/automations/energy.yaml#L4-L36)

</details>

<details>
  <summary>Notify power consumption monthly</summary>

  [Go to code!](https://github.com/JoaquinBeceiro/home-assistant-config/blob/cb9735e2e04e43a8f65ec5079d1865c2396d6d62/config/automations/energy.yaml#L35-L49)

  ## Automation trigger

  Last day of month at **23:59HS**

  ## Automation tasks

  - Notify month power consuption to Telegram

</details>


<details>
  <summary>Notify when front door is open</summary>
  
  [Go to code!](https://github.com/JoaquinBeceiro/home-assistant-config/blob/cb9735e2e04e43a8f65ec5079d1865c2396d6d62/config/automations/hall.yaml#L1-L17)

  ## Automation trigger

  Front door sensor **ON**

  ## Automation tasks

  - Notify front door open to Telegram and Google Home speakers
  - [Notify if front door is open for 2 minutes to Telegram](https://github.com/JoaquinBeceiro/home-assistant-config/blob/cb9735e2e04e43a8f65ec5079d1865c2396d6d62/config/automations/hall.yaml#L32-L49)

</details>


## Secrets
You can find a complete list of secrets used on this project [here](secrets.example.yaml).


## ToDo list

- [x] Dashboard on Amazon Fire 7 tablet with [Fully Kiosk Browser](https://www.fully-kiosk.com/)
- [x] Aqara cube automations
- [x] Hack motorized roller blind (433MHz)
- [x] Rain sensor
- [x] Add scenes
- [ ] Improve ADB server to control TVs (open APPs, volume, turn on/off)
- [ ] Hardware Topology
- [ ] Add zigbee router/repeater to improve signal
- [ ] Multi-room audio system
- [ ] Add records to InfluxDB

## Authors

**Joaquin Beceiro**

- [GitHub](https://github.com/JoaquinBeceiro)
- [Web](https://JoaquinBeceiro.com.uy)
