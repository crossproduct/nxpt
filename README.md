nxpt
====

A CLI tool to flash, restore, and various other provisioning functions on Android based hardware.

###usage: nxpt \<command\>
 |  |
--- | ---
gohome | Direct all connected clients to launch their default / configured home launcher MAIN activity.
oemunlock	| Unlock the bootloader of all connected devices that have been launched into the bootloader mode.
oemlock | Lock the bootloader of all connected devices that have been launched into the bootloader mode.
provision [\<directory\>] [\<version\>] | flash all connected devices with fastboot
restore | Restore the device back to factory status (4.4.4 default)
		
##License
The MIT License (MIT)

Copyright (c) 2014 Chris Ross , crossproduct iNc.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
