# STHAX
> [!NOTE]
> this expolit currently does not allow for homebrew enabling,but I am currently investigating. this expolit also does not brick your device at all nor needs a jailbroken device to do and rather happens due to a flaw with the micro usb that can be expolited.

Whats is STHAX? you may ask, is a method that allows for booting into rcm mode on the Ti 84 Plus CE (ce & python versions) via a expolit found in the charging port,however it does have limits. entering the rcm mode can be exited with the on button,and if plugged into anything so down below is the guide!.


# Tutorial
what you need is a staple(you have to manually seprate it into a individual staple),the ti 84 plus ce (or python,both work) and access to the reset button

1. turn off the device
2. take the staple and insert it into the 5th pin (count from left to right,the 5th & 4th pin work but do NOT do this with it plugged in to a device and the 4th pin might make it worse)
3. okay,with the staple in HOLD down the reset button/or press it, now if you pressed it it'll say vaildating os and will go to a black screen. this is expected,if you held down the reset button it should stay on a black screen. if so,your in.

   # How does this work?
   I figured out that doing this with the reset button held down actually causes a different state, See when you insert the staple into the 5th pin,it kinda confuses the CPU into forgetting which mode its actually supposed to be in. due to this it panicks and ironically tricks the calculator into booting into a mode that Texas Instruments(TI) never intended for you to manipulate in such a way because software wise, it is now in limbo because its stuck inbetween a ram reset & a OS boot. however the flash nor the os is actually corrupted by doing this so it does not brick your system at all. and ontop of this it would be hard for Texas Intruments to patch a low level expolit like this due to it not being a software based one at all and due to the fact that this expolit Works on Modern TI calculators that have a charging slot like this and have a power button. So ironically this could have Opened Pandora's Box level of Custom Firmware.
