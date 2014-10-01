#(cd build && ../llvm/configure --enable-libcxx --with-gcc-toolchain=/opt/rh/devtoolset-2/root/usr/bin/gcc --disable-assertions --enable-optimized && make )
#(cd build && ../llvm/configure --with-gcc-toolchain=/opt/rh/devtoolset-2/root/usr/bin/gcc --disable-assertions --enable-optimized && make )
#(cd build && ../llvm/configure --disable-assertions --enable-optimized && make )
(cd build && ../llvm/configure --enable-libcxx --disable-assertions --enable-optimized && make )

