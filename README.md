# NexBeat

**NexBeat** is a modern, feature-rich music player for Android built with Kotlin and Jetpack Compose.

---



## Features

- YouTube Music streaming & search
- Offline downloads for offline playback
- Multi-provider lyrics (LrcLib, KuGou, YouTube, SimpMusic)
- Built-in audio equalizer with bass boost and virtualizer
- Discord Rich Presence integration
- Last.fm & ListenBrainz scrobbling
- "Together" — synchronized remote listening with friends
- Customizable themes and dynamic colors
- Optimized for low-bandwidth networks and mobile data

---

## Requirements

- **Android 8.0+** (API 26)
- Internet connection required for streaming

---

## Optimizations (v4.2)

- **Custom buffering**: 150s/300s buffer durations for smooth playback on slow networks
- **Adaptive quality**: Auto-detects 2G/3G/4G/WiFi and adjusts audio bitrate accordingly
- **Large cache**: 2GB song cache for repeated listening without re-downloading
- **Image memory cache**: Faster album art loading
- **Network resilience**: 30s connect / 60s read timeouts, automatic retry on failure
- **R8 full optimization**: Smaller APK, faster startup
