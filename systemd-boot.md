### systemd-boot
#### /boot/loader/loader.conf
```
timeout 0
console-mode keep
default arch.conf
```
#### /boot/loader/entries/arch-zenbook.conf
```
options ... ipv6.disable_ipv6=1 quiet loglevel=3 systemd.show_status=auto rd.udev.log_level=3 i915.fastboot=1 vt.global_cursor_default=0 acpi_osi=
```
#### /boot/loader/entries/arch-m1.conf
```
options ... pcie_aspm=off
```
