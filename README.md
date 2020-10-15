# Quefrency V2 3D Keyboard Case
This is a 3D printable keyboard designed for the split Quefrency V2 PCBs. Included are Fusion 360 source files, STEP files, and STLs for printing immediately.

 There are some other designs out there but none that met my personal criteria, or were closed source/paid.


![Left Case with RGB light strip](images/case_left_RGB.jpg "Left Case with RGB light strip")

## Design Goals
I designed this with a few main goals in mind.
1. The Quefrency V2 has built in RGB LEDs for underglow support, and I wanted it to be able to have that shine through the sides of the case! This means having thin sections where translucent or white filament can be used.
2. No plate is required, to simplify the design and lower costs (no need to purchase plate add ons, and makes build a little less bulky).
3. I want to have some amount of tilting/tenting support, similiar to the ergodox legs, to customize the ergonomics.

## Required Hardware
* M3x8mm screws & nuts for securing pcb to case
* Optionally, additional M3 screws/nuts of 8mm in length or higher, to allow for custimizeable tilting/tenting.

## Additional Notes
* Currently only compatible with PCB configurations of `Left with 2x5 macro pad` and `Right 65%`
  * If there is interest I can update the designs to support the `Left without macro pad` and `Right 60%` configurations.
* The left half of the case is split into 2 files, `case_left_macro_bottom.stl` and `case_left_macro_top.stl`.
    * The PCB would be installed onto the bottom part first, and then the top part snaps in over it.