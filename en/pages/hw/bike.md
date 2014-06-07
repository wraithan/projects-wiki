# Bike Computer

## Summary

I have a few friends who experiment with electronics on their bikes. Most of
them being function/artistic lights, and that is generally the extent they go
to. Other friends of mine go out and buy things like the high end Garmins. They
have some cool data but it is all pushed to the proprietary website before it is
able to be downloaded.

I wanted to build a bike computer that can do most of what those Garmins can,
but I want to control my own data. On top of that, I'd like to be able to do
artistic stuff with my bike, and the first step is having a computer on there to
control it. My bike computer project is mostly taking several off the shelf
solutions to problems and tying them together to gather all the data I need.

## Parts List

* [Teensy 3.0](parts/teensy.md)
* [Sparkfun OpenLog](parts/openlog.md)
* [Adafruit Ultimate GPS](parts/gps.md)
* [Hall Effect Sensors](parts/hall.md)
* [DHT 11](parts/dht.md)
* [Super Bright White LEDs](parts/led.md)
* [Super Bright Red LEDs](parts/led.md)
* [Log Light Sensor](parts/light.md)
* [Polar Wireless Heart Rate Sensor](parts/hr.md)

## Progress

- [x] Research GPS boards
- [x] Research SD card boards
- [x] Get RTC on the Teensy working
- [ ] Get OpenLog setup to be able to push data to it
- [x] Get current location using the GPS board
- [ ] Come up with a method of logging to the OpenLog
- [ ] Come up with a way of dumping data off of the computer
- [x] Experiment with USB OTG with Android
- [ ] Research BLE chips
- [ ] Design a case for front and back lights that includes a diffuser
- [x] Get HR sensor working
- [ ] Write a server for hosting/display data from this project
- [ ] Use light sensor to automatically turn on lights
- [ ] Decide on real time data display method
- [ ] Decide on input methods
