
Homebrew taps for ztracer (OSX 10.9)

OSX 10.9 moved from libstdc++ to libc++ as the default C++ library. 

Unfortunately, Intel PIN is compiled against libstdc++, which means that on Mac, dependencies
from homebrew don't work anymore (since you cannot link against both libraries).

This tap just contains the dependencies for ztracer, modified to link against libstdc++.
