---
layout: documentation
title: ZRTSI - ZWave
---

{% include base.html %}

# ZRTSI Z-Wave to RTS Interface Controller
This describes the Z-Wave device *ZRTSI*, manufactured by *[Somfy](http://www.somfy.com/)* with the thing type UID of ```somfy_zrtsi_00_000```.

The device is in the category of *Blinds*, defining Roller shutters, window blinds, etc..

The ZRTSI does not permanently listening for messages sent from the controller - it will periodically wake up automatically to check if the controller has messages to send, but will sleep most of the time to conserve battery life. The wakeup period can be configured in the user interface - it is advisable not to make this too short as it will impact battery life - a reasonable compromise is 1 hour. The wakeup period does not impact the devices ability to report events or sensor data. The device can be manually woken with a button press on the device as described below - note that triggering a device to send an event is not the same as a wakeup notification, and this will not allow the controller to communicate with the device.

## Overview

No device information is provided in the database. Consider [updating the database](http://www.cd-jackson.com/index.php/zwave/zwave-device-database/zwave-device-list/devicesummary/369) to improve the documentation.

## Channels

The following table summarises the channels available for the ZRTSI

| Channel | Channel Id | Category | Item Type |
|---------|------------|----------|-----------|



## Device Configuration

The device has no configuration parameters configured.

## Association Groups

Association groups allow the device to send unsolicited reports to the controller, or other devices in the network. Using association groups can allow you to eliminate polling, providing instant feedback of a device state change without unnecessary network traffic.

The device does not support associations.
## Technical Information

### Endpoints

#### Endpoint 0

| Command Class | Comment |
|---------------|---------|
| COMMAND_CLASS_NO_OPERATION_V1| |
| COMMAND_CLASS_BASIC_V1| |
| COMMAND_CLASS_MANUFACTURER_SPECIFIC_V1| |
| COMMAND_CLASS_VERSION_V1| |

### Documentation Links

* [Manual](https://www.cd-jackson.com/zwave_device_uploads/369/ZRTSI-Instructions-1811265.pdf)

---

Did you spot an error in the above definition or want to improve the content?
You can [contribute to the database here](http://www.cd-jackson.com/index.php/zwave/zwave-device-database/zwave-device-list/devicesummary/369).
