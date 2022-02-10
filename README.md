# Removing and Cloning HALS

rm -rf hardware/qcom-caf/msm8996/audio && rm -rf hardware/qcom-caf/msm8996/media && rm -rf hardware/qcom-caf/msm8996/display && rm -rf hardware/qcom-caf/wlan && git clone https://github.com/afterallafk/hardware_qcom-caf_msm8996_audio.git -b 12 hardware/qcom-caf/msm8996/audio && git clone https://github.com/afterallafk/hardware_qcom-caf_msm8996_media.git -b 12 hardware/qcom-caf/msm8996/media && git clone https://github.com/afterallafk/hardware_qcom-caf_msm8996_display.git -b 12 hardware/qcom-caf/msm8996/display

# Cloning Trees

git clone https://github.com/afterallafk/voltage_device_xiaomi_onclite.git -b twelve device/xiaomi/onclite && git clone https://github.com/afterallafk/vendor_xiaomi_onclite-12.git -b twelve vendor/xiaomi/onclite && git clone https://github.com/afterallafk/kernel_xiaomi_onclite.git -b twelve kernel/xiaomi/onclite
