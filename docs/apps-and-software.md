# Apps & Software

[← Back to Home](../README.md)

---

## Essential Apps

| App | Purpose | Notes |
|-----|---------|-------|
| **[YouTube ReVanced](https://revanced.app/)** | Ad-free YouTube | Background playback, ad blocking |
| **[SmartTube](https://github.com/yuliskov/SmartTube)** | Alternative YouTube client | TV-optimized interface |
| **[Taskbar](https://play.google.com/store/apps/details?id=com.farmerbb.taskbar&hl=en_US)** | Multi-window management | Floating windows like desktop PC |
| **[Voice Access](https://play.google.com/store/apps/details?id=com.google.android.apps.accessibility.voiceaccess&hl=en_US)** | Hands-free navigation | Google accessibility feature |
| **[Key Mapper](https://github.com/keymapperorg/KeyMapper)** | Button remapping | Customize physical controls |
| **[LocalSend](https://localsend.org/)** | File transfers | Fast WiFi transfers - Open source multi-platform airdrop alternative |

## Alternative App Stores

| App Store | Purpose | Notes |
|-----------|---------|-------|
| **[Aptoide](https://en.aptoide.com/)** | Alternative app store | Works on both Chinese & international versions |
| **[Aurora](https://auroraoss.com/)** | Anonymouse Play Store Access | Does not require Google services |
| **[F-Droid](https://f-droid.org/en/)** | App store alternative hosting FOSS applications | Free and open source |

---

## Progressive Web Apps (PWAs)

Chrome on the INMO Air 3 does not support the standard "Install App" option for Progressive Web Apps. As a workaround, you can convert PWAs to installable APK files:

### Using PWABuilder

1. Visit **[PWABuilder.com](https://www.pwabuilder.com/)** on a PC or phone
2. Enter the URL of the PWA you want to install
3. Click "Start" to analyze the web app
4. Select "Android" as the platform
5. Download the generated APK file
6. Transfer the APK to your INMO Air 3 and install it

This method works for many popular PWAs including web-based tools, games, and services that don't have native Android apps.

---

## Content & Streaming

- **Netflix** (limited to SD quality - Widevine L3)
- **Disney+**
- **Prime Video**
- **Twitch**
- **Plex** (local media server)
- **VLC Player** (supports picture-in-picture)
- **[Stremio](https://www.stremio.com/)** TV and Movie streaming

---

## Productivity & Remote Access

| App | Description |
|-----|-------------|
| **Chrome Remote Desktop** | PC screen mirroring (highly recommended) |
| **AnyDesk** | Remote desktop (causes heat when charging) |
| **TeamViewer** | Alternative remote access |
| **Moonlight** | PC game streaming |
| **Spacedesk** | Extend Windows desktop via USB/WiFi |
| **ApowerMirror** | Android phone screen mirroring (use Smart TV version) |
| **[Scrcpy](https://github.com/Genymobile/scrcpy)** | Mirrors Android to Linux/PC/Mac |

See [Screen Mirroring & Remote Desktop](screen-mirroring.md) for detailed setup guides.

---

## Input & Control

| App | Description |
|-----|-------------|
| **[Key Mapper](https://github.com/keymapperorg/KeyMapper)** | Remap physical buttons and controller inputs |
| **Tasker** | Automation and custom actions (advanced users) |
| **[Nova Launcher](https://play.google.com/store/apps/details?id=com.teslacoilsw.launcher&hl=en_US)** | Popular customizable launcher replacement |

### Key Mapper

Key Mapper is a powerful Android app for remapping buttons and creating custom shortcuts on external devices. It supports over 100 individual actions and works with keyboards, game controllers, headsets, mice, and built-in buttons.

**Recommended Version:** Install from [GitHub Releases](https://github.com/keymapperorg/KeyMapper/releases) rather than the Play Store. The GitHub version includes additional features like screen on/off control that are not available in the Play Store version.

**Supported Devices:**
- Bluetooth keyboards (including BlackBerry-style keyboards)
- Game controllers (D-pad, ABXY buttons)
- Volume and side buttons
- Headset buttons
- Mice

**Example Use Cases:**
| Shortcut | Action |
|----------|--------|
| Volume button long press | Toggle voice assistant |
| Keyboard key | Trigger voice input |
| Double-press volume | Screen on/off |
| Hold button | Adjust brightness |
| Custom key combo | Open specific app |
| Controller button | Simulate scroll up/down |
| Headset button | Launch intent or app |

**Trigger Options:**
- Single press, double press, long press
- Key combinations and sequences
- App-specific constraints (only trigger in certain apps)
- Screen state constraints (lockscreen, screen off)

Works great combined with external keyboards like the [Winmaxle B1](accessories.md#blackberry-style-keyboards) or [ZitaoTech keyboards](accessories.md#blackberry-style-keyboards) for hands-free control of your INMO Air3.

**Links:** [GitHub](https://github.com/keymapperorg/KeyMapper) | [F-Droid](https://f-droid.org/packages/io.github.sds100.keymapper/) | [Documentation](https://docs.keymapper.club/)

---

## System Optimization

| Tool | Description |
|------|-------------|
| **[Quick Settings](https://play.google.com/store/apps/details?id=com.frandro.quicksettings)** | Access to hidden or hard to find system settings |

---

## GPS & Navigation

| App | Description |
|-----|-------------|
| **[Bluetooth GNSS](https://play.google.com/store/apps/details?id=com.clearevo.bluetooth_gnss)** | Use external Bluetooth GPS receiver for improved location accuracy |

### Using External Bluetooth GPS

The built-in GPS on INMO Air3 may have limited accuracy. For navigation or location-dependent apps, you can use an external Bluetooth GPS receiver:

1. Install **Bluetooth GNSS** from the Play Store
2. Pair your external GPS receiver via Bluetooth
3. Configure Bluetooth GNSS to use the external receiver as mock location
4. Enable mock locations in Developer Options
5. Navigation apps will now use the more accurate external GPS

This is useful for driving navigation, cycling, or any activity requiring precise location tracking.

---

## Known Limitations

| App/Feature | Issue |
|-------------|-------|
| **ChatGPT** | Integrity verification fails |
| **ARCore Apps** | Not certified, won't work |
| **Widevine L1 Streaming** | Not available (Netflix limited to SD) |
| **PWA Installation (Chrome)** | Not supported - use [PWABuilder](https://www.pwabuilder.com/) to convert PWAs to APKs |

---

[← Back to Home](../README.md)
