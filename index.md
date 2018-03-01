# Zone4 with CCBC

The web version of Zone4 and accompanying Go Chips system is a large change from what many are used to using to time cross-country skiing and other sports in British Columbia.
This site will help give some best practices and pointers for how to use the software in a well-known consistent manner throughout the province.

Please note that Zone4 is always changing and improving their software, and content here may become out of date. They have a great help system of their own over at [Zone4 Help](http://help.zone4.ca/).

## Registration

The first step to running a race is getting people registered.

- Create a registration page
- Create a race
- Setup start groups
- Create the start list and post it online

## Pre-race setup

Zone4 allows you to do quite a lot while the race is in progress, but it's still best to be prepared and get some things setup beforehand.

- Configure course groups
- Configure result sets (overall, category, chip handout lists, etc)
- Configure and test timing points

## Hardware

### Equipment by race type

Depending on the type and size of race you hold, you will have different requirements for timing equipment.

#### Small club time trial

Could be timed simply with the Zone4 mobile app using the keypad entry. Similar to this would be using Webscorer and their app for keypad entry.

#### Loppet

Loppets typically have no rules on timing, and are mass start events. Order of finish is more important than times, and so finish beams are not required. Using chips as a primary time makes most of the timing automatic and reduces the number of volunteers required. The cost of chips is more easily born by the generally higher race fees.
Consider the difficulties of handing out hundreds of chips at once to a large starting field however, and make sure to plan enough volunteer help at the start.

#### Regional Cup

TODO

#### BC Cup/Westerns

At BC Cup level events and higher, chips are not allowed to be the primary time source. Instead we use the finish beams, with summit plungers as backup, and use the chips for bib order and backup.

#### NorAm/Nationals

TODO

#### Summary

This table summarizes these suggestions:

| | Phone keypad | Summit keypad | Finish beams | Chips | Finish camera |
|--|---|---|---|---|---|
| Time trial | x | | | | |
| Loppet | x | x | | x | |
| Regional cup | | x | x | o | |
| BC Cup | | x | x | x | o |
| National | | x | x | x | x |

### Hardware (GoChips)

The new GoChip system from Zone4 makes many aspects of timing simpler and more automated, but introduces some new issues to think about and plan for.

At a high level, the GoChips are an active chip system. Each chip has memory and a battery. Chips are woken up and activated by movement, and will sleep to conserve battery between uses. When a chip passes over a wire loop activator, the time and loop number is stored on the chip. Chips also have a bluetooth connection, and will automatically connect to Android phones running the Zone4 app. Times are then transferred to the phone, and from there to the Zone4 servers.

The activators are a small brick sized box with a few status lights and connectors to attach the wire loop. This loop runs from the activator and across your course around the finish line or other timing point you wish to capture. The chip will use the centre point of the loop to capture the time, so the loop should be evenly spaced across the trail at a constant width either side of the finish line.

This image shows the basic process.

![Flow for reading a chip]({{ "/assets/gochip-flow.svg" | absolute_url }})

Because times are stored on the chip, timing points can be placed around the course without needing network connectivity. The times will be read off the chip once it connects with a phone.

### Hardware (Networking)

Good practice to separate functions (Start/Laps, Finishes, Printing results and verification)

When using a serverbox or the old desktop Zone4, a network switch to connect all timing computer is highly recommended. Zone4 will ship a Ubiquiti Bullet Wifi access point with the serverbox, and while this is useful for the phones, it works best for the timing computers to be hardwired together. A networked printer is also a good idea, as this allows anyone to print results if necessary.

TODO: network diagram

### More TODO

- Activator placement
- Loop checker
- Phone placement
- Chip racks
- Chip tester tool
- Chip distribution logistics
- Server box
- How do Summits fit in?

## During the race

TODO

- Timing grids
- Results
- Announcer view

## Document resources

### Run sheet

[Run sheet](run-sheet) - describes tasks done by different teams throughout the race

### Volunteer assignments

[Volunteer assignments](volunteer-assignments) - different roles required

### Timing diagrams

[2018 Payak timing diagram - chips but no Summits](assets/2018 P'ayak TIMING DIAGRAM without Summits.pdf)

## Other resources

- As mentioned before, try the Zone4 official help pages first: [Zone4 Help](http://help.zone4.ca/).
- Contact an experienced volunteer: @alarobric on Github, Twitter, Facebook, etc. has done timing for many races at Whistler and Kamloops, and can also put you in contact with others in the province.

## Contributing

Contributions to this documentation are welcome. If you're comfortable with Github, feel free to send me a pull request with your changes, otherwise you can open an issue on Github with your suggestion, or even just send me an email with your change.
