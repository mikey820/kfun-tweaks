# Phantom

iOS SpringBoard customization app powered by the [DarkSword kernel exploit](https://github.com/wh1te4ever/darksword-kexploit-fun). No jailbreak required — sideload the unsigned IPA and run it.

## Supported devices

All iOS / iPadOS **17.0 – 26.0.1** devices, except A19 / M5.

## Tweaks

| Tweak | Description |
|---|---|
| **5 Icon Dock** | Adds a 5th icon slot to the dock |
| **Hide Icon Labels** | Removes text labels from home screen icons |
| **Disable App Library** | Removes the App Library page from the home screen |
| **Disable Icon Fly-In** | Skips the bounce animation when unlocking |
| **Double Tap to Lock** | Double-tap the home screen to lock the device |
| **Home Screen Grid** | Customizable columns and rows (default 4×6) |
| **Home Screen Icon Scale** | Adjustable icon size (default 0.9×) |
| **Dock Icon Scale** | Adjustable dock icon size (default 0.9×) |
| **Instant Wake** | Removes fade-in animation when screen wakes |
| **Instant Screen Off** | Removes fade-out animation when locking |
| **Custom Drag Coefficient** | Adjustable global animation speed |
| **Disable / Re-enable OTA** | Blocks or restores OTA update daemons (reboot required) |

Parametric tweaks (scale, grid size, animation speed) have sliders in the Settings tab and apply immediately without re-running the exploit.

## Install

1. Download `phantom.ipa` from [Releases](https://github.com/mikey820/phantom-tweaks/releases/latest)
2. Sideload with **AltStore**, **Sideloadly**, **TrollStore**, or any IPA installer
3. Open the app — the exploit runs automatically on launch
4. Go to the **Settings** tab to enable tweaks

## Build from source

Requires Xcode 16+ on macOS.

```
git clone --recursive https://github.com/mikey820/phantom-tweaks
cd phantom-tweaks
open darksword-kexploit-fun.xcodeproj
```

GitHub Actions builds a signed-off unsigned IPA on every push to `main`.

## Credits

- [wh1te4ever](https://github.com/wh1te4ever) — DarkSword kernel exploit & 5 icon dock / hide labels
- [AlexDavitoiu](https://github.com/AlexDavitoiu) — kexploit-fun fork
- [kolbicz](https://github.com/kolbicz) — DarkSword-Tweaks (SpringBoard tweak implementations)
- [opa334](https://github.com/opa334) — kernel exploit primitives
- [zeroxjf](https://github.com/zeroxjf) — XPF patchfinder
