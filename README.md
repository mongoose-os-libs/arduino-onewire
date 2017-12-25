# Arduino OneWire library for Mongoose OS

This library provides an Arduino compatibility layer for onewire by providing
an `OneWire.h` public header, so that one could pick an existing Arduino
program which uses onewire, throw it into the Mongoose OS application sources,
and ideally, it "just works".

Additionally, a mgos-specific API is available: for
[C](https://mongoose-os.com/docs/api/mgos_arduino_onewire.h.html) and
[mJS](https://mongoose-os.com/docs/api/api_arduino_onewire.js.html).
