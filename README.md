# ergogen-keeb (placeholder name)
A 66-key wireless (BLE) ergonomic split mechanical keyboard generated with Ergogen. Heavily inspired by [keyzog's Kapl](https://github.com/keyzog/kapl) and [omkbd's Ergodash](https://github.com/omkbd/ErgoDash) keyboards.

This is a learning project. It's _very_ WIP and my first foray into PCB design and 3D modeling. Be warned, stuff in this repo will likely be broken and messy.

![Keeb top-view enclosed case sketch](/image/preview_case_both.svg "Keeb top-view enclosed case sketch")

## Project Overview
TODO

## Resources and Tools
- [Ergogen Ceoloide](https://ergogen.ceoloide.com/) - Ceoloide's web-based Ergogen that supports custom footprints
- [ceoloide's ergogen PCB footprints](https://github.com/ceoloide/ergogen-footprints) - Very useful to have this open in a separate tab to reference footprint parameters when using the web-based Ergogen
- [FlatFootFox's Let's Design A Keyboard With Ergogen v4](https://flatfootfox.com/ergogen-introduction/) - The de facto Ergogen guide.
- [easyeda2kicad](https://github.com/uPesy/easyeda2kicad.py) - For downloading LSCS (see JLCPCB parts) footprints and models for use in KiCad
- [KiCad to Ergogen footprint converter](https://kicad2ergogen.genteure.com/) - For converting the abovementioned footprints so they can be used in Ceoloide's Ergogen
- [kicad-druid](https://github.com/Cimos/kicad-druid) - KiCad design rules for JLCPCB and PCBWay, supports KiCad versions 8 through 10
- [KiCad ViaStitching Plugin](https://github.com/weirdgyn/viastitching) - Generates stitching vias over a fill zone.
- [SVG Viewer](https://www.svgviewer.dev/) - A web-based SVG viewer, used this to flip/mirror SVG files.
- [Shaper Utilities](https://marketplace.autodesk.com/apps/1caf9b83-5b54-4cab-b893-9c0b9e8f312a) - Autodesk Fusion plugin for exporting SVGs
- [Joric's nrfmicro wiki - Alternatives](https://github.com/joric/nrfmicro/wiki/Alternatives) - Wiki for Pro Micro Compatible alternatives including the SuperMini NRF52840
- [Fabrication-Toolkit](https://github.com/bennymeg/Fabrication-Toolkit) - KiCad plugin for generating gerbers, BOMs and component position files for JLCPCB