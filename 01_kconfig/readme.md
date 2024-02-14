Refer to https://interrupt.memfault.com/blog/practical_zephyr_kconfig

# Alternative CONF File
west build --board nrf52840dk_nrf52840 -d ../build -- -DCONF_FILE=prj_release.conf