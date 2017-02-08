# xtool
Build a cross compiler on noop Linux.

Pass a machine triplet as an argument.

Example:

EXTRA_GCC_OPTIONS="--with-arch=armv7-a --with-float=hard --with-fpu=neon-vfpv4" ./xtool arm-linux-gnueabihf
