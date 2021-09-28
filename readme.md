# Rtools-ucrt

Toolchains and libraries for the ucrt64 compilers in rtools40.

## Details

This reposity has several extra package [rtools-packages](https://github.com/r-windows/rtools-packages) used only for the toolchains that target the UCRT:

 - Latest git version of mingw-w64-{headers,crt} (many ucrt related fixes)
 - Static build of mingw-w64 winpthreads 
 - Latest stable version of GCC-10
 - Recent version of ICU.
 - Recent version of tcl/tk

 We only deploy these for the new ucrt64 toolchains. All other ucrt packages are built from [rtools-packages](https://github.com/r-windows/rtools-packages) just like the mingw32 and mingw64 binaries used by Rtools 4.0 and up.
