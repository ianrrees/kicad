# Ian's KiCad Miscellany
Libraries, Footprints, etc that I find useful when working with [KiCad](http://kicad-pcb.org/).

Some contents here is my work, other parts come from other folks under similar licensing.

Some of the schematic symbols and footprints here are for parts that I would tend to buy from aliexpress. Most of those are more-or-less de-facto standard components - I'll try to put together a procurement guide here at some stage...

My intent here is to only share things which I have used successfully for making working PCBs, and which are not included in KiCad out of the box. The idea is that others should be able to use this repository to fill gaps in KiCad's offerings, with a similar level of confidence in making a successful board.

Usually, I buy PCBs from [DirtyPCBs.com](http://dirtypcbs.com/), so footprints will have their design rules in mind (0.006 inch minimum wire and space). These should be compatible with virtually any PCB manufacturer, and better quality DIY processes.

Pull requests are welcome.  In particular, I'd like to see any helpful stuff from here getting pulled in to official KiCad distribution channels!

## One way to use symbols and footprints
KiCad manages schematic symbols and PCB footprints separately, so these instructions contain the same steps duplicated for libraries and footprints:

 1. Clone this library to your computer - see [github's help](https://help.github.com/articles/cloning-a-repository/) for generic instructions
 2. Open KiCad's Symbol Library Editor, go to Preferences -> Manage Symbol Libraries...
 3. Pick the tab for either Global Libraries or Project Specific Libraries depending on your preference
 4. Click the Browse Libraries... button
 5. Navigate to the symbols subdirectory in the clone you made in step 1 and select the one(s) you want to add
 6. Now the symbols you want have been added, close the Symbol Library Editor
 7. Open KiCad's Footprint Library Editor, go to Preferences -> Manage Footprint Libraries...
 8. Click the Browse Libraries... button
 9. Navigate to the footprints subdirectory in the clone you made in step 1 and select the one(s) you want to add
 10. Done!
