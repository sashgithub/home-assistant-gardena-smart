# home-assistant-gardena-smart
gardena smart garden

Code from Jérémie Klein - grm


configuration.yaml

email: !secret gardena_email
password: !secret gardena_password
client_id: !secret gardena_client_id
location_id: !secret gardena_location_id
mower_duration: 300
smart_irrigation_control_duration: 60
smart_watering_duration: 1800
