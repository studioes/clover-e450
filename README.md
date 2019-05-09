# clover-e450
Clover EFI for ThinkPad E450

My machine:  
Lenovo ThinkPad E450(Japan BTO)  
BIOS 1.35  
Core i7 5500U  
12GB RAM(8GB+4GB)  
HD5500 + Radeon R7 M260(not working)  
IPS 1920x1080  
8265 WiFi(not working)  
US Keyboard  
Samsung 840EVO 250GB SSD  
Add TP-Link Archer T2U nano USB WiFi  

**Important:**
 If you set a charge threshold with ThinkVantage, that setting is valid in this environment and can only be changed with ThinkVantage. If you need change threshold, you must use Windows 10 and ThinkVantage.

Running: 10.13.6, 10.14.4

- CPU: OK
- Graphics: OK(HD5500 only)
- Ethernet: OK
- WiFi: not working
- Battery: OK
- Backlight: OK(PWMMax low?)
- Keyboard: OK(with hotkeys, Audio Mute, VolumeUp&Down, Backlight brightness Up&Down)
- TrackPoint: OK(without scroll)
- TrackPad: OK(multi touch not working)

Require kexts(/L/E)
- ACPIBatteryManager.kext
- AppleBacklightFixup.kext
  
History
- 0.1: HighSierra support
- 0.2: Audio device support
- 0.2.1: Mojave support
- 0.3:
  - Backlight control support.
  - Battery status support.
  - Hotkey support.
