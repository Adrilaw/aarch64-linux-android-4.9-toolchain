# AArch64 GCC 4.9 Toolchain Setup

This project utilizes the Android AArch64 GCC 4.9 toolchain from the master branch to compile 64-bit ARM code. We have disabled deprecation warnings and removed any unnecessary build delays to ensure faster and smoother compilation.

## Features
- **AArch64 GCC 4.9**: Optimized for 64-bit ARM architecture.
- **No Deprecation Warnings**: Cleaner output during build by suppressing deprecated feature notices.
- **Build Delays Removed**: Faster compilation by eliminating unnecessary delays.

## Usage

1. **Clone the Toolchain**
   ```bash
   git clone https://github.com/Adrilaw/aarch64-linux-android-4.9-toolchain/ -b master
   
2. **Configure Build**
   ```bash
   export ARCH=arm64
   
   export SUBARCH=arm64
   
   CROSS_COMPILE=~/path/to/aarch64-linux-android-4.9-toolchain/bin/aarch64-linux-android-

4. **Compile**
   ```bash
   make -j$(nproc)
   
   
