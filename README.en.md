<div align="center">

<a href="https://noizworks.is-a.dev/medialatch/">
  <img src="https://noizworks.is-a.dev/medialatch/assets/hero-banner.webp" width="1280" alt="MediaLatch — media saving, cloud destinations, and Posts & Drafts studio">
</a>

<br>

[![Chrome Web Store](https://img.shields.io/badge/Chrome_Web_Store-Install-e11d48?style=flat-square&labelColor=0f1117&logo=googlechrome&logoColor=ffffff)](https://chromewebstore.google.com/detail/medialatch/cimghidldpjhhhngdhigddjfpcofhbmh)
[![v3.1.3](https://img.shields.io/badge/Release-v3.1.3-6366f1?style=flat-square&labelColor=0f1117)](https://github.com/NoizWorks/MediaLatch/releases/tag/v3.1.3)
[![Chromium 120+](https://img.shields.io/badge/Chromium-120%2B-222738?style=flat-square&labelColor=0f1117&logo=googlechrome&logoColor=cbd5e1)](https://github.com/NoizWorks/MediaLatch)
[![Manifest V3](https://img.shields.io/badge/Manifest-V3-222738?style=flat-square&labelColor=0f1117)](docs/PRIVACY.md)
[![Stars](https://img.shields.io/github/stars/NoizWorks/MediaLatch?style=flat-square&label=Stars&labelColor=0f1117&color=222738)](https://github.com/NoizWorks/MediaLatch/stargazers)
[![Boosty](https://img.shields.io/badge/Boosty-Support-6366f1?style=flat-square&labelColor=0f1117&logo=boosty&logoColor=ffffff)](https://boosty.to/fs0x1337)

<p>
  <a href="README.md">Русский</a> ·
  <strong>English</strong> ·
  <a href="https://noizworks.is-a.dev/medialatch/">Website</a> ·
  <a href="https://github.com/NoizWorks/MediaLatch/releases/tag/v3.1.3">Release Notes v3.1.3</a> ·
  <a href="docs/PRIVACY.md">Privacy Policy</a> ·
  <a href="SECURITY.md">Security</a>
</p>

<p>
  <strong>MediaLatch</strong> is a Chromium extension that saves original images, videos, and GIFs using your folder rules, delivers files locally or to cloud storage, and prepares posts for Telegram and VK. No backend, no telemetry, and no companion app.
</p>

</div>

---

## Interface & Capabilities in v3.1.3

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://noizworks.is-a.dev/medialatch/assets/hero-downloads.webp">
        <img src="https://noizworks.is-a.dev/medialatch/assets/hero-downloads.webp" width="100%" alt="MediaLatch Downloads gallery (3×/4×/5×), native 424×540 Popup, and cloud destination profiles">
      </a>
      <br>
      <strong>Downloads, Gallery &amp; Cloud Profiles</strong><br>
      Collapsible site groups (<code>3× / 4× / 5×</code>), built-in media viewer, and the native <code>424×540</code> popup with <code>~4×</code> faster search. Separate folder and naming profiles for <code>Local</code>, <code>Google Drive</code>, <code>Yandex Disk</code>, <code>MEGA</code>, and <code>Telegram</code>.
    </td>
    <td width="50%" valign="top">
      <a href="https://noizworks.is-a.dev/medialatch/assets/hero-posts.webp">
        <img src="https://noizworks.is-a.dev/medialatch/assets/hero-posts.webp" width="100%" alt="Three-column Posts & Drafts studio: local drafts, composer, and live Telegram and VK preview">
      </a>
      <br>
      <strong>Posts &amp; Drafts Studio</strong><br>
      Three-column workspace: <code>Local drafts</code>, composer with <code>Cred: {author}</code> and default <code>#hashtags</code>, and live Telegram / VK preview. Inline <code>✈</code> post prep on X and 37 Booru sites with auto-parsed <code>Source:</code>, <code>Queue (+2h)</code> scheduling, and duplicate protection.
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://noizworks.is-a.dev/medialatch/assets/hero-inline.webp">
        <img src="https://noizworks.is-a.dev/medialatch/assets/hero-inline.webp" width="100%" alt="Monolithic 2×2 inline dock, Micro-HUD, Find original lookup, and Activity & Volume chart">
      </a>
      <br>
      <strong>2×2 Inline Dock, Find Original &amp; Stats</strong><br>
      Monolithic dock (<code>MP4 | GIF | ☁</code> + <code>✈</code>) and Micro-HUD with <code>Escape</code> dismissal. <strong>Find original</strong> (local matching + Google Lens, Yandex Images, SauceNAO, IQDB) and persistent <code>Activity &amp; Volume</code> stats in IndexedDB.
    </td>
    <td width="50%" valign="top">
      <a href="https://noizworks.is-a.dev/medialatch/assets/hero-themes.webp">
        <img src="https://noizworks.is-a.dev/medialatch/assets/hero-themes.webp" width="100%" alt="Four MediaLatch themes: Obsidian, Sakura, Dark, and Light">
      </a>
      <br>
      <strong>4 Themes &amp; 7 Languages</strong><br>
      <code>Obsidian</code>, <code>Sakura</code>, <code>Dark</code>, and <code>Light</code> with full keyboard navigation and <code>prefers-reduced-motion</code> support. Localized in <code>EN</code>, <code>RU</code>, <code>ES</code>, <code>JA</code>, <code>KO</code>, <code>PT-BR</code>, and <code>ZH-CN</code>.
    </td>
  </tr>
</table>

---

## Installation & Updates

> [!IMPORTANT]
> Install and update MediaLatch **exclusively through [Chrome Web Store](https://chromewebstore.google.com/detail/medialatch/cimghidldpjhhhngdhigddjfpcofhbmh)**.
> Official extension ID: `cimghidldpjhhhngdhigddjfpcofhbmh` — verify it after installation in `chrome://extensions` with Developer mode enabled.

1. Open the [MediaLatch Chrome Web Store listing](https://chromewebstore.google.com/detail/medialatch/cimghidldpjhhhngdhigddjfpcofhbmh) and click **Add to Chrome** (Chromium 120+).
2. Updates are delivered automatically by the Store; [GitHub Releases](https://github.com/NoizWorks/MediaLatch/releases) publishes release notes only.
3. Reload already-open tabs on supported sites after updating the extension.

---

## Site Coverage & Saving Flow

MediaLatch resolves the selected media's original, verifies its source and bytes, saves it locally or to the chosen cloud destination, and updates the local preview cache. It never substitutes a file from a neighboring post.

| Platform | Images | Video & GIF | Inline `✈` & `Source:` |
| --- | --- | --- | --- |
| **X (Twitter)** | Originals and multi-media posts (up to 20 items) | Native MP4 video, GIFs, MP4 → GIF conversion | Inline `✈` button (drafts, author, post text) |
| **Pixiv** | Original artwork page or verified multi-page list | — | Account folders; link previews |
| **Reddit** | Original images | Native GIFs, progressive MP4, bounded unencrypted H.264/AAC HLS VOD | Link previews and context-menu saving |
| **VK / VK Video** | Photos, carousels, and collages | Supported feed videos, players, and native clips (experimental) | Publishing & scheduling to VK communities |
| **Pinterest** | Selected original images | Supported MP4/HLS video pins, MP4 → GIF conversion | Inline buttons and context menu |
| **Sankaku Complex** (`sankakucomplex.com` / `sankaku.app`) | Originals linked to the selected post | Direct MP4 originals | Post-metadata saving |
| **37 Booru sites** | Originals on supported engines (subject to site access) | Supported post videos/animations | Inline `✈` + auto-parsed `Source:` & author |
| **TikTok / Instagram / RedGIFs** | Selected photos (Instagram, RedGIFs) | Selected videos/Reels, RedGIFs player (including separate-audio recovery) | Inline Copy/Save; 12 platforms in Link Previews |
| **Other HTTP(S) pages** | Image attributes, `srcset`, metadata, and original links | No universal video search | Browser context-menu saving |

<details>
<summary><strong>Folders, filename rules, preview cache &amp; cloud profiles</strong></summary>

```text
Downloads/
└── SavedImages/
    ├── x/posting_account/Image/photo.jpg
    ├── reddit/posting_account/Videos/clip.mp4
    └── danbooru/uploader/Image/artwork.jpg
```

- **Destinations:** `Local-First` (Browser Downloads or a chosen folder), `Google Drive`, `Yandex Disk`, `MEGA`, and `Telegram`. Each destination keeps its own folder and naming profile; Universal setup fills destination profiles while retaining their subfolders and labels. Ordinary inline Download stays local; connecting a cloud reveals adjacent cloud actions. Details: [Cloud setup](docs/CLOUD.md).
- **Levels & templates:** site, account, media type (`{type}` defaults to `Image`, `Videos`, `GIF`, each customizable independently; literal `Images` stays one shared folder), extension, date/year-month/year, or a custom template. Unknown levels are skipped; rule changes apply only to new saves and never rename existing files. Details: [Folder templates](docs/FOLDER_TEMPLATES.md).
- **Filenames & collisions:** original basename or composed fields (site, account, UTC download-start time or verified publication date on X and supported Booru posts). Colliding filenames receive a suffix even after clearing history and statistics — existing files are never overwritten. Long filenames are shortened; excessively long Windows paths may still be rejected by the browser or OS.
- **Folder access & backups:** if the browser re-prompts for folder permission, use **Restore folder access** in settings. The local preview cache stores up to `2,048` thumbnails and `256` originals (`128 MiB`/file, `512 MiB` total, `30 days`). History (up to `50,000` records) and statistics export/restore separately as JSON (up to `32 MiB` UTF-8, excluding media, URLs, and folder grants). Details: [Local data formats](docs/LOCAL_DATA.md).

</details>

<details>
<summary><strong>Technical caveats &amp; compatibility</strong></summary>

- **Link Previews (12 platforms):** X, Instagram, TikTok, YouTube videos/Shorts, Reddit, Pixiv, Bluesky, Threads, Twitch, Tumblr, and Bilibili. Link conversion runs locally. Having a **Copy** control on a site does not imply support for downloading its media.
- **Twitch VODs & mirrors:** Twitch VODs retain their original URL; playback, audio, and galleries depend on the chosen mirror service and messenger.
- **Tab reload after updates:** reload already-open site tabs after updating the extension so content scripts refresh cleanly.
- **Not supported:** DRM, live streams, universal HLS/DASH, arbitrary gallery selection, and YouTube downloads. `HTTP 403`, expired URLs, missing originals, and unsupported streams are reported as failures without falling back to a neighboring post.
- **Codecs & Windows paths:** playback in the built-in viewer depends on browser codecs; Windows path-length limits remain governed by the browser and filesystem.

</details>

---

## Privacy (Local-First)

- **No backend or telemetry:** MediaLatch operates no developer media server, analytics, or advertising. Downloads contact the selected source/CDN directly; cloud uploads go directly to the connected provider.
- **Encrypted credentials & sessions:** `Google Drive`, `Yandex Disk`, `MEGA`, `Telegram`, and `VK` credentials are stored in private extension storage and encrypted at rest (AES-GCM with a non-exportable browser-held key).
- **Private image lookup:** local similar-image matching runs on your device; external lookup via Google Lens, Yandex Images, SauceNAO, or IQDB triggers only on explicit user action and sends only a small `image.jpg` preview without the original file, filename, or source URL.
- **Google Limited Use:** Google API data use (`drive.file`) complies with the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including Limited Use requirements.
- **Data control:** history, optional statistics, local drafts, and sanitized debug logs remain in the browser profile and can be cleared manually. Release checks query GitHub's public releases API without credentials.

Details: [Privacy Policy](docs/PRIVACY.md) · [Website Privacy Policy](https://noizworks.is-a.dev/privacy.html) · [Security Policy](SECURITY.md) · [Project Status](docs/STATUS.md)

---

## Contacts, Support & License

- **Feedback & bug reports:** [GitHub Issues](https://github.com/NoizWorks/MediaLatch/issues) · Telegram [@fs0x1337](https://t.me/fs0x1337) · Email [always1337@vk.com](mailto:always1337@vk.com) *(send vulnerability reports and sensitive details by email only)*
- **Support development:** [Boosty](https://boosty.to/fs0x1337) · [DonationAlerts](https://dalink.to/fs0x1337) · [CloudTips](https://pay.cloudtips.ru/p/da0d3dbe)
- **Docs & changelog:** [CHANGELOG.md](CHANGELOG.md) · [docs/CLOUD.md](docs/CLOUD.md) · [docs/STATUS.md](docs/STATUS.md)
- **License:** starting with `3.0.0`, project-owned code and artwork use the [proprietary license](LICENSE) (earlier GPL recipients retain their existing rights; third-party notices in [THIRD_PARTY_NOTICES.txt](THIRD_PARTY_NOTICES.txt)).
