# CWONDR

Project "CW on da road":
low-power pocket-size CW transceiver for direct amateur radio contacts on 70 cm

## Motivation

*You're strolling through the city on a warm summer evening, chatting with your friends, when all of a sudden you hear a faint Morse signal out of your pocket. You take out the small device, plug in the earphones, and key a QRZ DE YOURCALLSIGN?*

*There's a response from your buddy who seems to be in town as well, and you quickly exchange some greetings and QTH information, so that you can meet in a nearby coffee shop in half an hour.*

*After you've finished, you receive a call on the same frequency from a ham visiting your city, and you invite them along for a coffee. You may just have made a new friend through the air.*

*You set your device to beacon mode, unplug the earphones, and put it back into your pocket, while explaining to your friends you just did the CW equivalent of a local social web exchange.*

All of this should well be possible, except that to my knowledge,
such a device is not (yet) available commercially.
If you know about something similar, please [contact me][] ASAP!

## The Problem

- CW nowadays is mostly used for contesting and DX, only rarely for chatting
- Handheld VHF/UHF transceivers are only available for FM voice transmission
- HF requires big antennas and is not suited for operation "out of pocket"

## The Solution

- 5 V power is widely available in USB supplies and batteries: no development!
- 70 cm is an uncrowded band suitable for short range contacts: low noise!
- RF systems for 70 cm are widely available: cheap development!
- Arduino and similar solutions provide low-power control facilities

## The Dream

- mobile-phone sized device
- powered by external USB source, low power consumption in receive mode
- key button for CW transmission included, external possible
- small loudspeaker included, main operation through earphones
- user interface through buttons and Morse sidetone, i.e no display required
- selectable transmit power levels for short range QSOs

## Participation

This is a very young project, and your participation is highly appreciated,
by [e-mail][contact] or by pull requests to this repository!

- [list of ideas]( ideas.md )
- [hardware todo list]( todo-hard.md )
- [software todo list]( todo-soft.md ).

---

[contact]: mailto:hb9kns@gmail.com

_(2018-July-8 HB9KNS)_
