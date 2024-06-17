# LenovoH2O-Unlocker
These Are tool/Source From "The Vault", that I decided to upload, so expect not fully polished product, or very slow Fixes if any
# USE AT YOUR OWN RISK,I won’t be responsible for any damage.

Latest BIOS and 2022 Model are not supported

## Is my bios Is supported by this:
To check if your bios is Unlockable by this: search for “cE!” unicode text in UEFI tool, if at lest 2 result are found (one on DebugPageDxe and the other on H20FormBrowserDXE), you can give a shot.
Alternatively just run it and check...

## I need a SPI Flasher?:
No

## How to use
Download the exe run with admin privileges, the bios will be unlocked, run again it will be locked again.

## How this work/worked, and how was discovered

~ Maybe I will write a proper blog post about this~

# I have Linux, what I can do

You just need to create a Efi Variable named cE! with GUID {6ACCE65D-DA35-4B39-B64B-5ED927A7DC7E}

Given how different linux Install can be, I will not provide any guide, but you thsi can be a good start [efivarfs - a (U)EFI variable filesystem](https://www.kernel.org/doc/html/latest/filesystems/efivarfs.html)



## Related Stuff
Newest BIOS are not unlockable by this, as turned out that the cE! switch responsible for this, also disabled other secuiry feature (on Intel Machine), so it has been completely removed

[Eset Research ](https://www.welivesecurity.com/2022/04/19/when-secure-isnt-secure-uefi-vulnerabilities-lenovo-consumer-laptops/) on this.
