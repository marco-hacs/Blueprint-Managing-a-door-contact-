`- Version: 1.0 -`

# Managing a door contact

In this project I try to exploit a sensor port for multiple uses. 

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


### Installazione

Per poter installare il progetto puoi importarlo tramitè il tasto ........
In alternativa puoi compiare il FILExxxxx  nella directory \config\blueprints\automation 
