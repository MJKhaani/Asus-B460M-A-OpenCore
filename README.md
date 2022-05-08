![](https://badgen.net/badge/OpenCore/0.7.9/green) ![](https://badgen.net/badge/macOS/12.3/orange)

|Component | Model |
| -------- | ----- |
| CPU | Intel(R) Core(TM) i3-10100 CPU @ 3.60GHz |
| Mainboard | Asus Prime B460M-A |
| iGPU | Intel UHD 630 |
| SSD | Adata SowrdFish 1TB NVMe |
| HDD | WB 1TB Blue |
| Ethernet | RTL8111 |
| Wifi & BT | BCM943602CS purchased but i need adapter to connect it |
| Audio | ALC887 |
| Display | 2 x Full HD LG Display |


|   | F | P | N | Comment |
| - | ----- | --------- | ----------- | ------- |
| CPU Power Managment | ✅ | | | Using CPUFriend.kext + CPUFriendDataProvider.kext -> LMF 800MHz |
| USB Ports | ✅ | | | Using USBInjectAll.kext & building USBPort.kext using hackintool |
| iPGU Accrelation | <div align=”center”>✅</p> | | | Using device-id 9B3E0000 & framebuffer port patching |
| Dual Display | | ✅ | | Works if one of them is off during boot |
| Sleep | ✅ | | | also working with dual display |
| DRM | | | ✅ | DRM is broken for iGPU-only systems (need dGPU) |
| iServices | ✅ | | | |
> F: fully working  P: Partially working N: not working
