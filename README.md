# flutter-basic

## Start

```bash
$ flutter run --device-id chrome
🔥  To hot restart changes while running, press "r" or "R
```

## install flutter

1. official refferenceでdownload  
<https://docs.flutter.dev/get-started/install>
2. passを通す
.zshrcに `export PATH="$PATH:$HOME/flutter/bin"` を追加
3. passが通っているか確認

```bash
$ flutter --version
Flutter 3.7.7 • channel stable • https://github.com/flutter/flutter.git
Framework • revision 2ad6cd72c0 (2 weeks ago) • 2023-03-08 09:41:59 -0800
Engine • revision 1837b5be5f
Tools • Dart 2.19.4 • DevTools 2.20.1

$ flutter doctor
Doctor summary (to see all details, run flutter doctor -v):
[✓] Flutter (Channel stable, 3.7.7, on macOS 12.6.3 21G419 darwin-arm64, locale ja-JP)
[✓] Android toolchain - develop for Android devices (Android SDK version 33.0.2)
[✓] Xcode - develop for iOS and macOS (Xcode 14.2)
[✓] Chrome - develop for the web
[✓] Android Studio (version 2022.1)
[✓] VS Code (version 1.76.2)
[✓] VS Code (version 1.76.2)
[✓] Connected device (2 available)
[✓] HTTP Host Availability

• No issues found!
```

### 参考

- <https://www.flutter-study.dev/getting-started/install>
