These are the libraries (lbr), design rules (dru), and cam files (cam) used to create Pygmy boards.

---lbr---
Pygmy.lbr contains a collection of component footprints used on Pygmy boards. Some of them are copied from sparkfun.lbr, and others were created by project members specifically for the project.
PygmyBoards.lbr contains the Pygmy board specific parts such as board footprints, board art, etc.

---dru---
Dru file names appended with "(Production)" will mask vias less than 25mil in diameter.
Dru file names appended with "(Proto)" will never mask vias.

---cam---
Cam file names appended with "(Special silk)" will have the following layers on the produced silk gerbers: tTest/bTest, _tsilk/_bsilk, and Dimension.
Cam file names not appended with "(Special silk)" will have the following layers on the produced silk gerbers (if applicable): tPlace/bPlace, _tsilk/_bsilk, and Dimension.

Stencil.cam is used to generate files for solder paste stencils.
Board Checks.cam is used to check the silk layers on the boards