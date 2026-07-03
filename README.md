# NexBeat

**NexBeat** — A modern, open-source music player for Android built with Kotlin & Jetpack Compose. Powered by YouTube Music.

> This repository hosts **GitHub Releases** for automatic in-app updates.  


---

## Downloads

| Version | Date | APK | Size |
|---------|------|-----|------|
| v4.3.1 | 2026-07-03 | [NexBeat-v4.3.2-universal-release.apk](https://github.com/PandaSL2/NexBeat/releases/tag/v4.3.2) | 34.9 MB |

All APKs are **universal** (supports arm64-v8a, armeabi-v7a, x86, x86_64).

---

<img width="357" height="800" alt="Screenshot_20260604_071823_com_theek_nexbeat_MainActivity (1)" src="https://github.com/user-attachments/assets/2440d955-6ac5-4273-9c5c-0e7ef3bd79a3" />

---

## Core Features

- **Multi-Source Streaming & Integration**:
  - **YouTube Music Streaming**: Access the entire YouTube Music catalog, search songs, play albums, and explore charts.
  - **Spotify & Apple Music Connections**: Seamlessly connect, import, and sync metadata or playlists from Spotify and Apple Music via dedicated plugins.
  - **Local Music Library**: Scan and organize local audio files (MP3, FLAC, M4A, etc.) from device storage with high-fidelity local playback.
- **Offline Downloads & Caching**: Download tracks for uninterrupted offline listening with smart storage caching.
- **Discord Rich Presence**: Share what you are listening to in real-time directly on Discord.
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
