ProgArm-Hardware
================

**NB! This project is in active development and things are changing all the time.**

This repository contains only schematic and PCB files. Schematic PDF and Gerber files are attached to every [release](https://github.com/ProgArm/ProgArm-Hardware/releases).

You can find other files used in ProgArm project [in other repositories](https://github.com/ProgArm). 

Contributing
------------
If you have found a bug, please consider creating an [issue](https://github.com/ProgArm/ProgArm-Hardware/issues). If you have a question, please [ask it on our website](http://progarm.org/Ask).


Please set up these [filters](http://git-scm.com/book/en/Customizing-Git-Git-Attributes) before commiting to this repository:
```
git config --global filter.cleansch.clean "sed 's/^Date.*$/Date \"\"/'"
git config --global filter.cleanlib.clean "sed 's/^\(EESchema-LIBRARY Version [^ \\t]*\).*$/\1/'"
git config --global filter.cleanpcb.clean "sed 's/\(host pcbnew \"\)[^\"]*/\1/'"
git config --global filter.cleanpro.clean "sed 's/^\(update=\).*$/\1/'"
```

License
-------
[According to](https://www.gnu.org/licenses/gpl-faq.html#GPLOtherThanSoftware) Free Software Foundation, GPL license can be applied to anything as long as we can clearly define 'source code'. In this repository all Kicad files are considered as source code files (*.sch *.kicad_pcb *.lib *.mod and several others). You must provide these files (or their modifications) if you are distributing any work based on this project. Please refer to [LICENSE](https://github.com/ProgArm/ProgArm-Hardware/blob/master/LICENSE) file for details.

    ProgArm is free hardware & software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.
