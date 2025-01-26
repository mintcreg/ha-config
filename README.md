<h1 align="center">HomeAssistant config</h1>


<p align="center">
  Below is my HomeAssistant config, this is more for my own documentation purposes but if its usefull to you please give it a star! 😇
</p>

<p align="center">
  <img alt="Last Commit" src="https://img.shields.io/github/last-commit/mintcreg/ha-config?style=plasticr"/>
  <img alt="Commit activity" src="https://img.shields.io/github/commit-activity/m/mintcreg/ha-config"/>
  <img alt="Maintenance" src="https://img.shields.io/maintenance/yes/2025"/>
</p>

<p align="center">
  <img alt="HA Version" src="https://img.shields.io/badge/HA--Version-2025.1.2-9cf"/>
  <img alt="Mosquitto Version" src="https://img.shields.io/badge/Mosquitto--Version-6.5.0-9cf"/>
  <img alt="MariaDB Version" src="https://img.shields.io/badge/MariaDB--Version-2.7.2-9cf"/>
  <img alt="MariaDB Version" src="https://img.shields.io/badge/Zigbee2MQTT--Version-2.0.02-9cf"/>
</p>

## Table of Contents

- [Mobile Dashboard](#mobile-dashboard)
- [Integrations](#integrations)
- [Lovelace Cards](#lovelace-cards)
- [Addons](#addons)
- [Devices](#devices)
- [Automations](#automations)
- [ToDo list](#todo-list)

## Mobile Dashboard



Please visit the dashboard section [Mobile Dashboard](https://github.com/mintcreg/ha-config/tree/main/dashboard/mobile) and open up each folder which will contain screenshots and a demo (where possible) along with the full room view YAML

- [Home Page](https://github.com/mintcreg/ha-config/tree/main/dashboard/mobile/home) - A sleek homepage showing all rooms with bubble popup cards for sections and swiper sliders.
- [Birthday Calendar](https://github.com/mintcreg/ha-config/tree/main/dashboard/mobile/calendar) - A page to display upcoming birthday's with a markdown card, calendar and option to add a new calendar entry.
- [Health/Network Status](https://github.com/mintcreg/ha-config/tree/main/dashboard/mobile/health) - A health status page to monitor a Windows PC / Unraid Server / RPI4 & Router.
- [Profile Page](https://github.com/mintcreg/ha-config/tree/main/dashboard/mobile/profile%201) - A profile page to show all specific user settings (input helpers used in automations).

<details>
  <summary>Screenshots</summary>
  
<br>

![Slideshow](/images/screenshots/dashboard/overall.gif)

</details>

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
- [DVLA-Vehicle-Enquiry-Service](https://github.com/jampez77/DVLA-Vehicle-Enquiry-Service/)
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

<details>
  <summary>Show full list</summary>
  
<br>
<h2 align="center">Primary Devices</h2>
<table align="center" border="0" width="100%">
  <thead>
    <tr>
      <th>Device</th>
      <th>Name</th>
      <th>Use</th>
      <th>Quantity</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <img src="images/devices/rpi.png" alt="drawing" width="120" />
      </td>
      <td><a href="https://www.raspberrypi.com/products/raspberry-pi-4-model-b/">RPI 4 (8gb)</a></td>
      <td>Directly running HASSIO OS</td>
      <td>x1</td>
    </tr>
    <tr>
      <td>
        <img src="images/devices/RT-AC86U.jpg" alt="drawing" width="120" />
      </td>
      <td><a href="https://www.asus.com/uk/networking-iot-servers/wifi-routers/asus-wifi-routers/rt-ac86u/">ASUS RT-AC86U</a></td>
      <td>Router</td>
      <td>x1</td>
    </tr>
    <tr>
      <td>
        <img src="images/devices/SONOFF-Zigbee-plus-e.jpg" alt="drawing" width="120" />
      </td>
      <td><a href="https://www.amazon.co.uk/SONOFF-Universal-ZBDongle-Gateway-Assistant/dp/B0B6P22YJC">SONOFF-Zigbee Plus-E</a></td>
      <td>Zigbee co-ordinator</td>
      <td>x1</td>
    </tr>
    <tr>
      <td>
        <img src="images/devices/google-mini.jpg" alt="drawing" width="120" />
      </td>
      <td><a href="https://store.google.com/product/google_nest_mini?hl=en-GB&pli=1">Google Home Mini</a></td>
      <td>Voice Assistant</td>
      <td>x2</td>
    </tr>
  </tbody>
</table>


<h2 align="center">Zigbee Devices</h2>
<table align="center" border="0" width="100%">
  <thead>
    <tr>
      <th>Device</th>
      <th>Name</th>
      <th>Use</th>
      <th>Quantity</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <img src="images/devices/ikea-vallhorn-motion-sensor.jpeg" alt="drawing" width="120" />
      </td>
      <td>
        <a href="https://www.ikea.com/gb/en/p/vallhorn-wireless-motion-sensor-smart-white-90504341/">Ikea Vallhorn Motion Sensor</a>
      </td>
      <td>
        Capture motion
      </td>
      <td>x4</td>
    </tr>
    <tr>
      <td>
        <img src="images/devices/sonoff-snzb-02.jpeg" alt="drawing" width="120" />
      </td>
      <td>
        <a href="https://sonoff.tech/product/gateway-and-sensors/snzb-02/">Sonoff SNZB-02</a>
      </td>
      <td>
        Temperature Sensor
      </td>
      <td>x2</td>
    </tr>
    <tr>
      <td>
        <img src="images/devices/sonoff-snzb-04.jpeg" alt="drawing" width="120" />
      </td>
      <td>
        Sonoff SNZB-02
      </td>
      <td>
        Open/close sensor
      </td>
      <td>x3</td>
    </tr>
    <tr>
      <td>
        <img src="images/devices/tuya-TT001ZAV20.png" alt="drawing" width="120" />
      </td>
      <td>
        <a href="https://www.aliexpress.com/item/1005006097911972.html?spm=a2g0o.productlist.main.67.6e4bDRxFDRxFaq&algo_pvid=c9da9377-4fe7-4899-99c3-f3c8c24115bd&utparam-url=scene%3Asearch%7Cquery_from%3A">TUYA - TS0201</a>
      </td>
      <td>
        Fridge temperature sensor
      </td>
      <td>x1</td>
    </tr>
    <tr>
      <td>
        <img src="images/devices/tuya-TS0011.jpeg" alt="drawing" width="120" />
      </td>
      <td>
        <a href="https://www.aliexpress.com/item/1005006243515442.html?spm=a2g0o.productlist.main.5.1bbf1ce0SbZ0gq&algo_pvid=c8e55973-7666-4687-b9dc-3fac5df54fb0&utparam-url=scene%3Asearch%7Cquery_from%3A">Tuya - TS0011</a>
      </td>
      <td>
        Light switch
      </td>
      <td>x9</td>
    </tr>
    <tr>
      <td>
        <img src="images/devices/tuya-BSD29_1.jpeg" alt="drawing" width="120" />
      </td>
      <td>
        <a href="https://www.aliexpress.com/item/1005006346571151.html?spm=a2g0o.productlist.main.11.cf6d6630pGXRKZ&algo_pvid=63bcba82-75ec-4dee-aab5-8750b9cfa96f&utparam-url=scene%3Asearch%7Cquery_from%3A">Tuya BSD29_1</a>
      </td>
      <td>
        Switch / Power meter
      </td>
      <td>x1</td>
    </tr>
    <tr>
      <td>
        <img src="images/devices/tuya-WSD500A.jpeg" alt="drawing" width="120" />
      </td>
      <td>
        <a href="https://www.aliexpress.com/item/1005008248042691.html?spm=a2g0o.productlist.main.1.4e971b8bMyyr9y&algo_pvid=2eea70ac-dd3d-49e5-bfcc-d27824738dd7&utparam-url=scene%3Asearch%7Cquery_from%3A">Tuya - WSD500A</a>
      </td>
      <td>
        Temperature Sensor
      </td>
      <td>x3</td>
    </tr>
    <tr>
      <td>
        <img src="images/devices/tuya-ZG-227Z.png" alt="drawing" width="120" />
      </td>
      <td>
        <a href="https://www.aliexpress.com/item/1005007645898497.html?spm=a2g0o.productlist.main.11.6e4bDRxFDRxFaq&algo_pvid=c9da9377-4fe7-4899-99c3-f3c8c24115bd&algo_exp_id=c9da9377-4fe7-4899-99c3-f3c8c24115bd-5&pdp_npi=4%40dis%21GBP%213.47%211.80%21%21%2130.32%2115.74%21%40211b813f17378355900048747e9cd3%2112000041638489031%21sea%21UK%210%21ABX&curPageLogUid=pOazckk2dyUn&utparam-url=scene%3Asearch%7Cquery_from%3A">Tuya - ZG-227Z</a>
      </td>
      <td>
        Temperature Sensor
      </td>
      <td>x5</td>
    </tr>
    <tr>
      <td>
        <img src="images/devices/tuya-ZY-M100-24GV3.png" alt="drawing" width="120" />
      </td>
      <td>
        <a href="https://www.aliexpress.com/item/1005005543432442.html?spm=a2g0o.productlist.main.3.f717IOqMIOqMHd&algo_pvid=5216b319-d187-4277-871d-4646b1ba2bf3&utparam-url=scene%3Asearch%7Cquery_from%3A">Tuya - ZY-M100-24GV3</a>
      </td>
      <td>
        Presence sensor
      </td>
      <td>x2</td>
    </tr>
  </tbody>
</table>



</details>

## Automations

- [Birthday Reminders](https://github.com/mintcreg/ha-config/tree/main/automations/Birthday%20Reminders) - Reminders for upcoming birthdays at defined intervals (using local calendar)
- [TAX & MOT Reminder](https://github.com/mintcreg/ha-config/tree/main/automations/TAX%20%26%20MOT%20Reminder) - Reminders for car TAX & MOT at defined intervals
- [Wheelie Bins/Trash](https://github.com/mintcreg/ha-config/tree/main/automations/Wheelie%20Bins) - Reminders for trash/wheelie bins being put out and taking back in (with virtual trackers)
- [Electric Car](https://github.com/mintcreg/ha-config/tree/main/automations/Electric%20Car) - Save a little bit of money whilst charging with Octopus Energy and an electric car


## ToDo list

- [ ] Add items to the to do list


