XTerm Color Tests
-----------------
When porting some code from Linux to SunOS, I noticed some differences in the color scheme of the output as a result of xterm incompatibilities. This was more evident when using [GNU Screen](http://www.gnu.org/software/screen/). In anticipation of my recurring need for this code, I put it in as a repository.

## The 256 color mode of xterm
[Wolfgang Frisch](mailto:xororand@unfoog.de) discussed issues related to xterm 256 color mode at: [http://www.frexx.de/xterm-256-notes/](http://www.frexx.de/xterm-256-notes/)

### 16 Colors Test (bash script)
* **Code**: colortable16.sh
* **Author**: Wolfgang Frisch \<xororand@unfoog.de>
* **License**: GPL v3+

### 256 Colors Test (perl script)
* **Code**: 256colors2.pl
* **Author**: Thomas Dickey \<dickey@his.com>
* **License**: MIT

Availability
------------
Appearntly, the above code is package as part of a Debian package called [colortest](http://packages.debian.org/search?keywords=colortest) with a python alternative named [colortest-python](http://packages.debian.org/search?keywords=colortest-python)
