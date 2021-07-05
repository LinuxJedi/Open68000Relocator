# Open68000Relocator
Open68000Relocator is an Open Hardware adapter PCB that changes the orientation of a 68000 DIP CPU.

![Board](doc/render-top.png)

**Note**: This project requires KiCad 5.99 or higher.

## Summary
This is based on [SukkoPera's](https://github.com/SukkoPera/Open68000Relocator) awesome 68000 relocator. I modified it to make it easier to fit on some motherboards and better support for PiStorm. It has the following changes:

* Hole for the capacitor C816 in rev 6 and 8 Amiga 500s (and Plus).
* Re-routed 4-layer with length adjusted traces for stability with PiStorm on some Amigas.
* Better power traces, useful for PiStorm.
* Some style changes.
* A couple of decoupling capacitors (2x 100nF 0603).

## License
Open68000Relocator is Open Hardware released under the GNU General Public License (GPL) v3. If you make any modifications to the board, **you must** contribute them back.

Open68000Relocator is provided to you ‘as is’ and without any express or implied warranties whatsoever with respect to its functionality, operability or use, including, without limitation, any implied warranties of merchantability, fitness for a particular purpose or infringement. We expressly disclaim any liability whatsoever for any direct, indirect, consequential, incidental or special damages, including, without limitation, lost revenues, lost profits, losses resulting from business interruption or loss of data, regardless of the form of action or legal theory under which the liability may be asserted, even if advised of the possibility or likelihood of such damages.

