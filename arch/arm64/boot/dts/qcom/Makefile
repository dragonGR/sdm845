ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
        dtbo-$(CONFIG_ARCH_SDM845) += \
        sdm845-mtp-overlay.dtbo \
        sdm845-v2-mtp-overlay.dtbo \
        sdm845-v2.1-mtp-overlay.dtbo \
        enchilada-evb-v2.1-overlay.dtbo \
        enchilada-t0-v2.1-overlay.dtbo \
        enchilada-evt1-v2.1-overlay.dtbo \
        enchilada-evt2-v2.1-overlay.dtbo \
        enchilada-evt2-cxo-v2.1-overlay.dtbo \
        enchilada-dvt-v2.1-overlay.dtbo \
        enchilada-dvt-v2.1-backup-overlay.dtbo \
        enchilada-dvt-v2.1-usb30-overlay.dtbo \
        enchilada-pvt-v2.1-overlay.dtbo \
        enchilada-pvt-v2.1-backup-overlay.dtbo \
        enchilada-mp-v2.1-overlay.dtbo \
        fajita-evb-v2.1-overlay.dtbo \
        fajita-t0-v2.1-overlay.dtbo \
        fajita-evt1-v2.1-overlay.dtbo \
        fajita-dvt-v2.1-overlay.dtbo \
        fajita-dvt-v2.1-bu-overlay.dtbo \
        fajita-pvt-v2.1-overlay.dtbo \
        fajita-pvt-v2.1-bu-overlay.dtbo \
        fajita-pvt-v2.1-v1-overlay.dtbo \
        fajita-pvt-v2.1-spec-overlay.dtbo \
        fajita-mp-v2.1-spec-overlay.dtbo

sdm845-mtp-overlay.dtbo-base := sdm845.dtb
sdm845-v2-mtp-overlay.dtbo-base := sdm845-v2.dtb
sdm845-v2.1-mtp-overlay.dtbo-base := sdm845-v2.1.dtb
enchilada-evb-v2.1-overlay.dtbo-base := sdm845-v2.1.dtb
enchilada-t0-v2.1-overlay.dtbo-base := sdm845-v2.1.dtb
enchilada-evt1-v2.1-overlay.dtbo-base := sdm845-v2.1.dtb
enchilada-evt2-v2.1-overlay.dtbo-base := sdm845-v2.1.dtb
enchilada-evt2-cxo-v2.1-overlay.dtbo-base := sdm845-v2.1.dtb
enchilada-dvt-v2.1-overlay.dtbo-base := sdm845-v2.1.dtb
enchilada-dvt-v2.1-backup-overlay.dtbo-base := sdm845-v2.1.dtb
enchilada-dvt-v2.1-usb30-overlay.dtbo-base := sdm845-v2.1.dtb
enchilada-pvt-v2.1-overlay.dtbo-base := sdm845-v2.1.dtb
enchilada-pvt-v2.1-backup-overlay.dtbo-base := sdm845-v2.1.dtb
enchilada-mp-v2.1-overlay.dtbo-base := sdm845-v2.1.dtb
fajita-evb-v2.1-overlay.dtbo-base := sdm845-v2.1.dtb
fajita-t0-v2.1-overlay.dtbo-base := sdm845-v2.1.dtb
fajita-evt1-v2.1-overlay.dtbo-base := sdm845-v2.1.dtb
fajita-dvt-v2.1-overlay.dtbo-base := sdm845-v2.1.dtb
fajita-dvt-v2.1-bu-overlay.dtbo-base := sdm845-v2.1.dtb
fajita-pvt-v2.1-overlay.dtbo-base := sdm845-v2.1.dtb
fajita-pvt-v2.1-bu-overlay.dtbo-base := sdm845-v2.1.dtb
fajita-pvt-v2.1-v1-overlay.dtbo-base := sdm845-v2.1.dtb
fajita-pvt-v2.1-spec-overlay.dtbo-base := sdm845-v2.1.dtb
fajita-mp-v2.1-spec-overlay.dtbo-base := sdm845-v2.1.dtb
endif

always		:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb
