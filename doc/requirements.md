# Requirements

This document describes the high level goals of what the project is seeking to achieve.

## Functional Requirements

Able to set complex programmes/schedules, i.e.:
 - Turn on and off multiple times per day
 - Able to have different schedules on different days, e.g. weekday vs weekend

Able to be remotely accessed and controlled away from premises that it is installed in (this may be delivered by being integrated into a remotely accessible Home Automation System).


## Non-Functional Requirements

Support a wide range of devices, from manufactures such as:
 - Fujitsu
 - Panasonic
 - Mitsubishi
 - Daikin
 - etc. (add additional as desired)

Able to integrate into existing home automation systems via standard protocols, e.g. [Matter](https://en.wikipedia.org/wiki/Matter_(standard)).

This also means it will require a network communication interface of some sort, Wifi (802.11) or ethernet is likely to be a logical choice, though bluetooth may be explored, but is not a priority at this time.

Able to be mounted on a wall with appropriate line of sight to heatpump, as will aim to use IR signals as primary means of communication with Heatpump.

Can be either battery powered (although this will further introduce need for battery power management), or hardwired to an external power source.

Must use affordable and easily accessible hardware.

Must be able to be configured to local environment, e.g. Wifi, IP address, home automation controller, etc. Ideally it would be able to use autoconfiguration/registration if possible.
