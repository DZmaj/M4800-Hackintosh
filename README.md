# M4800-Hackintosh
Document For hackintosh on Dell  Precision M4800
// create at 2016/01/01

Hardware:
Dell Precision M4800 
+ CPU: i7 4810QM 
+ Chipset: intel QM87 
+ RAM: 2x8GB RAM
+ IGPU: Intel HD 4600 ✔︎
+ DGPU: nVidia Quadro K1100M 2GB DDR5 - read more on next line
+ Display: 1920x1080 IPS - eDP port
+ Sound: RealTek ALC 292 ✔︎thank for Jake Lo - OSX latitude
+ WLAN: Replace origin intelWifi with BCM943225 ✔︎
+ Ethernet: Intel I217-LM ✔︎
+ TouchPad: ALPS touchpad ✔︎
+ Battery ✔︎

webcam and SDCard reader work fine on Yosemite but on El Capitan is not work - i'm will be fix soon.

/*!
2016/01/01.
+ Upload Origin ACPI
+ Upload Release Clover pack for OS X El Capitan
..and some ...

on this release :
+ disable nvidia Quadro K1100M
+ make sure your optimus is enable on every boot times.
+ display brightness control is Fn F3 and FN Insert (remember that, not up key and down key )

*/

Thanks.

____________
About nVidia Quadro K1100M
+ enable optimus : can work with external display (internal display connect to iGPU) - testing.... 
+ disable optimus : can work with internal display but issue is Dark Screen 
( dark = display panel light on but signal is lost ,
black = display panel light is of )

why dark ?
because my internal connector is eDP port.
i don't know why eDP work on Intel HD4600 but not work fine on K1100M

*never support for Tonymacx86/unibeast/multibeast/hackintoshzone/niresh
____________
origin Vietnamese thread http://osx.vn/threads/guide-dell-precision-m4800-macbook-co-suc-manh-workstaion.2926/
@DuongTH
E-mail: HungDuongWP@gmail.com
Facebook: https://www.facebook.com/DuongOSX
