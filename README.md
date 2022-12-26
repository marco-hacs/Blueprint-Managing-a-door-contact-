`- Version: 1.0 -`

# Managing a door contact

In this blueprint I try to exploit a sensor port for multiple uses. 

Automation is divided into two parts: 
1)  Turns on a light when the door is opened for a customizable time by following rules:
- Let it be after sunset
- You can insert switch and light
- The light is turned on/off only if the initial state was not on
- The light is turned off after a customizable time that starts from the moment the door is closed

2) Receive an alert in case the door was left open for a customizable time:
- You can decide whether to enable push notification.
- You can decide whether to enable TTS notification.
- You can decide whether to enable Alexa notification.
- You can customize the text of the notification.
- You can opt out of receiving alerts by not enabling any of the notify services

### Requirements:

In order to use the project:
- The door sensor must be *device_class: door*: If the senor does not have the device_class indicated, you can set it from *settings-devices and services-entities-select entity and set port to show-like* 


### Installation

To be able to install the blueprint you can import it tramitè the dedicated button or alternatively you can compiare the <i>[file](https://github.com/marco-hacs/Managing-a-door-contact-/blob/main/managing_a_door_contact.yaml)</i> in the path \config\blueprints\automation 

<a href="https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fmarco-hacs%2FManaging-a-door-contact-%2Fblob%2Fmain%2Fmanaging_a_door_contact.yaml" target="_blank"><img src="https://my.home-assistant.io/badges/blueprint_import.svg" alt="Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled." /></a>
