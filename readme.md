# TaWI

First write out your devotions.
Then, each day, set your intentions in service of each devotion.
At the end of the day, reflect on the actions you took.

## How?

`tawi` relies on taskwarrior -- it's assumed you've got that installed already.

Clone this repo and put it somewhere convenient like ~/.
`$ tawi devotions` is used to write out your devotions.

Then, each day you'll use these commands:
- `$ tawi new` to declare your intentions for the day
- `$ tawi set` to officially set them, putting them into taskwarrior
- Use taskwarrior throughout the day to mark off your tasks
- `$ tawi reflect` will help you review your day, and it's saved in `./reflections`

