mars-app
========

The MARS MIPS Simulator/IDE packaged as an OSX app for easy installation/use. 
Packaging MARS as an app also gives it a more native feel 
(for example, menus are located in the menubar instead of in the MARS window).

All actual development information can be found on the author's page here: 
http://courses.missouristate.edu/KenVollmar/MARS/index.htm 

Installation:
-------------

To install, run the following line in terminal. Once it completes, MARS.app will be 
located in /Applications.

    curl -L https://github.com/sagark/MARS-app/archive/master.zip > master.zip && unzip master.zip -x README.md && mv MARS-app-master/MARS.app /Applications/ && rm -rf MARS-app-master && rm master.zip

If you'd like to be able to access MARS at the command line (using `mars`), 
add the following to `.bashrc` (or your equivalent):

    alias mars="/Applications/MARS.app/Contents/MacOS/JavaApplicationStub"

If you're having an odd issue while installing, please ensure that the above 
lines were correctly copied into Terminal.

License: 
--------

The original license applies, I simply packaged it as an app:

Copyright (c) 2003-2008, Pete Sanderson and Kenneth Vollmar

Developed by Pete Sanderson (psanderson@otterbein.edu)
and Kenneth Vollmar (kenvollmar@missouristate.edu)

Permission is hereby granted, free of charge, to any person obtaining 
a copy of this software and associated documentation files (the 
"Software"), to deal in the Software without restriction, including 
without limitation the rights to use, copy, modify, merge, publish, 
distribute, sublicense, and/or sell copies of the Software, and to 
permit persons to whom the Software is furnished to do so, subject 
to the following conditions:

The above copyright notice and this permission notice shall be 
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, 
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF 
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. 
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR 
ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF 
CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION 
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

(MIT license, http://www.opensource.org/licenses/mit-license.html)
