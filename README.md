# NexBeat

**NexBeat** — A modern, open-source music player for Android built with Kotlin & Jetpack Compose. Powered by YouTube Music.

> This repository hosts **GitHub Releases** for automatic in-app updates.  


---

## Downloads

| Version | Date | APK | Size |
|---------|------|-----|------|
| v4.3.1 | 2026-09-04 | [NexBeat-v4.3.5-universal-release.apk](https://github.com/PandaSL2/NexBeat/releases/download/v4.3.5/NexBeat-4.3.5.apk) | 36.3 MB |

All APKs are **universal** (supports arm64-v8a, armeabi-v7a, x86, x86_64).

---

<img width="357" height="800" alt="Screenshot_20260604_071823_com_theek_nexbeat_MainActivity (1)" src="https://github.com/user-attachments/assets/2440d955-6ac5-4273-9c5c-0e7ef3bd79a3" />

---

## Core Features

- **Multi-Source Streaming & Integration**:
  - **YouTube Music Streaming**: Access the entire YouTube Music catalog, search songs, play albums, and explore charts.
  - **Spotify & Apple Music Connections**: Seamlessly connect, import, and sync metadata or playlists from Spotify and Apple Music via dedicated plugins.
  - **Local Music Library**: Scan and organize local audio files (MP3, FLAC, M4A, etc.) from device storage with high-fidelity local playback.
  - **Custom Community & Private Playlists**: Create playlists combining local MP3s and YouTube tracks, with the option to publish them to your Home Screen.

- **🔊 Earpiece Stereo (Dual Speaker Boost)**:
  - **Pseudo-Stereo for Single-Speaker Devices**: Leverages the top earpiece speaker as a secondary speaker alongside the main bottom speaker.
  - **Hardware-Safe 30% / 70% Sound Balance**: Calibrated at a safe 30% earpiece / 70% bottom speaker volume ratio to produce rich dual-speaker sound without risking speaker damage.
  - **Quick Sound Controls**: Toggle switch available in Player Settings and directly inside the Equalizer Dialog.

- **🔒 Secret Encrypted Vault & Hardware Security**:
  - **Hardware KeyStore AES-256-GCM Encryption**: Securely hide private photos, videos, and media files (unlock by long-pressing the NexBeat logo with PIN authentication).
  - **Image Grid Previews & Batch Actions**: Real-time thumbnail previews with multi-select batch actions (Delete, Restore, Share).
  - **Encrypted Expirable Share Links**: Share vault files with optional Security Passcodes and expiration timers (15m, 1h, 24h, 7d, or live stream).
  - **Clickable Hyperlink Formatting**: Formatted URLs with clean spacing so messaging apps (WhatsApp, Telegram, SMS) display links as clickable blue hyperlinks.

- **🎶 "Together" Remote & Online Listening**:
  - **Real-Time Playback Synchronization**: Listen to the same music live with friends across LAN or Online connections without needing the same Wi-Fi.
  - **One-Click Deep Link Joining**: Instant join links (`http://nexbeat.app/together?code=XXXXXX`) that open NexBeat directly and auto-connect guests to the room without passcodes or expiration dates.
  - **Live Listener Status Display**: Session hosts can view joined participants' display names live in real-time under the active status card.

- **Offline Downloads & Smart Caching**: Download tracks for uninterrupted offline listening with smart storage caching.
- **Discord Rich Presence**: Share what you are listening to in real-time directly on Discord.
- **Scrobbling Support**: Full integration with Last.fm & ListenBrainz to log and track your listening history.
- **Built-in Equalizer**: Multi-band hardware audio equalizer with Bass Boost and Virtualizer support.
- **Content Moderation Engine**: Mandatory user content agreement with a 3-report automatic community content removal threshold for safe sharing.

---

## 🎨 Advanced Customization & Appearance

Customize the interface to fit your unique visual style directly via the **Appearance Page**:

- **Aesthetic Themes & Color Engine**:
  - **Dynamic Theme Engine**: Automatically generate color schemes matching your device wallpaper or current album artwork.
  - **Custom Color Palettes**: Pick and customize colors manually when dynamic themes are disabled.
  - **Pure Black (OLED) Mode**: Deep obsidian dark mode optimized to save battery on OLED screens.
  - **Typography Scale**: Adjust font scaling dynamically (0.8x to 1.4x) or use system default fonts.
  - **Performance Optimization**: Option to disable intensive blur effects on low-resource hardware.

- **Player Interface Stylization**:
  - **6 Distinct Player Designs**: Choose from multiple layouts (V1 to V6) depending on your preference for minimal or info-rich styles.
  - **Stunning Player Backgrounds**: Configure standard backgrounds, custom image backdrops, real-time blurs, animated glows, Apple Music-style mesh gradients, or live-responsive canvas visualizers.
  - **Custom Playback Sliders**: Choose standard, wavy, thick, circular, or simple visual seekbars.
  - **Artwork Customization**: Set album art corner radiuses or crop artwork to square templates.
  - **Gestures**: Swap tracks easily by swiping left/right on the player artwork (with adjustable sensitivity).

- **Fluid & Word-Synced Lyrics (Lyrics V2)**:
  - Powered by a premium, fluid word-synchronized lyrics engine (Apple Music style).
  - Customize text alignment (Left, Center, Right), adjust text size (16sp to 36sp), and modify line spacing.
  - Choose animated lyric transitions: None, Fade, Glow, Slide, Karaoke, or Apple Music style.
  - Interactive playback: Tap any lyric line to skip or seek directly to that exact part of the track.

---

## 🔄 Seamless In-App Updates

Stay up-to-date with new feature releases directly inside the application:

- **Update Notifications**: Receive a push notification the moment a new release is available on GitHub.
- **Direct Settings Navigation**: Clicking the update notification takes you straight to **Settings -> Updates**.
- **In-App Download & Installation**: View your current version alongside the latest release. Tap to download and install the update directly inside the app, with fallback sources and installer prompt setups.

---

## ⚡ Optimizations & Stability (v4.3.5)

- **Zero-Crash Shield**: Safe background exception handling across coroutines and services, eliminating unexpected crashes and crash report dialogs (`DebugActivity`).
- **Service Protection**: Prevents background service initialization crashes on Android 12+ and Android 14+.
- **Custom Buffering**: 150s/300s buffer durations for smooth playback on slow networks.
- **Adaptive Quality**: Auto-detects network conditions (2G/3G/4G/WiFi) and adjusts audio bitrate accordingly.
- **Large Storage Cache**: Up to 2GB song cache for repeated listening without re-downloading.
- **Image Memory Cache**: Faster album art loading and smooth scroll performance.
- **Network Resilience**: 30s connect / 60s read timeouts with automatic connection retries on failure.
- **R8 Full Optimization**: Compact APK size with faster app cold startup time.

---

## Requirements

- Android 8.0+ (API 26)
- Internet connection for streaming

