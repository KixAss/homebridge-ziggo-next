# homebridge-ziggo-next

`homebridge-ziggo-next` is a Homebridge plugin allowing you to control your mediabox & any connected HDMI-CEC controllable devices with the Apple Home app & Control Centre remote!

The Ziggo Next will display as a TV Accessory with Power, Input & Remote Control.

## Requirements
* iOS 12.2 (or later)
* [Homebridge](https://homebridge.io/) v0.4.46 (or later)

## Installation
Install homebridge-ziggo-next:
```sh
npm install -g homebridge-ziggo-next
```

## Usage Notes
Quickly switch input using the information (i) button in the Control Centre remote

## Configuration
Add a new platform to your homebridge `config.json`.

Specific "favourite" inputs can be added manually or all available inputs reported by the AVR will be set.

Example configuration:

```js
{
    "platforms": [
      {
        "platform": "ziggo-next",
        "name": "Mediabox",
        "username": "your@email.com",
        "password": "Your Ziggo-password"
      }
    ]
  }
```

## Thanks to
[homebridge-yamaha-avr](https://github.com/ACDR/homebridge-yamaha-avr)

[NextRemoteJs](https://github.com/basst85/NextRemoteJs/)