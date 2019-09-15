# Tarantula-pro

Purpose for this Fork:

I bought the Tevo Tarantula Pro 2019 + BL Touch Sensor + Dual Z + TMC2208 bundle;
At the time of this writing, Tevo supplies the Marlin firmware source code with different configuration.h/configuration_adv.h files, depending on the "extras" that buyers went for: BL Touch sensor, Dual Z motors, Silent TMC2208 Stepper Drivers;
However, Tevo doesn't supply a config version with all extras included, and it would just be a matter of combining the different configs to achieve the result.
I had to do it to get my setup to work as intended and saw other people requesting for this on YouTube - if you haven't already, please check out the very detailed and helpful videos by @ruiraptor - both generic and extras assembly as well as firmware configuration changes, calibration, tips and tricks, those videos are a great help and may save you a few headaches along the way.

So, back to this fork:

The master branch will hold Tevo's original zip archives;
Branch 20190716_dualz_bltouch_tmc2208 holds the config I'm using that combines all the available extras at the moment, as stated above.
Will update the branch if required, but for now it all seems to be working as intended - please improve upon/provide feedback if you can, so that until a better solution is available, we may all benefit from better settings/extras support/etc. on the firmware.


Thank you.
