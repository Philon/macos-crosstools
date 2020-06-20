# arm-mac-linux-gnueabihf
**GCC Version**: 8.3.0  
**GDB Version**: 8.2.1(with gdbserver)  
**Build**: MacBook Pro late 2016 with macOS 10.15.5  
**Host**: macOS 10.13+  
**Target**: ARMv7/Cortex-A15(hardware float)  
**Language**: c/c++ 

## GCC Configure

/Volumes/dev/philon/build/arm-mac-linux-gnueabihf/src/gcc/configure --build=x86_64-build_apple-darwin19.5.0 --host=x86_64-build_apple-darwin19.5.0 --target=arm-mac-linux-gnueabihf --prefix=/Volumes/dev/philon/x-tools/arm-mac-linux-gnueabihf --with-sysroot=/Volumes/dev/philon/x-tools/arm-mac-linux-gnueabihf/arm-mac-linux-gnueabihf/sysroot --enable-languages=c,c++ --with-cpu=cortex-a15 --with-fpu=neon-vfpv4 --with-float=hard --with-pkgversion='crosstool-NG 1.24.0' --enable-__cxa_atexit --disable-libmudflap --disable-libgomp --disable-libssp --disable-libquadmath --disable-libquadmath-support --disable-libsanitizer --disable-libmpx --with-gmp=/Volumes/dev/philon/build/arm-mac-linux-gnueabihf/buildtools --with-mpfr=/Volumes/dev/philon/build/arm-mac-linux-gnueabihf/buildtools --with-mpc=/Volumes/dev/philon/build/arm-mac-linux-gnueabihf/buildtools --with-isl=/Volumes/dev/philon/build/arm-mac-linux-gnueabihf/buildtools --enable-lto --enable-threads=posix --enable-target-optspace --enable-plugin --enable-gold --disable-nls --disable-multilib --with-local-prefix=/Volumes/dev/philon/x-tools/arm-mac-linux-gnueabihf/arm-mac-linux-gnueabihf/sysroot --enable-long-long

Thread model: posix
