<p align="center">
  <img src="https://raw.githubusercontent.com/jrushengodas/YTM-GODAS-STREAMERBOT/main/assets/logo.jpg" width="400">
</p>

<h1 align="center">YTM Song Request V3.1</h1>

<p align="center">
  Advanced YouTube Music Song Request System for Streamer.bot
  <br>
  Built for stability, automation and large Twitch communities.
</p>

<p align="center">
  <a href="https://github.com/jrushengodas/YTM-GODAS-STREAMERBOT/releases/latest/download/YTM-GODAS-STREAMERBOT.zip">
    <img src="https://img.shields.io/badge/⬇️_DOWNLOAD-COMPLETE_PACKAGE-00ff99?style=for-the-badge&logo=github&logoColor=white">
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/status-stable-green">
  <img src="https://img.shields.io/badge/version-3.1-blue">
  <img src="https://img.shields.io/badge/Streamer.bot-compatible-purple">
  <img src="https://img.shields.io/badge/YTMDesktop-supported-red">
  <img src="https://img.shields.io/badge/API-MultiKeys-orange">
</p>

---

# Features

```text
✅ Song Request via !sr
✅ Priority Song Requests
✅ Local intelligent queue system
✅ YouTube & YouTube Music links support
✅ Search by title + artist
✅ Multi YouTube API Keys support
✅ Smart retry system
✅ Auto cache system
✅ Queue cleaner
✅ Auto stuck song detection
✅ Auto skip protection
✅ Fake current detection
✅ Frozen YTM protection
✅ Playlist compatibility
✅ Current / next song commands
✅ Playlist viewer
✅ Streamer.bot compatible
✅ YouTube Music Desktop compatible
```

---

# What's New In V3.1

V3.1 introduces a major rewrite focused on stability and YTM Desktop reliability.

### New protections

```text
✅ Fake current detection
✅ Auto skip on frozen songs
✅ Auto timeout protection
✅ Better queue synchronization
✅ Stuck song detection
✅ Improved cache validation
✅ Better YTM Desktop handling
✅ Invalid API key protection
✅ Retry logic improvements
✅ Better local queue cleanup
```

---

# Intelligent Search System

The search engine automatically analyzes :

```text
✅ Song title
✅ Artist name
✅ Official audio
✅ Official video
✅ VEVO channels
✅ Official channels
✅ Topic channels
```

Automatically avoids :

```text
❌ YouTube Shorts
❌ sped up
❌ slowed
❌ nightcore
❌ remix
❌ TikTok edits
❌ reactions
❌ karaoke
❌ playlists
❌ compilations
❌ live versions
```

---

# Architecture

```text
Viewer
   ↓
Streamer.bot
   ↓
GODAS Local Queue
   ↓
Watcher V3.1
   ↓
YouTube Music Desktop
```

---

# Commands

```text
!sr music          → Add a song
!song              → Current song
!next              → Next YTM song
!nextsr            → Next local SR
!playlist          → Show SR queue
!skip              → Skip current song
!prio music        → Priority SR
!clear             → Clear queue
```

---

# Watcher V3.1 Protections

```text
✅ Detects fake current songs
✅ Handles frozen YTM states
✅ Detects songs stuck at 0:00
✅ Auto skip system
✅ Queue synchronization
✅ Cooldown protection
✅ Duplicate prevention
✅ Broken queue protection
✅ Invalid queue cleanup
```

---

# Multi API Keys System

Supports multiple YouTube API Keys :

```text
✅ Automatic key rotation
✅ Quota protection
✅ Retry system
✅ Invalid key detection
✅ Massive SR capacity
```

Example :

```json
[
  "API_KEY_1",
  "API_KEY_2",
  "API_KEY_3"
]
```

---

# Compatibility

```text
✅ Streamer.bot
✅ YouTube Music Desktop
✅ Companion Server
✅ Twitch Chat Commands
```

---

# Requirements

```text
- Streamer.bot
- YouTube Music Desktop
- Companion Server enabled
- Port 26538
- YouTube API Keys
```

---

# Installation

## 1. Install YouTube Music Desktop

Enable :

```text
Settings → Integrations → Companion Server
```

Default port :

```text
26538
```

---

## 2. Import Streamer.bot Package

Import :

```text
YTM-GODAS-STREAMERBOT.zip
```

---

## 3. Configure API Keys

Add your YouTube API Keys :

```text
youtubeApiKeys_godas
```

Example :

```json
[
  "AIzaSyXXXXXXXX",
  "AIzaSyYYYYYYYY",
  "AIzaSyZZZZZZZZ"
]
```

---

## 4. Enable Watcher

Enable :

```text
YTM - Auto SR Watcher
```

Recommended interval :

```text
5 seconds
```

---

# Troubleshooting

Check :

```text
- YTM Desktop is running
- Companion Server enabled
- Port 26538 open
- API Keys valid
- Watcher enabled
- Queue variables initialized
```

If YTM freezes :

```text
1. Disable autoplay
2. Clear YTM queue
3. Run !clear
4. Restart playback manually
```

---

# Technologies

```text
- Streamer.bot
- C#
- Newtonsoft.Json
- YouTube Data API v3
- YouTube Music Desktop
```

---

# Credits

### Development

```text
Godas DEV
```

### Special thanks

```text
Twitch community testers
```

---

<p align="center">
  <strong>YTM Song Request System V3.1</strong>
  <br>
  Developed by <strong>Godas DEV</strong>
  <br><br>
  <img src="https://img.shields.io/badge/GODAS-DEV-00ff99?style=for-the-badge">
</p>
