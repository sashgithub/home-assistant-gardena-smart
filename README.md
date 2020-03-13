# home-assistant-gardena-smart
Gardena Smart Garden

*   Code from Jérémie Klein - grm
*   Thx to Jérémie Klein - please support him!

## Requirements

*   **Python 3.6+**

## Supported devices

For now, only few devices are supported. I may add new ones in the future :  
*   Gateway
*   Smart Mower
*   Smart water control
*   Smart sensor
*   Power plugs
*   Smart Irrigation control

## Account creation in order to have access to Gardena API

Gardena requires the creation of an account and an application in order to use their API.
You can find how to create such an account and application here : <a href="https://developer.1689.cloud/docs/getting-started#/docs/getting-started/#3connect-api-to-application">Account and application creation</a>


## Home Assistant
```
configuration.yaml

email: !secret gardena_email
password: !secret gardena_password
client_id: !secret gardena_client_id
location_id: !secret gardena_location_id
mower_duration: 300
smart_irrigation_control_duration: 60
smart_watering_duration: 1800
```
60 = 1 minute (example: 1800 = 30 minutes)
