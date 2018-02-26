# ZTE Axon 7 Dolby Atmos
This module enables ZTE Axon 7 Dolby Atmos port and is the fifth most compatible of all the ports. [More details in support thread](https://forum.xda-developers.com/android/software/soundmod-axon-7-dolby-atmos-t3412342).

## Compatibility
* Android Marshmallow-Nougat
* Selinux enforcing
* All root solutions (requires init.d support if not using magisk or supersu. Try [Init.d Injector](https://forum.xda-developers.com/android/software-hacking/mod-universal-init-d-injector-wip-t3692105))

## Change Log
### v1.5 - 2.25.2018
* Fixed vendor files in bootmode for devices with separate vendor partitions
* Bring back old keycheck method or devices that don't like the newer chainfire method
* Fix seg faults on system installs

### v1.4 - 2.16.2018
* Add file backup on system installs
* Fine tune unity prop logic
* Update util_functions with magisk 15.4 stuff
* Fix music_helper/sa3d removal in xml files

### v1.3 - 2.12.2018
* Fix vendor cfg creation for devices that don't have it
* Fix sepolicy patching

### v1.2 - 2.10.2018
* Added sa3d removal for samsung devices

### v1.1 - 2.6.2018
* Fixes for xml cfg files

### v1.0 - 2.5.2018
* Initial rerelease

## Credits
* [Dolby Laboratories](https://www.dolby.com/us/en/brands/dolby-atmos.html)
* [ZTE](https://www.zteusa.com/)

## Source Code
* Module [GitHub](https://github.com/therealahrion/Dolby-Atmos-ZTE-Axon-7)
* Collective Dolby Atmos Ports [GitHub](https://github.com/therealahrion/Collective-Dolby-Atmos-Ports)
