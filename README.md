# GrokMediaDownloader

**The ultimate Chrome extension for downloading and managing media from Grok AI.**

[![Chrome Web Store](https://img.shields.io/chrome-web-store/v/niebmpjbnghbfnjbbeajlndkjpgpamhi?label=Chrome%20Web%20Store)](https://chromewebstore.google.com/detail/grok-media-downloader/niebmpjbnghbfnjbbeajlndkjpgpamhi)
[![Chrome Web Store Users](https://img.shields.io/chrome-web-store/users/niebmpjbnghbfnjbbeajlndkjpgpamhi)](https://chromewebstore.google.com/detail/grok-media-downloader/niebmpjbnghbfnjbbeajlndkjpgpamhi)

## Links

- **Official Website**: [grokmedia.kario-studio.com](https://grokmedia.kario-studio.com)
- **Chrome Web Store**: [Install GrokMediaDownloader](https://chromewebstore.google.com/detail/grok-media-downloader/niebmpjbnghbfnjbbeajlndkjpgpamhi)
- **Publisher**: [Kario Studio](https://grokmedia.kario-studio.com)
- **Pricing**: [Free & PRO Plans](https://grokmedia.kario-studio.com/pricing.html)
- **FAQ**: [Frequently Asked Questions](https://grokmedia.kario-studio.com/faq.html)

## Features

### Tag-Based Download ✨ NEW
Download media from a specific Grok tag (folder). Select a tag, download all media within it. Each tag has separate download history, files organized under `tags/{tagName}/`.

### Custom Filename Templates ✨ NEW
Three filename modes: **Grok Native** (original format), **Prompt Based** (uses your prompt text), or **Custom** (free-form templates with tokens like `{date}`, `{prompt}`, `{quality}`). Available to all users.

### Video Generation Queue
Automatically queue and track multiple video generation tasks. Monitor progress and download completed videos in batch.
[Learn more →](https://grokmedia.kario-studio.com/video-gen-queue.html)

### Story Mode
Create multi-scene stories with consistent characters. Interactive filmstrip lets you select any frame for continuation. Frame Lock auto-locks your selection and trims on export for seamless transitions.
[Learn more →](https://grokmedia.kario-studio.com/story-mode.html)

### Batch Download
Select and download multiple images and videos at once. Filter by date range, export/import your media library.

### Stream Capture
Capture video streams in real-time as Grok generates them. No quality loss — get the original HD output.

### HD Upgrade
Automatically upgrade images to high-definition quality before downloading.

### Project Downloads
Download entire Grok projects with all associated media files organized in folders.

## Free vs PRO

| Feature | Free | PRO |
|---------|------|-----|
| Batch image download | ✅ | ✅ |
| Date range filter | ✅ | ✅ |
| Export/Import media list | ✅ | ✅ |
| Custom Filename Templates | ✅ | ✅ |
| Video stream capture | 3 per day | ✅ Unlimited |
| HD image upgrade | 5 per day | ✅ Unlimited |
| Video Generation Queue | 3 per day | ✅ Unlimited |
| Story Mode | 1 per day | ✅ Unlimited |
| Project downloads | 1 per day | ✅ Unlimited |
| Tag-Based Download | ❌ | ✅ |

**PRO License**: One-time purchase, lifetime access. [Get PRO →](https://grokmedia.kario-studio.com/pricing.html)

## Changelog

### v2.3.0 (Latest)
- **Tag-Based Download**: Download media by tag folder with separate download history per tag
- **Custom Filename Templates**: Three-mode filename selector (Grok Native / Prompt Based / Custom with tokens)
- **Frame Lock & Trim**: Select any frame via filmstrip for video continuation, auto-trim on export for seamless transitions
- **Queue fixes**: Fixed video post page redirect loop, "Make Video" button disabled state, and retry logic
- **HD Upgrade**: Proper await for upscale requests with rate limit handling and accurate failure tracking
- **Download abort**: Fixed cancel button state not updating properly

### v2.2.6
- Video download rate limit protection (auto-pause every 250 videos to avoid Grok 429 errors)
- Improved button naming (Clear Download Preview List / Reset Download History)
- Resume progress display (X/Y completed, click to continue)
- Button shows "Continue Download" after interruption
- Generate List real-time progress display
- Fixed 64MB Chrome messaging limit with large media items
- Memory usage optimization

### v2.2.5
- Bug fixes and performance improvements

### v2.2.0
- Added Video Generation Queue feature
- Multi-video batch generation and download

### v2.1.0
- Added Story Mode for multi-scene narratives
- Consistent character generation across scenes

### v2.0.0
- Major UI overhaul
- Added Stream Capture for real-time video download
- Added HD Upgrade for image quality enhancement
- Added Project Downloads

## Bug Reports & Feature Requests

Found a bug or have a feature idea? Please [open an issue](https://github.com/tomsonlee150/GrokMediaDownloader/issues) on this repository.

When reporting a bug, please include:
- Chrome version
- Extension version (shown in the extension popup)
- Steps to reproduce the issue
- Screenshots if applicable

## Privacy

GrokMediaDownloader respects your privacy. We do not collect personal data. Read our full [Privacy Policy](https://grokmedia.kario-studio.com/privacy.html).

## License

GrokMediaDownloader is proprietary software published by [Kario Studio](https://grokmedia.kario-studio.com). This repository is for issue tracking and documentation only — it does not contain the extension source code.

[Terms of Service](https://grokmedia.kario-studio.com/terms.html)
