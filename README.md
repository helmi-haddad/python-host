# python-host

# What is the SwitchBot opensource project?
[SwitchBot](https://www.switch-bot.com) is a smart IoT robot to mechanically control all your switches and buttons. You can control the bot by your smartphone app ([iOS](https://itunes.apple.com/app/switchbot/id1087374760?mt=8) or  [Android](https://play.google.com/store/apps/details?id=com.theswitchbot.switchbot), SwitchLink, or other platform based on our open APIs.

This project aims to provide a super light-weight solution to control your SwitchBot on [Raspberry Pi](https://www.raspberrypi.org)/[OpenWRT](https://openwrt.org/) or any other Linux based board.

# How to Install?

On Raspberry Pi.
You will need:
  -  A Raspberry Pi 3 or A Raspberry Pi 2 plugged with a [Bluetooth dongle](https://www.amazon.com/Plugable-Bluetooth-Adapter-Raspberry-Compatible/dp/B009ZIILLI/ref=sr_1_3?s=electronics&ie=UTF8&qid=1487679848&sr=1-3&keywords=bluetooth+dongle).
  -  A SwitchBot.
  -  An SD Card with a fresh install of Raspbian (tested against the latest build [2017-01-11 Jessie with Pixel](https://www.raspberrypi.org/downloads/raspbian/)).

Installation:
  -  Boot your fresh Pi and open a command prompt.
  -  Install the python pexpect library.
```sh
sudo apt-get install python-pexpect
```
  -  Clone this repo to the Pi.
```sh
git clone https://github.com/OpenWonderLabs/python-host.git
```
  -  run the python code.
```sh
cd python-host
sudo python switchbot.py
```
  -  Follow instructions to input the device number you want to control....

Enjoy:)

Share your words in our [community](http://community.switch-bot.com/).
