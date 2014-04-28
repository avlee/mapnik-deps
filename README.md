# mapnik-deps

The include files, libs and dlls that required for building mapnik on windows with msvc2010.

All projects that mapnik depend on are builded with msvc2010 sp1 on 64-bit windows 7.

Usage:

    git clone https://github.com/avlee/mapnik-deps.git
    
    unpack.bat

The unpack.bat cmd is used to extract the gdal.lib file from the 7z archive file, because github's file size limited to 100 MB.