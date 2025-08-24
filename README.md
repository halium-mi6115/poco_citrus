## Project Status

Beta. Still need more patches for a few components


## Features & Usability

### Actors
- [x] Manual brightness
- [x] Vibration

### Camera
- [x] Flashlight
- [ ] Photo
- [ ] Video
- [ ] Switching between cameras

### Cellular
- [x] Single SIM functionality
- [ ] [Dual SIM functionality](https://github.com/halium-mi6115/poco_citrus?tab=readme-ov-file#dual-sim-functionality)
- [x] Carrier info, signal strength
- [x] Data connection
- [x] [Incoming, outcoming calls](https://github.com/halium-mi6115/poco_citrus?tab=readme-ov-file#volte)
- [ ] MMS in, out (not tested)
- [ ] Pin unlock
- [x] SMS in, out
- [ ] Change audio routings (not tested)
- [ ] Voice in-call (not tested)
- [ ] Volume control (not tested)

### Endurance
- [ ] 24+ hours battery lifetime (not tested)
- [ ] 7+ days stability (not tested)

### GPU
- [x] Boot into UI
- [x] Hardware video playback

### Misc
- [x] Waydroid
- [ ] AppArmor patches
- [x] Battery percentage
- [x] Offline charging
- [x] Online charging
- [x] Recovery image
- [x] Reset to factory defaults
- [x] SD card storage
- [x] RTC time
- [x] Shutdown / Reboot
- [ ] Wireless external monitor (not tested)

### Network
- [x] Bluetooth
- [x] Flight mode
- [x] FM radio
- [x] Hotspot
- [x] Wi-Fi

### Sensors
- [ ] Automatic brightness (not tested)
- [ ] Fingerprint reader
- [x] [GPS](https://github.com/halium-mi6115/poco_citrus?tab=readme-ov-file#gps)
- [ ] Proximity (not tested)
- [x] Rotation
- [x] Touchscreen
- [ ] Double tap to wake (not tested)

### Sound
- [x] Earphones
- [x] Loudspeaker
- [x] Bluetooth headphones
- [x] Microphone
- [x] Volume control

### USB
- [x] MTP access
- [x] SSH access

## Global issues

The issues listed below are present in most or all of the devices depending on the technology they are built on.

### Dual SIM functionality
- Cellular data is not available on SIM 2 when two are inserted.
- All devices on Focal
- [More info](https://gitlab.com/ubports/development/core/lomiri-indicator-network/-/issues/101)

### VoLTE
- Calling over VoLTE is not supported, please check that this is not a requirement in your country.
- Halium and Legacy ports
- [More info](https://gitlab.com/ubports/ubuntu-touch/-/issues/1335)

### GPS
- Devices may take longer than usual to get the first GPS fix because of missing Assisted GPS support.
- All devices
- [More info](https://gitlab.com/ubports/development/core/location-service/-/issues/13)
