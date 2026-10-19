# Keeb---Custom-Keyboard

What to Put In It
Your repo should document your entire build. As you work through the guide, keep it updated with:

README.md: a writeup of your project covering what you built, why, and what you learned

PCB files: your KiCad project (schematics, layout, Gerbers). To export from KiCad:
Open your project in KiCad and launch PCB Editor

Go to File → Fabrication Outputs → Gerbers (.gbr)

Select all layers (F.Cu, B.Cu, F.Silkscreen, B.Silkscreen, F.Mask, B.Mask, Edge.Cuts) and click Plot

Then click Generate Drill Files to export the .drl file

Zip the output folder and commit it alongside your .kicad_pcb and .kicad_sch files

bom.csv: your bill of materials, the list of every part you bought with the grant, saved as a CSV file in the repo

Case files: your Onshape exports for the case and plate. To export from Onshape:

In your Onshape document, right-click the part or assembly you want to export

Select Export

Choose STEP format, set units to mm, and click Export

Commit the exported files to your repo

Photos: progress shots and your finished build
