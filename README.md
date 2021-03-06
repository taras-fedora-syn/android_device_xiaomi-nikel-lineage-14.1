# Device Tree for Xiaomi Redmi Note 4 (Nikel)

# Spec Sheet

| Feature                 | Specification                     |
| :---------------------- | :-------------------------------- |
| CPU                     | Deca-core 2.1 GHz                 |
| Chipset                 | Mediatek MT6797 Helio X20         |
| GPU                     | Mali-T880 MP4                     |
| Memory                  | 2/3/4 GB                          |
| Shipped Android Version | 6.0.1                             |
| Storage                 | 32/64 GB                          |
| MicroSD                 | Up to 256 GB                      |
| Battery                 | 4100 mAh (non-removable)          |
| Dimensions              | 151 x 76 x 8.5 mm                 |
| Display                 | 1920x1080 pixels, 5.5 (~401 PPI)  |
| Rear Camera             | 13 MP, LED flash                  |
| Front Camera            | 5 MP                              |
| Release Date            | January 2017                      |


   # Build
   * repo init -u git://github.com/LineageOS/android.git -b cm-14.1
   * repo sync
   * git clone https://github.com/jorgeiba97/android_device_xiaomi-nikel-lineage-14.1.git -b master device/xiaomi/nikel
   * git clone https://github.com/jorgeiba97/android_vendor_xiaomi-nikel-lineage-14.1.git -b cm-14.1 vendor/xiaomi/nikel
   * cd device/xiaomi/nikel/patches
   * . apply.sh
   * source build/envsetup.sh
   * breakfast nikel
   * brunch nikel
   * Done :)
   
   # Known Issue:-
   * Rotation Sensor
   * RIL is very unustable
   * FP Scanner
   * Camera
   
   # Credits:-
   * AdrianoMartins
   * divis1969
   * xen0n
   * samarV-121
   * DiedMaster
   * end222
   * & Me :)

