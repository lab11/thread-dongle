Thread USB Dongle Firmware
==========================

Ensure the OpenThread submodule is initialized and checked out:
```
git submodule init
git submodule update
```

Install required dependencies and build the NCP firmware:
```
./build
```

Flash the firmware with a SEGGER jlink probe:
```
./flash
```
