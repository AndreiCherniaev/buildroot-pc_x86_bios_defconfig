This is working config with kernel 4.19.269 (based on pc_x86_64_bios_defconfig)

To use
make clean -C buildroot
make BR2_EXTERNAL=${MyBaseDir}/my_external_tree -C buildroot pc_x86_bios_defconfig
make -C buildroot

see also
https://bugs.busybox.net/show_bug.cgi?id=15246
