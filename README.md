# Meta-iOS-Developer
## Anatomy of an iOS app
### UI application
Starting point.Responsible for initializing application window. Every ios app has one instance.
### UI application delegate
Maintains overall shared behavior of the app.Can be referred to as root of the app. Allows you to register
for any required services at launch time.
### User Defaults
#### UIDocument
interface for managing documents and content
### View Controller
Manages a view hierarchy for your app. Manages a single view at a time. Can be used to manage a view

## Simulators
examples BlueStacks, Genymotion, iOS Simulator, Android Emulator, Wine, Appetize.io, Nestopia(Nitendo games simulator)
### iOS Simulator
Simulates iOS devices on your computer. Can be used to test apps without having to own a device.
## Mobile CPU Architecture
### ARM
Advanced RISC Machine. Reduced Instruction Set Computer. 32-bit and 64-bit.
RISC is a CPU design strategy based on the insight that simplified instructions can provide higher performance if this simplicity enables much faster execution of each instruction. 
RISC processors typically have fewer than 100 instructions.
RISC processors typically execute instructions in one clock cycle by using pipelining.
RISC processors typically use a technique called register windowing to speed up procedure calls.
RISC processors typically execute instructions in one clock cycle by using pipelining.
Optimized for power consumption.
examples: ARMv7, armeabi
### ARM64
64 bit extension of ARM. 64-bit ARM architecture is called AArch64.
Gradually replacing ARMv7 and becoming the standard for new devices.
### x86
Not quite as power efficient as ARM. 32-bit and 64-bit.
More sophisticated than ARM. examples: x86, x86_64 x86abi
