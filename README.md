# Raspberry Pi Toolchain

Tuple Format:

    - Architecture
    - Vendor
    - Kernel
    - System

32-bit

```
        [l..X]   arm-rpi-linux-gnueabihf
            Languages       : C,C++
            OS              : linux-4.19.75-custom
            Binutils        : binutils-2.32
            Compiler        : gcc-linaro-7.4-2019.02-git
            C library       : glibc-2.30
            Debug tools     : gdb-8.3.1
            Companion libs  : expat-2.2.8 gettext-0.20.1 gmp-6.1.2 isl-0.21 libiconv-1.16 mpc-1.1.0 mpfr-4.0.2 ncurses-6.1 zlib-1.2.11
            Companion tools : autoconf-2.69 automake-1.16.1 libtool-2.4.6 m4-1.4.18 make-4.2.1
```

64-bit

```

        [l..X]   aarch64-rpi-linux-gnu
            Languages       : C,C++
            OS              : linux-4.19.75-custom
            Binutils        : binutils-2.32
            Compiler        : gcc-linaro-7.4-2019.02-git
            C library       : glibc-2.30
            Debug tools     : gdb-8.3.1
            Companion libs  : expat-2.2.8 gettext-0.20.1 gmp-6.1.2 isl-0.21 libiconv-1.16 mpc-1.1.0 mpfr-4.0.2 ncurses-6.1 zlib-1.2.11
            Companion tools : autoconf-2.69 automake-1.16.1 libtool-2.4.6 m4-1.4.18 make-4.2.1
```
