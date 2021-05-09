**2020/02/21**
- Update Kexts
- Replace USBInjectAll.kext with USBMap.kext

**2020/02/08**
- Edit ACPI to make AsusSMC kext work
- Fix Keyboard Backlight
- Fn function list:
  + Fn + F1: Mute
  + Fn + F2/F3: Increase/Decrease volume
  + Fn + F4/F5: Increase/Decrease screen brightness
  + Fn + F6: On/Off Touchpad
  + Fn + F7/F8: Increase/Decrease Keyboard Backlight (16 levels)
  + Fn + F9/F10/F11/F12: Home/End/PgUp/PgDown
  + Fn + Space: Play/Pause
  + Fn + Enter : Put Computer to Sleep (run install_daemon.sh as root to make this work)
  + Fn + Esc: On/Off Screen
- Add firmware Bluetooth (can use Intel Bluetooth)
- Sound fixing completely
- Update OpenCore to version 0.5.5
- Update all Kexts to newest version
* waiting for Wifi Intel Dual-Band AC8265 working

**2019/12/06**
- Update OpenCore to version 0.5.4
- Update Kexts to newest version
- Fix kernel panic when use Whatevergreen 1.3.6

**2019/11/18**
- Stable on macOS 10.15.1
- Stop update Clover (moved completely to OpenCore)
- Update OC Bootloader
- Update Kexts to newest version
- Fix sound not working
- Remove kext USB Wifi (just use setup file from homepage)
  + macOS 10.15: Use Hackintool to mount /System then run setup file

**2019/09/17**
- Make OpenCore Bootloader as Main Bootloader
- Update OpenCore Bootloader, kexts
- Add íntalling driver USB Wifi Comfast CF-811AC instruction

**2019/08/27**
- Add OpenCore Bootloader (testing)
- Fix Apple ALC
- Fix Minor bugs

**2019/06/14**
- Initialized
