# vendor_xiaomi_camera

Prebuilt stock MIUI Camera to include in custom ROM builds.

Extracted from lisa MIUI package (refer proprietary-files.txt for version).

### Supported devices
* POCO X3/NFC (Surya/Karna)

### How to use?

1. Clone this repo to `vendor/xiaomi/camera`:
```
git clone -b 16  https://github.com/NothingHere69/vendor_xiaomi_camera.git vendor/xiaomi/camera --single-branch
```

2. Inherit it from `device.mk` in device tree:

```
# Camera
$(call inherit-product-if-exists, vendor/xiaomi/camera/surya-camera.mk)
```
