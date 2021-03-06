# 08-July-2022
- Add telephony system-ext privapp permissions
- Address elliptic denials
- Allow platform app to find SoterService
- Allow system_app to write thermal sysfs
- Display icon beside thermal profiles
- Drop QCOM wfd HDCP support
- Fix fingerprint labels
- Import lmkd props from google gki
- Label fingerprint props as restricted vendor
- Move deviceid props to vendor
- parts: Don't explicitly set android:theme for activities
- Remove unused hwservice label
- Rename ANXCamera to MiuiCamera
- Revoke system_server access to fingerprint prop
- Ship VantomKernel v4.14.286

# 23-June-2022
- Add missing status bar dimensions
- Fix ANXCamera after updating blobs
- Fix data decryption in TWRP

# 21-June-2022
- Address QCOM WFD denials
- Disable zram writeback
- Don't enable iostats
- Don't tune sde partition on boot
- Drop firmware inclusion (Install firmware separately)
- Drop QCOM thermal engine components
- Drop updatable GPU drivers
- Enable auto brightness while dozing
- Fix UDFPS not registering
- Implement UDFPS handler
- Import dolby codecs
- June security patch level
- media: Finetune performance xml
- Move to common Xiaomi fingerprint HIDL
- Override odm_dlkm and vendor_dlkm props
- parts: Add dynamic thermal profile implementation
- parts: Handle more errors for dirac
- parts: Use directBootAware
- Pull sepolicy from SM8250
- Ship VantomKernel v4.14.282
- Support F2FS compression and garbage collector
- Switch SchedTune to UClamp
- Switch to EROFS for dynamic partitions
- Switch to status_bar_height_portrait
- Sync brightness overlays with coral
- Update blobs from LA.QSSI.12.0.r1-07100-qssi.0
- Update build fp & desc to MIUI V13.0.2.0.SFNMIXM
- Update display color compositions
- Update system WFD blobs from 07100
- Uprev radio config into 1.2
- Use coral tuning for columbus feature

# 07-May-2022
- May security patch level
- Introducing built-in ANXCamera
- Add 300Mhz minimum CPU scaling frequency
- Build IFAAService from source
- Import more camera blobs
- Increase volume steps from 15 to 25
- Update safe media volume index
- Power HAL improvements
- Switch to common Xiaomi light AIDL
- Address more denials
- VantomKernel v4.14.276 improvements
- Disable wallpaper zooming
- Switch to PlayGround clang
- Wi-Fi HAL improvements
- Switch to a custom QTI vibrator AIDL

# 02-May-2022
- Initial official and stable build based on Android 12.1
