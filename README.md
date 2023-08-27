# Top hat mod for Voron 2.4

Please read the most up-to-date instructions here: https://remake.ai/blog/voron-2-top-hat-mod/.

Voron 2.4 print volume height comes up short of the advertised 350mm (or 300mm, 250mm) - quite a bit -
especially when using the StealthBurner extruder and/or PTFE filament tubing.
Here is a "top hat" volume height extension that you can 3D-print and mount on top of
your Voron 2.4 (or Voron 2.4r2). Ny setup's max Z went up from 310mm to 355mm -
without changing vertical rails!

This mod sits between your Voron 2 frame and its top see-through plastic sheet. Specifically,
the top hat fits into the existing 2020 aluminum extrusion slots on top of your Voron2 - and
reproduces 2020 extrusion slots (in plastic) on its own top, so you can re-affix the see-through
plastic sheet.

Word of caution - when **printing above ~310mm**, your **minimum Y must be at least 20mm** (vs. zero),
otherwise Stealthburner can collide with the frame.

![PXL_20230825_075201542](https://github.com/kaiaai/voron2_top_hat/assets/33589365/5595a44c-cfe3-4874-a491-0a297c360bcf)

![Top hat Voron 2 4 350mm](https://github.com/kaiaai/voron2_top_hat/assets/33589365/3004e809-f377-4d45-ac5f-bf9cd43cd981)

The top hat's exhaust opening has the same size and position as the one on the "standard" Voron 2.
You can try mounting a Voron 2 exhaust filter proper or affix one of the many available exhaust
cover plates.

## Installation instructions
- in the slicer software, place each half-panel vertically on the print bed. The half-panel's slot should be facing up.
- 3D-print the half-panels. I recommend using PETG.
- assemble 8 half-panels into 4 panels - one front, one rear and two side panels.
Take two mating sub-panels (e.g. one `front left` and `front right`) and slide the
slotted end of one of the half-panels into the mating slotted end of the other half-panel. It's ok to gently pound the
half-panels to make them fit together. If the fit is too tight, try sanding the slot a little with a piece of sandpaper.
- take the top see-through plastic sheet off your Voron 2 extrusion frame
- place the four just-assembled on top of your Voron 2 frame. The top hat should sit nicely
in the grooves of your 2020 extrusions.
- use 8 M4x30 screws - 4 in the front and 4 in the back - to bolt the four panels together.
Don't overtighten when driving the screws into the plastic.
- choose a cover plate - see below - and 3D-print it
- mount your cover plate in the back of the top hat
- run your filament and/of PTFE tube and/or CAN bus wiring (if you have one) - whatever
you are using for your setup. I do recommend using PTFE and CAN bus.
- re-affix the see-through sheet top the top hat's 2020 "extrusions". Be careful not to
damage the "extrusions" plastic.
- edit your `printer.cfg` to update the max Z position

## Choice of exhaust covers or filter
These are just suggestions.

- you can try affixing a Voron 2 exhaust filter
- you can use [this](https://mods.vorondesign.com/detail/sChDLllFG34KYroxSym6MQ) exhaust plate
- or you can use [this](https://mods.vorondesign.com/detail/rBsQWXI7IQxnZUyVwpjH3A) exhaust plate
with a BTT filament sensor attached to it
- I recommend the `Exhaust cover BTT-PTFE-CAN-bus` plate in this repo. This plate has a BTT
filament sensor mount as well as an elongated knob that prevents your PTFE tube from sagging.
The PTFE tube slides through the knob. You can also secure your CAN bus cable to the knob.

![Exhaust cover BTT CAN bus](https://github.com/kaiaai/voron2_top_hat/assets/33589365/3a2cb880-4afc-4c4f-a00a-815d5e52c19a)

## Top hat photos
![PXL_20230825_075209553](https://github.com/kaiaai/voron2_top_hat/assets/33589365/f3dc9e91-d105-40a6-a2f1-a8022f34e780)
![PXL_20230825_075243794](https://github.com/kaiaai/voron2_top_hat/assets/33589365/76d7025a-7e54-46d3-bcb3-f987aa8c6014)
![PXL_20230825_075301291](https://github.com/kaiaai/voron2_top_hat/assets/33589365/b1360762-47f1-4494-904e-cb7248e99781)

Happy 3D printing!
