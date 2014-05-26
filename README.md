Berliner Spargel Operating System
====

"Mein Deutsch ist nicht so gut, aber es ist Spargel zeit!"

BSOS is a minimal operating system for x86's 16-bit Real Mode by
Travis Goodspeed.  It was written on a Nokia N900 in Spargel zeit of
2012 to pass the time on Berlin's public transportation.  (Traditional
forms of entertainment such as busking and submitting to random bag
searches were considerably less fun.)

As BSOS contains nothing but a hex viewer and some simple I/O
routines, it's only useful for folks who need to get a 16-bit target
environment running immediately and for whatever reason won't run DOS.



package | Requirements
------- | -------------------------------------------
bcc     | Bruce's C Compiler for X86.
yasm    | X86 Assembler for the Boot Sector.
ld86    | X86 Linker.
bochs   | Slow but easy to tinker with X86 Emulator.
qemu    | Faster X86 emulator.
