---
title: Hardware
permalink: /hardware/
toc: true
---
# Overview

This page includes information on different hardware requirements for different types and size of races, as well as the new GoChips, activators, and phones.

## Equipment by race type

Depending on the type and size of race you hold, you will have different requirements for timing equipment.

### Small club time trial

Could be timed simply with the Zone4 mobile app using the keypad entry. Similar to this would be using Webscorer and their app for keypad entry.

### Loppet

Loppets typically have no rules on timing, and are mass start events. Order of finish is more important than times, and so finish beams are not required. Using chips as a primary time makes most of the timing automatic and reduces the number of volunteers required. The cost of chips is more easily born by the generally higher race fees.
Consider the difficulties of handing out hundreds of chips at once to a large starting field however, and make sure to plan enough volunteer help at the start.

### Regional Cup

TODO

### BC Cup/Westerns

At BC Cup level events and higher, chips are not allowed to be the primary time source. Instead we use the finish beams, with summit plungers as backup, and use the chips for bib order and backup.

### NorAm/Nationals

TODO

### Summary

This table summarizes these suggestions:

| | Phone keypad | Summit keypad | Finish beams | Chips | Finish camera |
|--|---|---|---|---|---|
| Time trial | x | | | | |
| Loppet | x | x | | x | |
| Regional cup | | x | x | o | |
| BC Cup | | x | x | x | o |
| National | | x | x | x | x |

## Hardware (GoChips)

The new GoChip system from Zone4 makes many aspects of timing simpler and more automated, but introduces some new issues to think about and plan for.

At a high level, the GoChips are an active chip system. Each chip has memory and a battery. Chips are woken up and activated by movement, and will sleep to conserve battery between uses. When a chip passes over a wire loop activator, the time and loop number is stored on the chip. Chips also have a bluetooth connection, and will automatically connect to Android phones running the Zone4 app. Times are then transferred to the phone, and from there to the Zone4 servers.

The activators are a small brick sized box with a few status lights and connectors to attach the wire loop. This loop runs from the activator and across your course around the finish line or other timing point you wish to capture. The chip will use the centre point of the loop to capture the time, so the loop should be evenly spaced across the trail at a constant width either side of the finish line.

This image shows the basic process.

![Flow for reading a chip]({{ "/assets/gochip-flow.svg" | absolute_url }})

Because times are stored on the chip, timing points can be placed around the course without needing network connectivity. The times will be read off the chip once it connects with a phone.