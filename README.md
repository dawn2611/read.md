Copyright (C) 2017 - The LineageOS Project

Common device tree for Xiaomi MSM8953 based devices
 Full 
 
  git clone https://github.com/sayan7848/android_kernel_xiaomi_msm8953 -b ninthHorcrux kernel/xiaomi/msm8953
git clone https://github.com/sayan7848/proprietary_vendor_xiaomi-1 -b myadditions-pie vendor/xiaomi
 Havoc
 
git clone https://github.com/hungphan2001/android_device_xiaomi_msm8953-common -b havoc device/xiaomi/msm8953-common
git clone https://github.com/hungphan2001/android_device_xiaomi_mido -b havoc device/xiaomi/mido
git clone https://github.com/hungphan2001/hardware_qcom_display-caf-msm8996 -b p hardware/qcom/display-caf-msm8996
git clone https://github.com/nitrogen-project/android_hardware_qcom_media-caf-msm8996 -b p hardware/qcom/media-caf-msm8996
git clone https://github.com/nitrogen-project/android_hardware_qcom_audio-caf-msm8996 -b p hardware/qcom/audio-caf-msm8996
rm -rf hardware/qcom/bt
rm -rf hardware/qcom/power
rm -rf packages/apps/HavocSettings
rm -rf packages/apps/Updates
 git clone https://github.com/LineageOS/android_hardware_qcom_bt -b lineage-16.0 hardware/qcom/bt
  git clone https://github.com/LineageOS/android_hardware_qcom_bt -b lineage-16.0-caf hardware/qcom/bt-caf
  git clone https://github.com/LineageOS/android_hardware_ril -b lineage-16.0-caf hardware/ril-caf
  git clone https://github.com/LineageOS/android_hardware_qcom_power -b lineage-16.0 hardware/qcom/power
  git clone https://github.com/hungphan2001/android_packages_apps_HavocSettings -b pie packages/apps/HavocSettings
  git clone https://github.com/hungphan2001/android_packages_apps_Updates -b pie packages/apps/Updates
  
  Hals from los
  
  git clone https://github.com/LineageOS/android_hardware_qcom_audio -b lineage-16.0-caf-8996 hardware/qcom/audio-caf/msm8996
  git clone https://github.com/LineageOS/android_hardware_qcom_display b lineage-16.0-caf-8996 hardware/qcom/display-caf/msm8996
  git clone https://github.com/LineageOS/android_hardware_qcom_media b lineage-16.0-caf-8996 hardware/qcom/media-caf/msm8996
 
==============
