ifeq ($(CONFIG_ARCH_SUN),y)
dtbo-y += sun-kiwi-cnss.dtbo
dtbo-y += sun-kiwi-cnss-v8.dtbo
dtbo-y += sun-peach-cnss.dtbo
dtbo-y += sun-peach-cnss-v8.dtbo
dtbo-y += sunp-hdk-peach-cnss-v8.dtbo
endif

ifeq ($(CONFIG_ARCH_PINEAPPLE),y)
dtbo-y += pineapple-kiwi-cnss.dtbo
dtbo-y += pineapplep-hdk-kiwi-cnss.dtbo
endif

ifeq ($(CONFIG_ARCH_X1E80100),y)
dtbo-y += x1e80100-kiwi-cnss.dtbo
endif

ifeq ($(CONFIG_ARCH_RAVELIN),y)
dtbo-y += ravelin-idp-adrastea.dtbo
dtbo-y += ravelin-qrd-adrastea.dtbo
dtbo-y += ravelin-atp-adrastea.dtbo
endif

ifeq ($(CONFIG_ARCH_PARROT),y)
dtbo-y += parrot-idp-wcn3990.dtbo
dtbo-y += parrot-idp-wcn6750.dtbo
dtbo-y += parrot-qrd-wcn3990.dtbo
dtbo-y += parrot-qrd-wcn6750.dtbo
dtbo-y += parrot-atp-wcn3990.dtbo
dtbo-y += parrot-rumi-wcn3990.dtbo
dtbo-y += parrot-idp-wcn6755.dtbo
dtbo-y += parrot-qrd-wcn6755.dtbo
endif

ifeq ($(CONFIG_ARCH_VOLCANO),y)
dtbo-y += volcano-qca6750.dtbo
endif

always-y	:= $(dtb-y) $(dtbo-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb *.dtbo
