Full Device tree of Samsung Galaxy A52s 5G (SM-A528B).

THIS TREE REQUIRES FURTHER CONSOLIDATION/EXTRA MODIFICATIONS IN ORDER TO ACHIEVE STABILITY AND AVOID ERORS.

Feel free to create a fork of this repository, which contains a better developed structure/content than of this tree.

Device.mk is named twrp.device.mk because once this tree is made stable and complete, the TWRP manifest requires the prefix to be added https://github.com/minimal-manifest-twrp/platform_manifest_twrp_aosp.

This tree is named 'heavy' because i added alot more files, changed some file locations and added much more code to the .mk files, making this version more experimental than the lite version e.g. i added a multidisabler script at /recovery/root/system/bin developed by Ian MacDonald and afaneh92.
To use the multidisabler script in TWRP once built:

- Go to Advanced > Terminal, type: multidisabler.​
If vendor complain about free space left on device, will attempt to resize vendor. and it ask to  - Run multidisabler again!.​
- Type: multidisabler again. will see  - Finished. when done.​
- Go back to Wipe > Format Data > type yes.​
- Reboot to recovery.​


The lite version of the tree is avalable here: https://github.com/theyellowray/teamwinrecovery_samsung_a52sxq-lite- (built by a TWRP tree auto builder)
