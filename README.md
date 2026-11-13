<div align="center">

# Murmur

**Talk. It types.**

Hold a key, speak, let go. Clean, punctuated text lands wherever your cursor is.<br>
No account, no cloud, and no internet needed.

### [**→ Download at murmur-talk.vercel.app**](https://murmur-talk.vercel.app)

![macOS 14+](https://img.shields.io/badge/macOS-14%2B%20·%20Apple%20silicon-0f7a40?logo=apple&logoColor=white)
![Windows 10/11](https://img.shields.io/badge/Windows-10%20%2F%2011%20·%2064--bit-0f7a40?logo=windows&logoColor=white)
![Offline](https://img.shields.io/badge/runs-offline-3dff8f?labelColor=07120b)
![Free](https://img.shields.io/badge/price-free-3dff8f?labelColor=07120b)

</div>

---

## How it works

Murmur waits in the menu bar (Mac) or tray (Windows), shown only as a thin green line at the bottom of your screen.

| | Mac | Windows |
| --- | --- | --- |
| **Hold to talk** | `fn` | `Right Alt` |
| **Hands-free** | Double-tap the key, tap again to finish | Same |
| **Cancel** | `Esc` | `Esc` |

1. **Hold the key.** The line grows into a pill and its bars move with your voice.
2. **Say it naturally.** Ums, stutters and false starts are fine.
3. **Let go.** Cleaned-up text is typed right where you were, in email, docs, chat or code. Your clipboard is left as it was.

## It writes what you meant

Every dictation goes through a cleanup pass on your computer before it's typed.

| You say | Murmur types | |
| --- | --- | --- |
| "um so the launch is on track" | So the launch is on track. | Mac · Windows |
| "I I I think we're ready" | I think we're ready. | Mac · Windows |
| "first point new line second point" | First point.<br>Second point. | Mac · Windows |
| "meet me at ten thirty pm on march fifth" | Meet me at 10:30 PM on March 5 | Mac |
| "thanks comma see you soon" | Thanks, see you soon | Mac |

## Features

| Feature | | Mac | Windows |
| --- | --- | :---: | :---: |
| **Works offline** | Speech recognition runs on your own computer, even in airplane mode. | ✓ | ✓ |
| **Types into any app** | No plugins or integrations to set up. | ✓ | ✓ |
| **Hands-free mode** | Double-tap for longer thoughts; the bars turn orange while it listens. | ✓ | ✓ |
| **Learns your words** | Correct a name once and it remembers. Custom dictionary and shortcuts. | ✓ | Soon |
| **Voice commands** | "new tab", "select all", "scroll down", "volume up". | ✓ | |
| **Languages** | English and Hindi on Mac, with an optional offline auto-detect pack. | ✓ | English |

## Privacy

Your voice never leaves your computer. **0 servers · 0 accounts · 0 recordings kept.**

The only download the app ever makes is the speech model, once. On Windows that happens the first time you open it (about 190 MB).

## Install

Download from **[murmur-talk.vercel.app](https://murmur-talk.vercel.app)**. It picks the right version for your computer.

**Mac** — macOS 14 or later, Apple silicon. Drag Murmur into Applications and open it. If macOS says it can’t verify the app, click Done, then go to **System Settings → Privacy & Security** and click **Open Anyway**. Allow Microphone and Accessibility when asked.

**Windows** — Windows 10 or 11, 64-bit, no admin rights needed. If SmartScreen warns you, click **More info → Run anyway**. Murmur installs itself for your user and lives in the tray.

<details>
<summary><b>FAQ</b></summary>

**Is it really free?** Yes. No subscription, no trial, no account.

**Why does my OS warn me?** Murmur isn't code-signed yet. On Mac, open it once, then System Settings → Privacy & Security → **Open Anyway**. On Windows, More info → Run anyway.

**How do I change the key?** On Mac, open Settings from the menu bar icon (if you use `fn`, set System Settings → Keyboard → "Press 🌐 key to" → Do Nothing). On Windows, right-click the tray icon → Push-to-talk key (Right Alt, Right Ctrl or F8).

**How do I uninstall on Windows?** Right-click the tray icon → Uninstall Murmur, or use Settings → Apps → Installed apps. It also deletes the speech model.

</details>

---

## About this repository

This repo holds the source of the Murmur website, [murmur-talk.vercel.app](https://murmur-talk.vercel.app). Get the app from the website.

```
.
├── index.html    # the whole site: markup, styles and script in one file
├── vercel.json   # Vercel config: clean URLs and security headers
└── README.md
```

**Run locally** — no build step:

```bash
python3 -m http.server 4173
```

**Deploy** — hosted on Vercel at [murmur-talk.vercel.app](https://murmur-talk.vercel.app).

---

<div align="center">
Made by <a href="https://github.com/swaaaaaapnil">Swapnil</a>
</div>
