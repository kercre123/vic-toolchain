# vic-toolchain

This is a toolchain for the Anki Vector robot built with crosstool-ng.

arm-linux-gnueabi includes GCC 10.5.0 and some debug tools. It is built for an armeabi, glibc 2.19, and Linux kernel version 3.16 environment (all older than what is in Vector).
I have sucessfully built the TensorFlow Lite C API with it (r2.8).

arm-linux-gnueabihf include GCC 13. It is built for glibc 2.28 and kernel 3.16. This is not compatible with regular Anki vector software.
