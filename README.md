# com.linkomnia.mhchina

iBreviarium 我靈讚頌主 2.1.3 extracted from my Google Pixel phone
with the following command:

```sh
adb pull /data/app/~~4hAjChmEfjJTeKpGLGKwOQ==/com.linkomnia.mhchina-P690ZHGKXOydK0M37xObxQ==/base.apk
```

- File size: 6037130 bytes
- SHA256 checksum: 52312b9e535ea4ec94382b126374f4bb07fb4082aa810a09b7f74e3973334873

Incidentally, it looks identical to the APK available from:
[https://apkpure.net/ibreviarium-我靈讚頌主/com.linkomnia.mhchina/download](https://apkpure.net/ibreviarium-%E6%88%91%E9%9D%88%E8%AE%9A%E9%A0%8C%E4%B8%BB/com.linkomnia.mhchina/download)

## Installation

```
$ adb install com.linkomnia.mhchina.apk
Performing Streamed Install
adb: failed to install com.linkomnia.mhchina.apk: Failure [INSTALL_FAILED_DEPRECATED_SDK_VERSION: App package must target at least SDK version 24, but found 22]
$ adb install --bypass-low-target-sdk-block com.linkomnia.mhchina.apk
Performing Streamed Install
Success
```

Thanks to [INSTALL_FAILED_DEPRECATED_SDK_VERSION - Any way around it? : r/GooglePixel](https://www.reddit.com/r/GooglePixel/comments/17bzbcy/install_failed_deprecated_sdk_version_any_way/) for the solution!
