This is the Klipper config for my 350mm² Voron 2.4r2, built September through November 2022 (cerial number V2.4465).

![Voron Logo](/images/voron_logo.png)  ![Built Not Bought](/images/built_not_bought.png)

The purpose for this repo is mainly for backup, change management, and safer editing.  I've chosen to make this repo public in case anything in here might be useful to someone else.  Thus, it's ~~probably~~ definitely **not** a good idea to just blindly copy anything as-is.  ***Use at your own risk.***

## Goals
* A printer that is used for making functional parts
* High quality printing is more important than speed
* Reliability and consistency -- just Print & Walk Away™

## Customizations
This printer was built almost completely according to Voron Design spec, with the following customizations:

#### Hardware
* [Manta M8P + CB1](https://biqu.equipment/products/manta-m4p-m8p) by Big Tree Tech
* [16MP 105° USB Camera](https://www.arducam.com/product/arducam-16mp-wide-angle-usb-camera-for-laptop-1-2-8-cmos-imx298-mini-uvc-b0268/) by ArduCam
* [270° Hinge - Parametric](https://www.teamfdm.com/files/file/50-270%C2%B0-hinge-parametric/) by [Chris Gonzales](https://github.com/chrisgonzales)
* [Matched Height Kinematic Kit](https://mandalaroseworks.com/products/matched-height-kinematic-kit) and [Kinematic Center Brace](https://mandalaroseworks.com/products/kinematic-center-brace-for-voron-2-4) from Mandala Rose Works
* [5.5-inch Capacitive Touch AMOLED Display](https://www.waveshare.com/5.5inch-hdmi-amoled.htm) from Waveshare with [a skirt mount](https://www.teamfdm.com/files/file/174-waveshare-55-inch-hdmi-amoled/) by [Dr. Stephan Schimanski](https://github.com/sttts)
* [Rainbow Barf Logo LED for StealthBurner](https://github.com/tanaes/whopping_Voron_mods/tree/main/LEDs/Rainbow_Barf_Logo_LED) by [Jon Sanders](https://github.com/tanaes)
* NeoPixel (SK6812) RGBW tape for chamber lighting, using [LED Strip Holder for Voron 2.4](https://www.thingiverse.com/thing:4933314) by [Kridcha Autchaborriruk](https://www.thingiverse.com/funfunboy/designs)

#### Klipper
* [LED Effects](https://github.com/julianschill/klipper-led_effect/blob/master/docs/LED_Effect.md) by [Julian Schill](https://github.com/julianschill)
* [Rainbow Barf macros](https://github.com/tanaes/whopping_Voron_mods/blob/main/LEDs/Rainbow_Barf_Logo_LED/Code/stealthburner_led_effects_barf.cfg)  for LED Effects module by Voron Discord user **ChristianN**

#### Others
* Using [KIAUH](https://github.com/th33xitus/kiauh) by [th33xitus](https://github.com/th33xitus) to manage Klipper, Moonraker, Fluidd, etc.
