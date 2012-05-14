XTerm Color Tests
-----------------
When porting some code from Linux to SunOS, I noticed some differences in the color scheme of the output as a result of xterm incompatabilities. This was more evident when using [GNU Screen](http://www.gnu.org/software/screen/).

## The 256 color mode of xterm
[Wolfgang Frisch](mailto:xororand@unfoog.de) discussed issues related to xterm 256 color mode at:

[http://www.frexx.de/xterm-256-notes/](http://www.frexx.de/xterm-256-notes/)

The following scripts were used to test terminal colors:
### 16 Colors Test (bash script)
* **Code**: colortable16.sh
* **Author**: Wolfgang Frisch \<xororand@unfoog.de>
* **License**: GPL v3+

### 256 Colors Test (perl script)
* **Code**: 256colors2.pl
* **Author**: Thomas Dickey \<dickey@his.com>
* **License**: MIT
