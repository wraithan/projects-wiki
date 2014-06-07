# Media Keyboard

## Summary

I use fancy keyboards, those fancy keyboards tend to not have media keys for
switching music. As someone who listens to a lot of music it was a bit of a
problem. I found out that [Teensy](parts/teensy.md) was able to act as a
keyboard device, so I dived in. I had to patch the Teensy firmware to extend it
to handle media keys properly. Aside from that, this project had very few hang
ups.

## Parts List

* [Teensy 3.0](parts/teensy.md)
* [Rotary Encoder](parts/rotary.md)
* [Buttons](parts/buttons.md)

## Progress

- [x] Work out how to flash the teensy
- [x] Get a couple buttons hooked up to the teensy
- [x] Get rotary encoder working with the teensy
- [x] Send key strokes to my computer
- [x] Send media keys to my computer
- [x] Get teensy patches merged upstream
- [x] Move project to protoboard instead of breadboards
- [ ] Get PCB printed for the project
- [ ] 3d print a case for the project
