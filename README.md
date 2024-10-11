# Riley U0 Board

This is a hello world project in kicad. Just learning my way around.

Attempting to design a little board for a STM32U0 MCU.

Down the road (maybe a long time from now) I'd like to develop some open-source hardware projects as cheaper, more tractable alternatives to commercial scientific tools. I have a suspicion that the hobbyist electronics market is a severely under-utilized asset in ecological research.

If I'm able to come up with something useful here, I'll flesh out the docs and write a BSP in rust. But highly likely that I get 3/4 of the way done with this and feel like i've learned enough to move on to designing a non-toy project. We'll see.

## Stuff Riley Needs To Figure Out

- it would be nice to have a precommit that generates a new .pdf of the schematic every time i commit
- is it possible to run a design rules check on precommit/CI?
- Library/footprint management oh my god
- What the hell am i supposed to do with analog signals regarding EMI/noise stuff? e.g. especially with regards to amplifying analog signals to go into ADC
- Get lowpowerpilled: how much does underclocking/undervolting help?
- if i have some peripheral device e.g. i2c sensor where quiescent power consumption is much higher than my idle MCU, how can i cut off consumption when i'm not using it?
- I have legitimately no idea how oscillators work and i need pretty accurate time for my projects