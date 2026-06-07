# Frequently Asked Questions — 4K Video Downloader

> **Last updated: June 2026**

Find answers to the most common questions about downloading 4K videos with our free video downloader for Windows.

---

## 🆓 Pricing & License

### Is 4K Video Downloader really free?
**Yes, 100% free.** No subscription, no premium tier, no trial period, no hidden fees. Download and use it forever at absolutely no cost.

### Is the source code open?
Yes. This project is open source under the MIT license. You can view, audit, modify, and distribute the code freely. See [LICENSE](LICENSE).

### Will it stay free?
Yes. This project is community-maintained and free forever. We accept voluntary donations to cover server costs, but the software itself will always be free.

---

## 🔒 Safety & Privacy

### Is it safe to use?
**Completely safe.** The software contains no malware, spyware, adware, or any malicious code. You can verify the SHA256 checksum of the installer on the Releases page. The source code is publicly available for anyone to audit.

### Does it collect my data?
**Absolutely not.** 4K Video Downloader does not collect any personal data, browsing history, download history, or usage statistics. Everything runs locally on your computer.

### Will antivirus flag it?
Some antivirus software may show a false positive for new executables. This is a known issue with all new software. The installer is digitally signed. You can verify the signature by right-clicking the installer → Properties → Digital Signatures.

### Does it upload my videos anywhere?
**No.** All downloads happen directly between your computer and the source website. We never upload, process, or store any of your content.

---

## 📥 Downloading

### What video qualities can I download?
You can download in: 8K, 4K Ultra HD (2160p), 1080p Full HD, 720p HD, 480p, 360p, 240p. Available qualities depend on what the source website provides.

### Can I download YouTube videos in 4K?
**Yes.** Paste a YouTube video URL, click "Paste URL", and select 4K from the quality dropdown. Note: some YouTube videos may not have 4K available if the uploader didn't upload in 4K.

### Can I download entire YouTube playlists?
**Yes.** Just paste the YouTube playlist URL (it looks like `youtube.com/playlist?list=...`). The app will fetch all videos in the playlist and download them.

### Can I download YouTube channels?
**Yes.** Paste the channel URL and the app will list all videos. You can select all or choose specific ones to download.

### Can I download TikTok videos without watermark?
**Yes.** 4K Video Downloader downloads TikTok videos from the original source, which does not include the watermark overlay.

### Can I download Instagram Reels?
**Yes.** Paste the Instagram Reel or post URL. For private content, you need to import your Instagram cookies from your browser.

### What happens if a download fails?
The download manager will automatically retry. If it keeps failing, try: (1) updating the app, (2) checking if the video is still available, (3) checking your internet connection.

### Can I pause and resume downloads?
**Yes.** Click the Pause button next to any download. Downloads resume from where they left off — you won't re-download what's already been saved.

### How fast does it download?
Download speed is only limited by your internet connection. On a 100 Mbps connection, a typical 1 GB 4K video downloads in 1-2 minutes.

---

## 🎵 Audio

### Can I extract just the audio from a video?
**Yes.** When adding a URL, select "Audio Only" from the format dropdown. You can save as MP3, AAC, FLAC, OGG, or M4A.

### What's the maximum MP3 quality?
Up to **320 kbps** constant bitrate, which is indistinguishable from lossless audio for most listeners.

### Can I download just the audio from a YouTube playlist?
**Yes.** Paste the playlist URL and select "Audio Only" + "MP3" before starting the download.

---

## 🌐 Supported Sites

### How many websites are supported?
Over **1,000 websites** are supported. See [SUPPORTED_SITES.md](SUPPORTED_SITES.md) for the full list.

### Does it work with YouTube, TikTok, Instagram?
**Yes** to all three. It also supports Vimeo, Twitter/X, Facebook, Twitch, Kick, Rumble, Dailymotion, Reddit, Pinterest, SoundCloud, and hundreds more.

### Can I download from streaming services like Netflix or Disney+?
**No.** These services use DRM (Digital Rights Management) protection which prevents downloading. We do not support DRM circumvention.

### The website I want isn't supported. Can you add it?
Open a [Feature Request](https://github.com/fiagotvfnl/4k-video-downloader/issues/new?template=feature_request.md) with the website URL and we'll look into adding support.

---

## ⚙️ Technical

### What Windows versions are supported?
Windows 10 (64-bit) and Windows 11 (64-bit). 32-bit systems are not supported.

### Does it work on Mac or Linux?
Currently, the application is Windows-only. A cross-platform version may be released in a future update.

### Does it need an internet connection to run?
Only for downloading videos. The app itself opens without internet. You can manage your already-downloaded video library offline.

### Does it use hardware acceleration?
Yes, if you have a compatible GPU. NVIDIA NVENC, AMD VCE, and Intel Quick Sync Video are supported for faster processing.

### Can I use it from the command line?
**Yes.** The app includes a CLI interface. Run `4kvd.exe --help` from PowerShell or Command Prompt for documentation.

### Is there a browser extension?
**Yes.** A Chrome/Edge extension is available that adds a download button directly on YouTube, Vimeo, and other supported sites.

---

## 🐛 Troubleshooting

### The app shows "Unable to extract video info"
This usually means the website changed their API. Update the app to the latest version — we push updates within 24-48 hours of breaking changes.

### I get a Windows SmartScreen warning
Click **"More info"** then **"Run anyway"**. This appears for all new software on Windows. The app is safe.

### Downloads are very slow
Try: (1) enabling hardware acceleration in Settings, (2) increasing the number of parallel connections, (3) checking if your ISP throttles video streaming.

### The video downloads but has no audio
This is a codec issue. In Settings, enable "Always use H.264" to ensure maximum compatibility.

### "Error 429 Too Many Requests"
You're making too many requests too fast. Enable the rate limiting option in Settings to add delays between requests.
