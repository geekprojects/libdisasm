libdisasm
===

This is a fork of [libdisasm]() that hacks^H^H^H^H^H adds in very basic
64 bit support. There's still a lot of work to do to fully support SSE and
other instructions that are standard in 64 bit instruction sets.

I have primarily been hacking this to support [Line](https://github.com/geekprojects/line).
It currently only builds under Mac OS but I will fix that soon.


API
---
The API for libdisasm is in libdisasm/libdis.h, which is installed in
$prefix/include after "make install".
