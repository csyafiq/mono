Follow this guide: 

https://peter1745.github.io/introduction.html

Rough steps:
Clone mono github
Build mono.sln
Take the x64 folder from build.


.NET (optional, but did it here)
Added it to lib as folder 4.5



===================================================
Actual files needed

Lib:
eglib.lib
libgcmonosgen.lib
libmini-sgen.lib
libmonoruntime-sgen.lib
libmono-static-sgen.lib
libmonoutils.lib
mono-2.0-sgen.lib
MonoPosixHelper.lib

DLLs:
mono-2.0-sgen.dll
MonoPosixHelper.dll

======================================================