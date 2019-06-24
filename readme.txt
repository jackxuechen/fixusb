1.remove the USBPower.kext from /Volumes/EFI/EFI/CLOVER/kexts/Other
2.put HibernationFixup.kext and USBInjectAll.kext into /Volumes/EFI/EFI/CLOVER/kexts/Other
3.trun on HibernationFixup
4.Disable NeverHibernate and enable HibernationFixup
5.exec "sudo pmset -a hibernatemode 0"
6.use the Kext Utility rebuild caches