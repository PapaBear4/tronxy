# tronxy
Tronxy X5SA config files

Factory config is what M8512??? read off the machine.

X5SA-PRO-24V-TLM8_V1.1.Gcode.gcode is what I downloaded from the Tronxy website as a "firmware" update.

Once running that I read it again with M???? and got back TronxyUpdatedConfig.gcode.  One interesting thing I noticed is that not all of the M-codes that were read in came back out again.  And the ones that were factory set, but not in the update, did not update.

The biggest reason that I started this was to try and "fix" the retraction settings.  The official Tronxy update did not do this so I've moved on to my own builds.  I've not gotten it to where I like yet, but I'm making progress.  So far, the most important thing I've learned is that M8020 doesn't seem to want to set to 0.00.
