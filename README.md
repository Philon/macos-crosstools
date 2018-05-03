# arm-mac-linux-gnueabihf
**GCC Version**: 6.3.0  
**GDB Version**: 7.12.1(with gdbserver)  
**Build**: MacBook Pro late 2016 with macOS 10.13.4  
**Host**: macOS 10.13+  
**Target**: ARMv7(hardware float)  
**Language**: c/c++ 

## GCC Configure
`/Volumes/buildcc/.build/src/gcc-6.3.0/configure --build=x86_64-build_apple-darwin17.5.0 --host=x86_64-build_apple-darwin17.5.0 --target=arm-mac-linux-gnueabihf --prefix=/Volumes/buildcc/x-tools/arm-mac-linux-gnueabihf --with-sysroot=/Volumes/buildcc/x-tools/arm-mac-linux-gnueabihf/arm-mac-linux-gnueabihf/sysroot --enable-languages=c,c++ --with-cpu=cortex-a9 --with-fpu=neon --with-float=hard --with-pkgversion='crosstool-NG crosstool-ng-1.23.0' --enable-__cxa_atexit --disable-libmudflap --disable-libgomp --disable-libssp --disable-libquadmath --disable-libquadmath-support --disable-libsanitizer --disable-libmpx --with-gmp=/Volumes/buildcc/.build/arm-mac-linux-gnueabihf/buildtools --with-mpfr=/Volumes/buildcc/.build/arm-mac-linux-gnueabihf/buildtools --with-mpc=/Volumes/buildcc/.build/arm-mac-linux-gnueabihf/buildtools --with-isl=/Volumes/buildcc/.build/arm-mac-linux-gnueabihf/buildtools --enable-lto --enable-threads=posix --enable-plugin --enable-gold --with-libintl-prefix=/Volumes/buildcc/.build/arm-mac-linux-gnueabihf/buildtools --disable-multilib --with-local-prefix=/Volumes/buildcc/x-tools/arm-mac-linux-gnueabihf/arm-mac-linux-gnueabihf/sysroot --enable-long-long`