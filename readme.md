# Rtools Testing

Experimental toolchains and libraries used for the ucrt64 compilers in rtools40.

## Details

This reposity has few experimental updates for [rtools-packages](https://github.com/r-windows/rtools-packages), mainly for UCRT support:

 - Latest git version of mingw-w64-{headers,crt} (many ucrt related fixes)
 - Static build of mingw-w64 winpthreads 
 - Latest stable version of GCC-10
 - Recent version of ICU.
 - Recent version of tcl/tk

Currently we only deploy these new versions for the new ucrt64 toolchains, to avoid potential changes in behavior for the existing mingw32 and mingw64 toolchains in rtools40.
