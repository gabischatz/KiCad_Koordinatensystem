# KiCad Page Template
Collection of KiCad templates
![github-small](https://github.com/gabischatz/KiCad_Koordinatensystem/blob/4bcd966a9d43a1e3082f7a0f7d1b35422138fb5b/drawing_sheet_template.png)
The picture shows the finished coordinate system and the position on the page template. Unfortunately, in KiCad 6 it is not yet possible to place the coordinate origin in the middle of the worktop! Therefore see the origin of the coordinates above, on the left, which is outside the worksheet (yellow).
I have the file name once in English and once in German. This is the same file.

## Installation Guide
- Install **KiCad 6.0**
- Clone the file into your Templates folder.
- Open KiCad -> 6.0 -> share -> kicad -> template
- Add `.lkicad_wks` files to KiCad in the Global Templates page
      - `coordinate_system.kicad_wks`
      - `Coordinate system.kicad_wks`


## Sources en
- https://github.com/gabischatz/KiCad_Koordinatensystem/blob/4bcd966a9d43a1e3082f7a0f7d1b35422138fb5b/coordinate_system.kicad_wks
## Sources de
- https://github.com/gabischatz/KiCad_Koordinatensystem/blob/4bcd966a9d43a1e3082f7a0f7d1b35422138fb5b/Koordinatensystem.kicad_wks

## description
- After installation, go to the PCB editor and double click on the desktop frame.
 ![github-small](https://github.com/gabischatz/KiCad_Koordinatensystem/blob/4bcd966a9d43a1e3082f7a0f7d1b35422138fb5b/drawing_sheet.png)
- Now the worksheet wizard opens and with one click, see red arrow, you can select the worksheet you just saved.
 ![github-small](https://github.com/gabischatz/KiCad_Koordinatensystem/blob/4bcd966a9d43a1e3082f7a0f7d1b35422138fb5b/Select_character_sheet.png)
- On the next picture you can see how I drew a circle from the center and declared this as the board boundary.
 ![github-small](https://github.com/gabischatz/KiCad_Koordinatensystem/blob/4bcd966a9d43a1e3082f7a0f7d1b35422138fb5b/PCB_editor.png)
- Finally, you will see the finished board. Now select everything and use the lock to lock the components.
 ![github-small](https://github.com/gabischatz/KiCad_Koordinatensystem/blob/4bcd966a9d43a1e3082f7a0f7d1b35422138fb5b/PCB_board.png)
- You now have the option to reload your original worksheet as described above and fill in the label. Now mark the board again and move it to the middle of your worksheet. There is a query as to whether the locked elements should be moved. Click Ignore Ban.
 ![github-small](https://github.com/gabischatz/KiCad_Koordinatensystem/blob/1b1093789839415f0658d76ab4b7893a8a09694b/Ignore_Ban.png)
- Don't forget to save your project! **:)**

## LICENSE
https://github.com/gabischatz/KiCad_Koordinatensystem/blob/4bcd966a9d43a1e3082f7a0f7d1b35422138fb5b/LICENSE
