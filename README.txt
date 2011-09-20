== Windows ==

Project is created by Visual C++ 2010 Express SP1. Download URL:
http://www.microsoft.com/visualstudio/en-us/products/2010-editions/visual-cpp-express
http://www.microsoft.com/download/en/details.aspx?id=23691

To build gstdirectsoundsink, DirectX 9.0 SDK October 2004 Update
must be unpacked (not installed) in dxsdk_oct2004. Download URL:
http://www.microsoft.com/download/en/details.aspx?id=19320

To build libvpx, vsyasm must installed. Download URL:
http://yasm.tortall.net/Download.html

== Linux (obsoleted) ==

$ cd unix
$ make

== Mac (obsoleted) ==

Build on 10.5 Prefered

pkg-config and yasm from MacPorts are needed.

$ cd macosx
$ make release (or debug)
