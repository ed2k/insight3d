<<<<<<< HEAD
INSIGHT 3D NG, VERSION 0.3.3
----------------------------

COMPILING UNDEX LINUX
---------------------

To compile insight3dng under Linux, you must have the following libraries: 

	- opencv
	- opengl
	- SDL
	- libxml2 (to parse xml files)
	- lapack 
    - blas (min. 1.2-8 (Debian/Ubuntu))
	- libgtk+-2.0

And this should be pretty much everything. Also, pkg-config should know about those libraries. 

Makefile and source code is in the "insight3d" subdirectory. There's no configuration, just execute "make" in the "insight3d" subdirectory. 

COMPILING ON WINDOWS
--------------------

You'll need the same libraries. You'll need to setup the paths to include 
and bin directories of these libraries in Visual Studio. The project has been
compiled using Microsoft Visual C++ Express 2008.
=======
INSIGHT 3D, VERSION 0.3.2
-------------------------

COMPILING UNDEX LINUX
---------------------

To compile insight3d under Linux, you must have the following libraries: 

	- opencv (which is pretty standard computer vision toolkit)
	- opengl
	- SDL
	- freetype2
	- libxml2 (to parse xml files)
	- lapack and blas (to do some math)
	- libgtk+-2.0

And this should be pretty much everything. Some of them have additional 
requirements (opencv needs libpng, libtiff, ...) but these should be trivial. 

Also, pkg-config should know about those libraries. 

Makefile and source code is in the "insight3d" subdirectory.

COMPILING ON WINDOWS
--------------------

Please, refer to the file HOW_TO_BUILD_WINDOWS_VISUALSTUDIO.txt.
>>>>>>> c2ec70947a8825f310b6a792f55353d5193345ca
