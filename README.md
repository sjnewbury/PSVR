# PSVR - Support for 90 and 120Hz

Example for use:

Put psvr.bin into `"/lib/firmware/edid/"`

Put below line into your dracut.conf or equivilent initramfs generator

`install_items+=" /lib/firmware/edid/psvr.bin "`

Add kernel parameter: (changing HDMI reference for your PSVR port)

`drm.edid_firmware=HDMI-A-1:edid/psvr.bin`

