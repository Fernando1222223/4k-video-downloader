# Changelog — 4K Video Downloader

All notable changes to this project are documented here.
Format follows [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

---

## [3.0.0] — June 2026 *(Latest)*

### Added
- **8K video download support** — Download 7680×4320 videos from supported sources
- **AV1 codec support** — 50% smaller files at the same visual quality
- **Batch URL import** — Import hundreds of URLs from a `.txt` file at once
- **Hardware acceleration** — NVIDIA NVENC, AMD VCE, Intel QSV encoding
- **Subtitle auto-embed** — Automatically embed subtitles into MKV/MP4 output
- **Thumbnail download** — Save video thumbnails alongside downloads
- **New CLI commands** — Full command-line interface for automation and scripting
- **Browser extension** for Chrome and Edge
- **Windows 11 taskbar progress** — Download progress shown in taskbar
- **Dark mode improvements** — True OLED-ready dark theme

### Changed
- Completely redesigned UI — modern, clean, fast
- YouTube engine rewritten — 3× faster playlist parsing
- TikTok watermark removal is now 100% reliable
- Default output format changed from AVI to MP4
- Maximum concurrent downloads increased from 8 to 16

### Fixed
- Fixed Instagram Stories not downloading correctly
- Fixed Twitter/X videos failing on long videos
- Fixed Vimeo 4K downloads requiring login unnecessarily
- Fixed memory leak on large playlist downloads
- Fixed crash when pausing during first 5 seconds of download

---

## [2.5.0] — February 2026

### Added
- **Kick.com** support — download streams and clips
- **Rumble** support — full video and channel support
- **YouTube Shorts** batch download support
- MP3 quality option up to 320 kbps
- Auto-rename on duplicate files
- Bandwidth throttling option (limit download speed)

### Changed
- Improved YouTube anti-bot bypass
- Faster metadata fetching (2× improvement)
- Better error messages with suggested fixes

### Fixed
- Fixed Twitch VOD downloads failing after API change
- Fixed playlist download stopping at video 50
- Fixed app freezing on Windows 10 when starting

---

## [2.0.0] — October 2025

### Added
- **Playlist sync** — Automatically check playlists for new videos
- **Proxy support** — HTTP and SOCKS5 proxy configuration
- **Cookies import** — Import browser cookies for private/age-restricted content
- **Quality profiles** — Save preferred quality settings per website
- **Windows Task Scheduler** integration for scheduled downloads

### Changed
- New download engine — 40% faster on average
- Redesigned settings panel
- Better 4K HDR handling on Windows 11

### Fixed
- Numerous bug fixes and stability improvements

---

## [1.5.0] — May 2025

### Added
- Instagram Reels download support
- Facebook Watch video support
- Discord video link support
- FLAC audio extraction

### Changed
- Updated YouTube downloader engine
- Improved TikTok support

---

## [1.0.0] — January 2025

### Initial Release
- YouTube download (up to 4K)
- TikTok download without watermark
- Instagram photo and video download
- Vimeo 4K download
- Twitter/X video download
- MP4, MKV, MP3, AAC output formats
- Playlist download
- Batch download queue
- Windows 10/11 support
