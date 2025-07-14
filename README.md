
# OFW_Payload

OFW_Payload is a fork of Lockpick_RCM to utilise its "Reboot (OFW)" function. It is the same as the one in hekate -> Reboot -> OFW. I made it because I wanted
a payload to start OFW. Hekate doesn't allow true OFW in its launch options (only stock via atmosphere).

It should work on Switches **without AutoRCM**. It is primarily for modchipped Mariko V2 Switches.

I was only able to test it on my picofly-modchipped Mariko.

## Example config for hekate

This requires the OFW.bin to be placed under "bootloader/payloads/"!
```
[OFW]
icon=bootloader/res/ofw.bmp
payload=bootloader/payloads/OFW.bin
```

## Massive Thanks to CTCaer !

Like Lockpick_RCM, this project owes a lot to [Hekate](https://github.com/CTCaer/hekate), and special thanks go to **CTCaer** for his valuable advice, expertise, and humor throughout the development process.

## Massive Thanks to Kofysh !

OFW_Payload uses [Kofysh's Lockpick_RCM](https://github.com/Kofysh/Lockpick_RCM) as its base.

## 📜 License

OFW_Payload is licensed under the **GPLv2**.
