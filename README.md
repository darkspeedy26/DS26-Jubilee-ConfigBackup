# DS26-Jubilee-ConfigBackup
## !!! WIP - USE AT YOUR OWN RISK !!!

I made a mix of [TypQxQ's](https://github.com/TypQxQ/KTC) KTCv1 backupconfig for his duet to work with his, wich i mixed with examples for his [KTCv2](https://github.com/TypQxQ/KTC) which i mixed with my Jubilee setup
I also rotated the bed 90° in the config, but that might have broken the pause command. Might also have broken other config things.


### List of issues:
- usually at startup i have to unlock or it errors out. I might have configured the lock sequence wrong while editing out 
- Pause crashes the tool. I should let it park the tool first, and then move toolhead to safe position
- cant get my bigtreetech sfs2.0 smart filament sensors to work
- some comments in the configs might not be translated from Dutch to English
- everytime you dock/undock a tool manually without printing, the bed moves Z higher. This is good while printing, but can be annoying when callibrating tool offsets manually with camera. Might be baked into KTCCv2 (not sure)
- cleanup of unused .cfg files


### used hardware:
- bigtreetech E3 mini - used for X Y and Lock
- BTT E3 DIP - used for 3x Z
- bigtreetech octopus i think v1.1 - used for tools and most fans
- XY motors: moons (i think the same as the E3D toolchanger)
- Z and Lock motors + keenovo bed heater: stock
- 4x BabyBullet tools with E3D revo micro's + orbiter 2.0


### usefull links:
- https://github.com/TypQxQ/DuetBackup/tree/fd98069c8b25ab5cdabb592dc4f357e2a89a62ec/qTC-Klipper - the exact branch on what this is based on mostly (its probably out of date by now)
- https://github.com/TypQxQ/KTC - what this mashup is meant for
- https://github.com/machineagency/jubilee - the toolchanger/printer
- https://youtu.be/Qzjp7f88pGU?si=0Wt-MwgSmdutiFYD - pre E3D Revo and pre enclosure video of the printer
- https://discord.com/channels/627982902738681876/760568333564903444/926141946039242802 - "made-a-jubilee" post of this printer (pre enclosure and tool upgrades)
- https://a360.co/3zkx1BG - 3D file with some of the mods of my printer
