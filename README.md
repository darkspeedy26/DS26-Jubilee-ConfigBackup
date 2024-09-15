# DS26-Jubilee-ConfigBackup
!!! WIP - use at your own risk !!!

I modified and tried to simplify typqxq's backupconfig of his KTCv1 for his duet to work with his KTCCv2.
I also rotated the bed 90° in the config, but that might have broken the pause command. Might also have broken other config things
not every uploaded .cfg file is used


List of issues:
- usually at startup i have to unlock or it errors out. I might have configured the lock sequence wrong while editing out 
- Pause crashes the tool. I should let it park the tool first, and then move toolhead to safe position
- cant get my bigtreetech sfs2.0 smart filament sensors to work
- some comments in the configs might not be translated from Dutch to English
- everytime you dock/undock a tool manually without printing, the bed moves Z higher. This is good while printing, but can be annoying when callibrating tool offsets manually with camera. Might be baked into KTCCv2 (not sure)


used hardware:
- bigtreetech E3 mini - used for X Y and Lock
- BTT E3 DIP - used for 3x Z
- bigtreetech octopus i think v1.1 - used for tools and most fans
- XY motors: moons (i think the same as the E3D toolchanger)
- Z and Lock motors + keenovo bed heater: stock
- 4x BabyBullet tools with E3D revo micro's + orbiter 2.0
