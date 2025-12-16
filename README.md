# Jcw Drafting's Big60
Modified Modix big60 Marlin firmware package to work with Octopus Pro 1.0, Includes sensor-less homing, proper bed tilt calibrating, separate drivers for all stepper motors and direct PID control for the hot bed.

Things to note:
- When Compiling this firmware for your machine, make sure the right U8glib Library is used for the Full Graphics Smart Controller as anything but the right one will output the secrets of the Matrix to the display!
- Take care when rewiring the z axis stepper motors as too many wiring mistakes can warp your frame or hotbed. These can happen when A+ A- B+ B- wires are around the wrong way. Compare the pinout of your motherboard to the pinout of the stepper motor and ensure you get the correct wiring.
- This modix machine neglects to earth the hotbed. Ensure an earthing wire runs from the wall power input in the PID box on the bottom to the hotbed either with a bolt directly through the bed or clamped. It may be tingly to touch or cause circuit breaker tripping if not appropriatly earthed.
- In order to utilise the existing box to suit a different motherboard, you may need to make new standoffs in the box to suit the hole patterns.

Feel like buying me a coffee?

https://buymeacoffee.com/JakeCharles

<img width="400" height="400" alt="bmc_qr" src="https://github.com/user-attachments/assets/d2e76c7e-092e-4391-9aa6-db01fff8afe9" />


