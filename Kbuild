ifeq ($(CONFIG_ARCH_PINEAPPLE), y)
dtbo-y += pineapple-audio.dtbo \
                 pineapple-audio-cdp.dtbo \
                 pineapple-audio-wsa883x-cdp.dtbo \
                 pineapple-audio-cdp-nfc.dtbo \
                 pineapple-audio-mtp.dtbo \
                 pineapple-audio-mtp-nfc.dtbo \
                 pineapple-audio-qrd.dtbo \
                 pineapple-audio-atp.dtbo \
                 pineapple-audio-rumi.dtbo \
                 pineapple-audio-rcm.dtbo \
                 pineapple-audio-qrd-sku2.dtbo \
                 pineapplep-audio-hdk.dtbo
endif

ifeq ($(CONFIG_ARCH_SUN), y)
dtbo-y += sun-audio.dtbo \
                sun-audio-cdp.dtbo \
                sun-audio-cdp-nfc.dtbo \
                sun-audio-rumi.dtbo \
                sun-audio-mtp.dtbo \
                sun-audio-mtp-3.5mm.dtbo \
                sun-audio-mtp-nfc.dtbo \
                sun-audio-qrd.dtbo \
                sun-audio-hdk.dtbo \
                sun-audio-qrd-sku2.dtbo \
                sun-audio-atp.dtbo \
                sun-audio-rcm.dtbo \
                sun-audio-hamilton-rcm.dtbo \
                sun-audio-hamilton-cdp.dtbo \
                sun-audio-hamilton-mtp.dtbo
endif

 always-y    := $(dtb-y) $(dtbo-y)
 subdir-y    := $(dts-dirs)
 clean-files    := *.dtb *.dtbo
