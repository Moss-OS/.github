# Moss OS

Matt's Operating System Saga/Shenanigans? This is a play area to scratch an itch.  Ultimaty an OS for Raspberry Pi 3 and 4.

## Tools
1. [GNU Arm Embedded Toolchain](https://developer.arm.com/tools-and-software/open-source-software/developer-tools/gnu-toolchain/gnu-a/downloads)
   - ~~brew: `gcc-arm-embedded`~~ This is 32 bit only, 64bit not available on brew
   - Extract this [pre-built cross-compiler toolchain](https://github.com/thinkski/osx-arm-linux-toolchains/releases/download/8.3.0/aarch64-unknown-linux-gnu.tar.xz) into the build folder (should be located at `$PROJECT/build/aarch64-unkown-linux-gnu`)
2. [QEMU](https://www.qemu.org/download/)
   - brew: `qemu`
## Resources
- https://datasheets.raspberrypi.com/bcm2711/bcm2711-peripherals.pdf
- [Arm A64 Instruction Set Architecture](https://developer.arm.com/documentation/ddi0596/2021-12/?lang=en)
- https://jsandler18.github.io/ - This is old and targets 32bit machines
- https://github.com/s-matyukevich/raspberry-pi-os
- https://github.com/jsherman212/moss
- https://www.youtube.com/watch?v=pd9AVmcRc6U&list=PLVxiWMqQvhg9FCteL7I0aohj1_YiUx1x8&index=1
- https://github.com/raspberrypi/documentation/

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
