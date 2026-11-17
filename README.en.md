<div align="center">

<p align="center"><img src="assets/readme/hero-en.svg?v=obsidian-loop-2" width="1120" alt="MediaLatch — save media, preview and organize"></p>

[![Chrome Web Store — Install](https://img.shields.io/badge/Chrome_Web_Store-Install-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white)](https://chromewebstore.google.com/detail/medialatch/cimghidldpjhhhngdhigddjfpcofhbmh)

[![Stars](https://img.shields.io/github/stars/NoizWorks/MediaLatch?style=for-the-badge&color=22D3EE)](https://github.com/NoizWorks/MediaLatch/stargazers)
[![Release notes](https://img.shields.io/badge/GitHub-Releases-E11D48?style=for-the-badge)](https://github.com/NoizWorks/MediaLatch/releases)
[![Chromium](https://img.shields.io/badge/Chromium-120%2B-22D3EE?style=for-the-badge&logo=googlechrome&logoColor=white)](https://github.com/NoizWorks/MediaLatch)
[![Manifest V3](https://img.shields.io/badge/Manifest-V3-10B981?style=for-the-badge)](docs/PRIVACY.md)
[![Email](https://img.shields.io/badge/Email-Contact-64748B?style=for-the-badge)](mailto:always1337@vk.com)
[![Boosty](https://img.shields.io/badge/Boosty-Support-FF6A00?style=for-the-badge&logo=boosty&logoColor=white)](https://boosty.to/fs0x1337)
[![License](https://img.shields.io/badge/license-Proprietary-A6A6AF?style=for-the-badge)](LICENSE)

[**🇷🇺 Русский**](README.md) | [**🇬🇧 English**](README.en.md)

</div>

<p align="center"><img src="assets/readme/divider.svg?v=obsidian-loop-2" width="1120" alt=""></p>

MediaLatch saves to your computer, Google Drive or Yandex Disk. Each destination has its own saving rules. See [project status](docs/STATUS.md) for development features.

[Product website](https://noizworks.is-a.dev/medialatch/) · [Cloud setup](docs/CLOUD.md)


## About

**MediaLatch** saves the images, videos and GIFs you select on a page. Use the browser menu or controls on supported sites, follow each file in the download manager, and open saved media in the built-in viewer.

Configure folders, names for new files, notices and optional statistics. No companion app is required. The extension has no backend or telemetry.

<p align="center"><img src="assets/readme/divider.svg?v=obsidian-loop-2" width="1120" alt=""></p>

## Installation and updates

<img src="assets/readme/install-en.svg?v=store-only" width="1120" alt="Install and update MediaLatch exclusively through Chrome Web Store">

Install and update MediaLatch **exclusively through [Chrome Web Store](https://chromewebstore.google.com/detail/medialatch/cimghidldpjhhhngdhigddjfpcofhbmh)**. The Store delivers updates automatically.

[GitHub Releases](https://github.com/NoizWorks/MediaLatch/releases) contains release notes. The automatic **Source code** archives contain this repository's documentation and artwork.

## Features in 3.0.7

This version is available from Chrome Web Store. [Version 3.1.0](docs/STATUS.md#development-build) is awaiting manual testing before Store submission.

| Task | Available behavior |
| --- | --- |
| Save selected media | Original-image discovery, progressive MP4/WebM and supported GIFs. Exact signed URLs stay intact. |
| Save a post | Multiple files from posts on X, Reddit, Pixiv, Pawchive and supported VK pages. See each file's result and cancel the remaining downloads. |
| Choose a destination | Browser Downloads, an explicitly selected folder, Google Drive or Yandex Disk. Separate profiles, ordered levels and custom templates. |
| Name new files | Original basename or selected site/account and UTC download-start or known publication date/time fields. Metadata-based names omit the CDN basename; unknown fields are skipped. |
| Preview saved media | Images, animated GIFs and MP4 with playback controls; fit/100%, zoom, pan, carousel buttons, arrow keys and swipe. |
| Track results | Popup, manager, page notices, optional statistics, retry and cancellation. Filters for images/GIFs and videos. |
| Copy preview links | 12 settings for X, Instagram, TikTok, YouTube videos/Shorts, Reddit, Pixiv, Bluesky, Threads, Twitch, Tumblr and Bilibili. Link conversion runs locally. |
| Adjust the interface | Violet, Red, Blue, Dark and Light themes; English/Russian; keyboard navigation and reduced motion. |
| Read release history | Browse release notes offline, with an Installed label on the matching version. |

Click a thumbnail in the manager to open the viewer. From the popup, it opens over the active tab; from a page notice, it opens over the source page. The viewer runs in an isolated extension frame. On restricted browser pages, it opens in the manager. Small previews appear on hover.

In 3.0.7 the local cache holds up to 2,048 thumbnails and 256 preview originals: 128 MiB per original, 512 MiB total and 30-day availability. If a file is too large or no longer cached, choose it from disk. The cache does not replace a backup or change saved files. Codec support depends on the browser.

### History and statistics

Open Overview → Local data and backups to export statistics and history as separate JSON files. Confirmed statistics restore replaces counters; history import adds missing records without starting downloads. Limits: 32 MiB UTF-8 per file and up to 50,000 history records per copy. Copies exclude media, source URLs and folder grants. History renders in windows while search covers the full retained list. [Details](docs/LOCAL_DATA.md).

### Cloud saving

Choose this PC, Google Drive or Yandex Disk in Storage or the popup. Each destination keeps its own folder and naming profile. Ordinary inline Download stays local; selecting a cloud reveals adjacent selected/all gallery actions. Connect by OAuth or an access token; files go directly to the provider. [Setup and limits](docs/CLOUD.md).

### Folders and filenames

```text
Downloads/
└── SavedImages/
    ├── x/posting_account/Image/photo.jpg
    ├── reddit/posting_account/Videos/clip.mp4
    └── danbooru/uploader/Image/artwork.jpg
```

Choose folder levels in order: site, account, media type, extension, date, year–month or year. Custom templates are available; levels with unavailable metadata are skipped. Account folders are enabled separately for supported services. Matched Danbooru/Moebooru posts can use a verified uploader; artist tags do not become account identity.

Choose download-start or known publication dates for filenames, and which services use the rule. Publication comes only from verified X or supported Booru metadata; unknown values are skipped. Folder date levels use publication or operation-start time in UTC. Universal setup fills all three profiles while retaining their subfolders and labels. Changes affect new files.

Customize image, video and GIF folder labels independently for the `{type}` level. Defaults are `Image`, `Videos` and `GIF`; an empty field restores its default. Only the type level for new saves changes: custom labels, admitted job paths and existing files are preserved. Literal `Images` in a template remains one shared folder, not a media-type switch.

If the browser requests access to a saved folder again, use Restore folder access in settings. The selected destination stays saved. Completed browser downloads can show their file in its folder after verification. Direct chosen-directory exports explain the file-manager API limitation; no system companion is required.

When names match, the extension adds a suffix, even after history and statistics are cleared. Existing files are not overwritten. Long filenames may be shortened to fit path limits. The browser or filesystem may still reject an excessively long Windows path.

<details>
  <summary>Saving settings</summary>
  <img src="assets/screenshots/saving-en.jpg?v=obsidian-20261117" alt="Folder and filename settings" width="1280">
</details>

<p align="center"><img src="assets/readme/divider.svg?v=obsidian-loop-2" width="1120" alt=""></p>

## From selection to file

<p align="center"><img src="assets/readme/flow-en.svg?v=obsidian-loop-2" width="1120" alt="Select media → verify its source and bytes → save → local preview"></p>

The extension finds the selected media's original, checks the source and file, then saves it to the destination folder. It does not substitute a file from a neighboring post.

## Site coverage

A site having Copy does not imply support for downloading its media. Twitch VODs retain their original address; playback, audio and galleries depend on the selected mirror and messenger. Reload already open site tabs after updating the extension.

Support depends on the selected media, page layout and your access to the source.

| Site or family | Scope |
| --- | --- |
| X / Twitter | Images and video, conversion of supported MP4 animations to GIF, and multiple files from a post. |
| Reddit | Images, native GIFs, declared progressive video and bounded unencrypted H.264/AAC HLS VOD. |
| Pixiv | The original of the selected artwork page or its verified page list; account folders. |
| RedGIFs | Selected images and player media, including supported separate-audio recovery. |
| VK / VK Video | Photos, supported carousels, collages and feed videos, preview cards, opened players and native clip downloads. Experimental; other layouts and audio need further testing. |
| TikTok / Instagram | Supported selected-video/Reel controls and posting usernames; separate-track-only feed sources can be unavailable. |
| Pawchive / Sankaku | Originals linked to the selected post. Incomplete archive imports are marked. |
| Booru families | Selected originals on supported engines, subject to authentication and site limits. |
| Other HTTP(S) pages | Image attributes, srcset, metadata and links to the selected image's original. There is no universal video search. |

DRM, live streams, universal HLS/DASH, arbitrary gallery selection and YouTube downloads are not supported. A 403, expired URL, missing original or unsupported stream is reported as a failure. Files from neighboring posts are not used as a fallback.

## Interface

The current development interface in **Obsidian**, with sample data. The new build will be manually tested before publication. [Provenance](assets/screenshots/provenance.json).

<details open><summary>Download manager</summary>

![Download manager](assets/screenshots/downloads-en.jpg?v=obsidian-20261117)

![Gallery](assets/screenshots/gallery-en.jpg?v=obsidian-20261117)

</details>
<details><summary>Statistics, popup and viewer</summary>

![Statistics](assets/screenshots/statistics-en.jpg?v=obsidian-20261117)
![Popup](assets/screenshots/popup-en.jpg?v=obsidian-20261117)
![Viewer](assets/screenshots/viewer-en.jpg?v=obsidian-20261117)

</details>

<p align="center"><img src="assets/readme/divider.svg?v=obsidian-loop-2" width="1120" alt=""></p>

## Privacy and security

MediaLatch has no backend or telemetry. Downloads contact the selected site, service or CDN. Settings, the queue, optional statistics, diagnostics and preview caches stay in extension storage. Release checks contact GitHub. Chrome Web Store delivers extension updates.

Page notices show a short download result. Folder grants and local paths stay private. A cloud save sends the selected file, its name and folder layout directly to the chosen provider. You can export reports and diagnostics manually; review the contents before sharing. HTTP/HTTPS permissions let the extension find selected media across sites. See the [privacy policy and permission explanations](docs/PRIVACY.md).

Report bugs, problems and vulnerabilities to [always1337@vk.com](mailto:always1337@vk.com) or [Issues](https://github.com/NoizWorks/MediaLatch/issues). Send vulnerability details and sensitive data by email. See the [Security Policy](SECURITY.md) for what to include and how to test.

## Support the project

Support development on [Boosty](https://boosty.to/fs0x1337), [DonationAlerts](https://dalink.to/fs0x1337) or [CloudTips](https://pay.cloudtips.ru/p/da0d3dbe). Send questions and feedback to [@fs0x1337](https://t.me/fs0x1337) on Telegram, [Issues](https://github.com/NoizWorks/MediaLatch/issues) or [email](mailto:always1337@vk.com).

## License

Starting with 3.0.0, project-owned code and artwork use the [proprietary license](LICENSE). Earlier GPL recipients keep their existing rights. Third-party components retain their [licenses and notices](THIRD_PARTY_NOTICES.txt).

Development source and its Git history are kept separately. The JavaScript inside a CRX can still be inspected after minification.

[Changelog](CHANGELOG.md) · [Privacy](docs/PRIVACY.md) · [Security Policy](SECURITY.md) · [Boosty](https://boosty.to/fs0x1337)



[Website](https://noizworks.is-a.dev/medialatch/) · [Privacy policy](https://noizworks.is-a.dev/privacy.html)
