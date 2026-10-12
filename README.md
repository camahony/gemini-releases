# Gemini - app downloads

This repo holds only the newest build of **Gemini** (Block World + Wobble World), a kids' game
made for one family, plus `latest.json`, which the installed game reads to know an update exists.
No source code lives here.

Current version: **1.6.0** (versionCode 8)

- `Gemini-1.6.0-armv7.apk` - 32-bit tablets (Amazon Fire HD 8 2020 and other armeabi-v7a devices)
- `Gemini-1.6.0-arm64.apk` - 64-bit tablets and phones (arm64-v8a)

Install: download the file for your tablet, open it, allow "install unknown apps" if asked, tap Install.
The app on a tablet checks `latest.json` on its start screen and shows a card when a newer version is here.
A grown-up holds the button for 3 seconds; the browser downloads the APK; Android asks to install it.
SHA256 of each file is in `latest.json`.
