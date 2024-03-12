# PicoPendant
This is a general design based on the RP2040/Pico to support Pendant/MPG and Keypad Controllers for [grblHAL](https://github.com/grblHAL/core). I intend to generalize this design to support additional controllers and custom controlpanel designs. All are welcome to participate in this efforts, even if it is just to make suggestions.

The first Pendant to be supported is a fairly common one.  It has a number of variants supporting different numbers of Axes and at least 2 difference connection methods (D Sub 15 and bare wire). Bare wire is supported via a 2x10 pin header.  The D Sub 15 connector is likely to be more popular for obvious reasons.
![Pendant Image](https://github.com/phil-barrett/PicoPendant/blob/main/Renders/Images/pendant.png)

There are two designs: a) RaspPi Pico based and b) RP2040 microcontroller based.
![Pico Based](https://github.com/phil-barrett/PicoPendant/blob/main/Renders/V1/PR2040-MPG.png)
![RP2040 Based](https://github.com/phil-barrett/PicoPendant/blob/main/Renders/V2/PR2040-MPG.png)
