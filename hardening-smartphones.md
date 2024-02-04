# Hardening smartphones
In this blog I will show you how to harden your phone, make it more private and secure.

# Table of Contents
- [Choosing a phone to harden](#choosing-a-phone-to-harden)
- [Easy way](#easy-way)
    - [General](##general)
    - [Sensors](##sensors)
    - [Network and location](##network-and-location)
    - [Language and Input](##language-and-input)
- [Advanced way](#advanced-way)

# Choosing a phone to harden
- Tier A: FairPhone, OnePlus, Sony, Asus, Google (Custom ROM)
- Tier B: Apple, Nokia, Samsung, ...
- Tier C: OPPO, Vivo, Realme, Xiaomi, Huawei, ...
## Some tips to choose a phone
- Don't buy /csg/ stuffs
- Don't buy locked phone of AT&T, Verizon, Docomo, Softbank, ...
- Buy a phone with clean firmware, or easily to unlock and install another ROM.
- I recommend to buy an Android phone. Apple's phone is not private and secure, it is too hard to harden too. (trust me bro)

# Easy way
## General
- Disable, uninstall all Google apps (Google is evil).
- Debloat apps, disable all telemetry on your phone. You can use ADB or Shizuku to uninstall unnecessary system apps. Bloated apps make your phone slow and it's always working to track you.
- Use FOSS and libre apps. You can use F-Droid to install FOSS apps like NewPipe or Mull. If you don't know which app to use, you can check out my list [here](https://example.com)
- Don't install too many apps.
- Always check for software updates.

## Sensors
- (Android 12 and higher) Disable Camera access and Mic access
- Disable sensors (you can find this setting on Developer Settings)

## Network and location
- Turn off Wi-Fi, Bluetooth, NFC and Mobile Network when not in use. On some custom ROM, you can change some settings to make it turn off automatically.
- Forget Wi-Fi networks to prevent automatic rejoin.
- Disable 'Turn on Wi-Fi automatically'
- Disable 'Hotspot 2.0'
- Disable location and location services (like "Find my phone", ...). This may enable anyone with access to your Google account (e.g. if hacked or by law enforcement) to track your location.
- Use privacy browser. I recommend to use Mull (hardened Firefox Android). It has disabled telemetry by default so you don't need to tweak it much. If you use Brave, you need to mitigate it by following [this guide]().
- Use a VPN. I Recommend RiseupVPN because it's free, open-source and does not collect any information.
- Use firewall to block apps connect to internet. You can use NetGuard or RethinkDNS, they can work without root permission.

## Language and Input
- Disable spell checker, suggestion, auto correct, ...
- Use open-source keyboard like FlorisBoard, OpenBoard, ...

# Advanced way
- Replace all system apps with AOSP apps or Simple Mobile Tool's apps
- Use de-googled, privacy and security-oriented custom ROM like GrapheneOS, LineageOS and CalyxOS.
- Use hardened kernel.
- Root your phone. I don't recommend this method, but it's also a good way to harden the phone.
- Encrypt your phone (you don't need to do that because from android 10 and higher, this setting is already enabled.)
- Lock SIM card.
- Remove camera and microphone.