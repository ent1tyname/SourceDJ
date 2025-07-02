# SourceDJ 🎷

**SourceDJ** is a lightweight, closed-source `.dll` plugin for the **Source Engine 2006** (Counter-Strike: Source v34) that streams music into in-game **voice chat** using a simple and clean **ImGui-based interface**.

No console commands. No extra setup. Just press `Insert` and play.

Note: this software requires a microphone to function.

---

## ✨ Features

* Play music through in-game voice chat (hearable by all players)
* Modern **ImGui user interface**
* Simple file browser for selecting tracks
* Built-in **libav** (FFmpeg) audio decoding
* All dependencies included — no need to install anything else
* Supports HPF Filter, mp3, m4a, and other audio, rewind, playlists

---

## 📅 Installation

1. Download the latest build from the [Releases](https://github.com/yourname/SourceDJ/releases).
2. Extract everything into your game's root folder:
3. Launch CS\:S v34
4. Press **`Insert`** in-game to open the **SourceDJ Menu**
5. Select and play any track from the interface
6. Hold `K` (or another configured key) to play music; release it to pause, when needed.

> 🔊 Make sure in-game voice chat is enabled. Music is transmitted via your microphone stream.

---

## 🎺 Controls

| Key      | Action                  |
| -------- | ----------------------- |
| `Insert` | Open/Close SourceDJ UI  |

---

## 🗃️ Folder Structure

```
/srcdj/
├── bin/
│   ├── avcodec-55.dll
│   ├── avdevice-55.dll
│   ├── avfilter-3.dll
│   ├── avformat-55.dll
│   ├── avutil-52.dll
│   ├── postproc-52.dll
│   ├── swresample-0.dll
│   ├── swscale-2.dll
│   └── sourcedj.dll
├── cstrike/
│   └── addons/
│       └── sourcedj.vdf
└── sounds/
    └── cue.mp3
```

---

## 📄 License

* This project is proprietary and distributed under a custom license. See [LICENSE](./LICENSE)
* Source code is not public.

---

## 🤋 Feedback & Contact

* 💬 Found an issue? Contact the developer directly
* 📬 Developer: `@entityname` on Telegram

---
