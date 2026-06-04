# NexBeat

**NexBeat** — A modern, open-source music player for Android built with Kotlin & Jetpack Compose. Powered by YouTube Music.

> This repository hosts **GitHub Releases** for automatic in-app updates.  


---

## Downloads

| Version | Date | APK | Size |
|---------|------|-----|------|
| v4.3.1 | 2026-06-03 | [NexBeat-v4.3.1-universal-release-optimized.apk](https://github.com/PandaSL2/NexBeat/releases/tag/v4.3.1) | 34.9 MB |

All APKs are **universal** (supports arm64-v8a, armeabi-v7a, x86, x86_64).

---
<img width="720" height="1612" alt="Screenshot_20260604_071031_com_theek_nexbeat_MainActivity" src="https://github.com/user-attachments/assets/48837826-8884-4c26-a5cb-9d1bfe597d19" />
<img width="720" height="1612" alt="Screenshot_20260604_071035_com_theek_nexbeat_MainActivity" src="https://github.com/user-attachments/assets/154415f1-54ac-4839-baac-40a79c5e1a16" />
<img width="720" height="1612" alt="Screenshot_20260604_071055_com_theek_nexbeat_MainActivity" src="https://github.com/user-attachments/assets/ffdffec8-0938-4bc9-9c29-706b554d7028" />

---

## Core Features

- **YouTube Music Streaming**: Full access to YouTube Music catalog, album streaming, and smart search.
- **Offline Downloads**: High-fidelity caching and downloading for uninterrupted offline playback.
- **Discord Rich Presence**: Share what you are listening to in real-time on Discord.
- **Scrobbling Support**: Full integration with Last.fm & ListenBrainz to log and track your listening history.
- **"Together" Listening**: Synchronize playback with friends remotely for shared listening sessions.
- **Built-in Equalizer**: Multi-band hardware audio equalizer with Bass Boost and Virtualizer support.

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

## Requirements

- Android 8.0+ (API 26)
- Internet connection for streaming

---

## Optimizations (v4.3.1)

- **Custom buffering**: 150s/300s buffer durations for smooth playback on slow networks
- **Adaptive quality**: Auto-detects 2G/3G/4G/WiFi and adjusts audio bitrate accordingly
- **Large cache**: 2GB song cache for repeated listening without re-downloading
- **Image memory cache**: Faster album art loading
- **Network resilience**: 30s connect / 60s read timeouts, automatic retry on failure
- **R8 full optimization**: Smaller APK, faster startup
