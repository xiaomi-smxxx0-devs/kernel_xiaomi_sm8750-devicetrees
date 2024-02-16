ifeq ($(CONFIG_ARCH_SUN), y)
	dtbo-y += hw_fence/sun-hw-fence.dtbo \
		sun-mm-cdp-kiwi-overlay.dtbo \
		sun-mm-cdp-kiwi-v8-overlay.dtbo \
		sun-mm-cdp-nfc-overlay.dtbo \
		sun-mm-cdp-overlay.dtbo \
		sun-mm-cdp-v8-overlay.dtbo \
		sun-mm-mtp-kiwi-overlay.dtbo \
		sun-mm-mtp-kiwi-v8-overlay.dtbo \
		sun-mm-mtp-nfc-overlay.dtbo \
		sun-mm-mtp-overlay.dtbo \
		sun-mm-mtp-v8-overlay.dtbo \
		sun-mm-qrd-sku1-overlay.dtbo \
		sun-mm-qrd-sku1-v8-overlay.dtbo \
		sun-mm-qrd-sku2-v8-overlay.dtbo \
		sun-mm-rumi-overlay.dtbo
endif

always-y    := $(dtb-y) $(dtbo-y)
subdir-y    := $(dts-dirs)
clean-files    := *.dtb *.dtbo
