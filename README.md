# SeedPills
Create your own set of 3D-printed BIP39 bitcoin lottery pieces!

This code is compatible with OpenSCAD modeling software (https://openscad.org).

Users will need to manually modify the progam to indicate the number of vertical columns, horizontal rows, and the starting BIP39 seed word for their grid of Seed Pills.
Users may also change the pills dimensions.

Just open the seedpills.scad file with OpenSCAD Editor. In OpenSCAD, you will need to select "Preview" to view your generated grid:

<img src="/pictures/screenshot.png">

If you are satisfied with your grid, select "Render" and then "Export as STL" in OpenSCAD to obtain a 3D-printable file. (Note that rendering the model can be a lengthy process depending on the size of your model and the processing capability of your computer.)

Notes:
- The pills will be two-sided so take this into account when printing (a full set will be 1024 pieces)
- The pills are interlocked to help with bed adhesion, and so you can verify the words after removing them from the printer 
