These standard C headers are missing from earlier versions of Visual Studio.


dirent.h is already present in:

minorGems/io/file/win32



stdint.h from here:

http://msinttypes.googlecode.com/svn/trunk/stdint.h



VisualStudio Linker/Input/Additional Dependencies setting must include:

comctl32.lib;wsock32.lib;steam_api.lib