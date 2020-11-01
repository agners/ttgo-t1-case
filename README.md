# FreeCAD case for LilyGO TTGO T1

Case for LilyGO TTGO T1 with Home Assistant logo. A parameteric design
created with FreeCAD 3D parametric modeler.

The case allows to mount a sensor module on a 4-pin 2.54mm pin header on
its side.

![TTGO T1 Case closed](https://github.com/agners/ttgo-t1-case/blob/master/case-closed.png?raw=true)

![TTGO T1 Case open](https://github.com/agners/ttgo-t1-case/blob/master/case-open.png?raw=true)

## Known Caveats

* Tight fit: The PCB fits rather tightly in the case
* Tight lid: The lid sits rather tight as well and is somewhat hard to open
* Printing the Home Assistant logo is hard: Slicer generate an extra circle for
  every node on the tree. I got better results by manually removing the circles
  in the G-code

## Built With

* [FreeCAD](https://www.freecadweb.org/)
* [LiliGO TTGO-T1](https://github.com/LilyGO/ESP32-TTGO-T1)

## License

This project is licensed under the MIT License - see the
[LICENSE](LICENSE) file for details

