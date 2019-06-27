1. remove the USBPower.kext from /Volumes/EFI/EFI/CLOVER/kexts/Other
2. put HibernationFixup.kext and USBInjectAll.kext into /Volumes/EFI/EFI/CLOVER/kexts/Other
3. put SSDT-USB.aml into /Volumes/EFI/EFI/CLOVER/ACPI/patched
4. exec "sudo pmset -a hibernatemode 3"
5. Disable NeverHibernate and enable HibernationFixup
6. use the Clover Configurator edit config.plist,and add darkwake=0 in Boot
7. use the Kext Utility rebuild caches
8. reboot the computer