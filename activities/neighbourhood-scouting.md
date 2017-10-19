# NNK Activity: Neighourhood Scouting

## What you'll need

- Community Network Field Book
- Pencils
- Electrical Tape
- Raspberry Pi, Micro SD Card, Power Adapter
- Alfa AWUS036H 1000mW 1W 802.11b/g USB Wireless WiFi Adapter
- 9dBi Antenna
- USGlobalsat BU-353-S4 USB GPS Receiver
- Cat 5 Ethernet Cable
- Micro USB to USB Cable

## What to do

This kit includes all the parts to map (or "wardrive") the existing networks around your block. It uses Kismet, one of many network detecting programs out here. Most things are pre-configured, but detailed instructions for set up are in the online guide: dcwalker.ca/neighbour-net-kit/

1. Screw the long antenna onto the Alfa Wifi adapter, using the micro usb plug into the Raspberry Pi
2. Plug the GPS receiver into the Raspberry Pi
3. Make sure the SD Card is in the Raspberry Pi and power on! (For testing you can plug into the wall using the power adapter, but if you'll want to move you need a power pack).
4. Connect to your Pi from a computer! You'll need to have your Pi on the same wireless network to do so remotely, plugging your Raspberry Pi into your router with the ethernet cable might be the quickest. Instructions are online: https://www.raspberrypi.org/documentation/remote-access/
5. Once remotely connected to your pi, start Kismet: `sudo kismet` (you'll be prompted to enter your password). Instructions for getting started with Kismet are online.
6. Once you are getting expected results, time to measure networks near you, or pack up for scouting on the go! Use the electrical tape and to secure all the equipment together.

## Resources

- Wifi Wardriving: https://scotthelme.co.uk/wifi-wardriving/
