# Campus Energy Monitor apps

CPUT Final Year Project 2026, Henock Mukonkole.

The apps open the live dashboard (https://campus-energy-emergent.pages.dev) in its own window. They show live 3-phase readings, the AI energy assistant, the controls and the camera, the same as the website. Any update to the website appears in the apps straight away, so they never need updating for content changes.

An internet connection is needed. Without one, the apps show a "No internet" screen with a Try again button.

Live dashboard: https://campus-energy-emergent.pages.dev  
Downloads page: https://campus-energy-emergent.pages.dev/download/

## Files

| Platform | File | Size |
|---|---|---|
| Android 5.1 and newer | [Campus-Energy-Monitor.apk](https://github.com/henockhnk092-dot/campus-energy-monitor-apps/releases/latest/download/Campus-Energy-Monitor.apk) | about 5 MB |
| Windows 10 and 11 (64-bit) | [Campus-Energy-Monitor-Setup.exe](https://github.com/henockhnk092-dot/campus-energy-monitor-apps/releases/latest/download/Campus-Energy-Monitor-Setup.exe) | about 110 MB |
| Linux (64-bit) | [Campus-Energy-Monitor-linux-x64.tar.gz](https://github.com/henockhnk092-dot/campus-energy-monitor-apps/releases/latest/download/Campus-Energy-Monitor-linux-x64.tar.gz) | about 120 MB |
| iPhone, iPad and Mac | no file, installed from the website (see below) | |

## Android

1. Copy `Campus-Energy-Monitor.apk` to the phone, or download it there.
2. Open it. If Android asks, allow installing apps from this source (Files or Chrome).
3. Tap **Install**, then **Open**.
4. The first time you use the AI voice chat, the voice call or the camera, allow the microphone and camera.

The Android app uses the phone's own voices to read answers aloud, and Google voice typing for the microphone button.

## Windows

1. Run `Campus-Energy-Monitor-Setup.exe`.
2. Windows may show "Windows protected your PC", because the app isn't signed with a paid certificate. Click **More info**, then **Run anyway**.
3. Choose a folder, then finish. A desktop shortcut is created.

## Linux

```bash
tar -xzf Campus-Energy-Monitor-linux-x64.tar.gz
cd Campus-Energy-Monitor-linux-x64   # the extracted folder
./campus-energy-monitor
```

If it doesn't start on Ubuntu 24.04 or newer, run it with `./campus-energy-monitor --no-sandbox`.

## iPhone and iPad

1. Open https://campus-energy-emergent.pages.dev in **Safari**.
2. Tap the **Share** button, then **Add to Home Screen**, then **Add**.

## Mac

1. Open https://campus-energy-emergent.pages.dev in **Safari** (macOS Sonoma or newer).
2. Choose **File > Add to Dock**.

On older macOS, or in Chrome, use Chrome's menu: **Cast, save and share > Install page as app**.

## Known limits

- **Google sign-in** doesn't work inside the Android, Windows and Linux apps, because Google blocks sign-in inside apps. Use **email and password** to sign in to the apps, or sign in with Google on the website.
- **Voice typing on Windows and Linux** (the microphone button in the AI chat): the desktop apps can't use Google's speech service, so speak to the assistant on Android or in the website in Chrome or Edge. Reading answers aloud works on all platforms.
- **Native iPhone and Mac apps** need a Mac with Xcode and an Apple developer account (USD 99 a year), so they are installed from the website for now.
