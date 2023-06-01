``` bash
python NDKPATH/build/tools/make_standalone_toolchain.py --arch arm --api 21 --install-dir=/tmp/my-android-toolchain

export GCC=/tmp/my-android-toolchain/bin/arm-linux-androideabi-g++
export CC=/tmp/my-android-toolchain/bin/arm-linux-androideabi-gcc
make -j 8
```
