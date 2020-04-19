# Tarantula-pro

Purpose for this Fork:

I bought the Tevo Tarantula Pro 2019 + BL Touch Sensor + Dual Z + TMC2208 bundle;
At the time of this writing, Tevo supplies the Marlin firmware source code with different configuration.h/configuration_adv.h files, depending on the "extras" that buyers went for: BL Touch sensor, Dual Z motors, Silent TMC2208 Stepper Drivers;
However, Tevo doesn't supply a config version with all extras included, and it would just be a matter of combining the different configs to achieve the result.
I had to do it to get my setup to work as intended and saw other people requesting for this on YouTube - if you haven't already, please check out the very detailed and helpful videos by @ruiraptor - both generic and extras assembly as well as firmware configuration changes, calibration, tips and tricks, those videos are a great help and may save you a few headaches along the way.

So, back to this fork:

* **master** - holds Tevo's original zip archives
* **20190716_dualz_bltouch_tmc2208** - holds the config that combines all the available extras, as stated above
* **20200419_tmc2208_all** - branched off of **20190716_dualz_bltouch_tmc2208** to enable TMC 2208 for all stepper drivers
  * X, Y, both Z and the Extruder
  * Configured all stepper drivers to use 1.19V using the built-in potentiometer and a multimeter
  * Uploading after having validated the settings with a successul print job with BQ PLA
  * No skipped steps noticed on any of the stepper motors
  * Currently, the only noise being produced is from the extra 120mm side fan on the bottom (custom mod) and the 40mm extruder fans included in the design

