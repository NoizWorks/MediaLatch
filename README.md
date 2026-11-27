<div align="center">

<a href="https://noizworks.is-a.dev/ru/medialatch/">
  <img src="https://noizworks.is-a.dev/medialatch/assets/hero-banner.webp" width="1280" alt="MediaLatch — сохранение медиа, облачные хранилища и студия Posts & Drafts">
</a>

<br>

[![Chrome Web Store](https://img.shields.io/badge/Chrome_Web_Store-Установить-e11d48?style=flat-square&labelColor=0f1117&logo=googlechrome&logoColor=ffffff)](https://chromewebstore.google.com/detail/medialatch/cimghidldpjhhhngdhigddjfpcofhbmh)
[![v3.2.1](https://img.shields.io/badge/Release-v3.2.1-6366f1?style=flat-square&labelColor=0f1117)](https://github.com/NoizWorks/MediaLatch/releases/tag/v3.2.1)
[![Chromium 120+](https://img.shields.io/badge/Chromium-120%2B-222738?style=flat-square&labelColor=0f1117&logo=googlechrome&logoColor=cbd5e1)](https://github.com/NoizWorks/MediaLatch)
[![Manifest V3](https://img.shields.io/badge/Manifest-V3-222738?style=flat-square&labelColor=0f1117)](docs/PRIVACY.md)
[![Stars](https://img.shields.io/github/stars/NoizWorks/MediaLatch?style=flat-square&label=Stars&labelColor=0f1117&color=222738)](https://github.com/NoizWorks/MediaLatch/stargazers)
[![Boosty](https://img.shields.io/badge/Boosty-Поддержать-6366f1?style=flat-square&labelColor=0f1117&logo=boosty&logoColor=ffffff)](https://boosty.to/fs0x1337)

<p>
  <strong>Русский</strong> ·
  <a href="README.en.md">English</a> ·
  <a href="https://noizworks.is-a.dev/ru/medialatch/">Сайт</a> ·
  <a href="https://github.com/NoizWorks/MediaLatch/releases/tag/v3.2.1">Release Notes v3.2.1</a> ·
  <a href="docs/PRIVACY.md">Privacy Policy</a> ·
  <a href="SECURITY.md">Security</a>
</p>

<p>
  <strong>MediaLatch</strong> — расширение для Chromium, которое сохраняет оригиналы изображений, видео и GIF по вашим правилам папок, захватывает чистые видеокадры в родном разрешении (до 1080p/4K/8K PNG), отправляет файлы локально или в облако и помогает готовить публикации для Telegram и VK. Без собственного сервера, телеметрии и сторонних программ.
</p>

</div>

---

## Интерфейс и возможности v3.2.1

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://noizworks.is-a.dev/medialatch/assets/hero-downloads.webp">
        <img src="https://noizworks.is-a.dev/medialatch/assets/hero-downloads.webp" width="100%" alt="Загрузки, галерея 3×/4×/5×, нативный Popup 424×540 и облачные профили MediaLatch">
      </a>
      <br>
      <strong>Загрузки, галерея и облачные профили</strong><br>
      Группировка по сайтам (<code>3× / 4× / 5×</code>), встроенный просмотрщик и нативный Popup <code>424×540</code> с ускоренным поиском и быстрыми действиями для видеокадра (<code>Save frame</code>, <code>Copy PNG</code>, отправка в <code>Telegram</code> в 1 клик). Отдельные правила папок и имён для <code>Local</code>, <code>Google Drive</code>, <code>Яндекс Диска</code>, <code>MEGA</code> и <code>Telegram</code>.
    </td>
    <td width="50%" valign="top">
      <a href="https://noizworks.is-a.dev/medialatch/assets/hero-posts.webp">
        <img src="https://noizworks.is-a.dev/medialatch/assets/hero-posts.webp" width="100%" alt="3-колоночная студия Posts & Drafts: черновики, редактор и живое превью Telegram и VK">
      </a>
      <br>
      <strong>Студия Posts &amp; Drafts</strong><br>
      Три колонки: <code>Local drafts</code>, редактор с <code>Cred: {author}</code> и дефолтными <code>#hashtags</code>, живое превью для Telegram и VK. Кнопка <code>✈</code> на X и 37 Booru-сайтах с автопарсингом <code>Source:</code>, очередь <code>Queue (+2h)</code> и защита от дублей.
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://noizworks.is-a.dev/medialatch/assets/hero-inline.webp">
        <img src="https://noizworks.is-a.dev/medialatch/assets/hero-inline.webp" width="100%" alt="Монолитный 2×2 inline-док, Micro-HUD, поиск оригинала и статистика Activity & Volume">
      </a>
      <br>
      <strong>Inline-док 2×2, захват кадра и поиск оригинала</strong><br>
      Монолитный док (<code>MP4 | GIF | ☁</code> + <code>✈</code>), Micro-HUD по <code>Escape</code> и захват видеокадра в родном разрешении (до 1080p/4K/8K PNG без интерфейса плеера через <code>OffscreenCanvas</code>, хоткей <code>Alt+Shift+S</code> включая фуллскрин, контекстное меню и inline-кнопка на поддерживаемых сайтах — с <code>0</code> новых разрешений браузера). «Найти оригинал» и график <code>Activity &amp; Volume</code> в IndexedDB.
    </td>
    <td width="50%" valign="top">
      <a href="https://noizworks.is-a.dev/medialatch/assets/hero-themes.webp">
        <img src="https://noizworks.is-a.dev/medialatch/assets/hero-themes.webp" width="100%" alt="Четыре темы оформления MediaLatch: Obsidian, Sakura, Dark и Light">
      </a>
      <br>
      <strong>Welcome / Quick Start, 4 темы и 7 языков</strong><br>
      Обновлённый экран приветствия (Welcome / Quick Start) с живым переключателем тем <code>Obsidian</code>, <code>Sakura</code>, <code>Dark</code> и <code>Light</code> и быстрой настройкой места сохранения. Клавиатурная навигация, <code>prefers-reduced-motion</code> и интерфейс на <code>RU</code>, <code>EN</code>, <code>ES</code>, <code>JA</code>, <code>KO</code>, <code>PT-BR</code> и <code>ZH-CN</code>.
    </td>
  </tr>
</table>

---

## Установка и обновления

> [!IMPORTANT]
> Устанавливайте и обновляйте MediaLatch **только через [Chrome Web Store](https://chromewebstore.google.com/detail/medialatch/cimghidldpjhhhngdhigddjfpcofhbmh)**.
> Официальный ID расширения: `cimghidldpjhhhngdhigddjfpcofhbmh` — проверьте его после установки в `chrome://extensions` при включённом режиме разработчика.

1. Откройте [страницу MediaLatch в Chrome Web Store](https://chromewebstore.google.com/detail/medialatch/cimghidldpjhhhngdhigddjfpcofhbmh) и нажмите **Установить** (Chromium 120+).
2. Обновления доставляются магазином автоматически; в [GitHub Releases](https://github.com/NoizWorks/MediaLatch/releases) публикуются только заметки к релизам.
3. После обновления расширения перезагрузите уже открытые вкладки поддерживаемых сайтов.

---

## Поддержка сайтов и сохранение

MediaLatch находит оригинал выбранного медиа, проверяет источник и байты, затем сохраняет файл локально или в выбранное облако и обновляет локальный кэш превью. Файл из соседнего поста никогда не подменяет выбранный объект.

| Платформа | Изображения | Видео и GIF | Inline `✈` и `Source:` |
| --- | --- | --- | --- |
| **X (Twitter)** | Оригиналы и мультимедиа-посты (до 20 элементов) | Нативное видео MP4, GIF, конвертация MP4 → GIF | Кнопка `✈` (черновики, автор и текст поста) |
| **Pixiv** | Оригинал страницы или проверенный список страниц иллюстрации | — | Папки аккаунтов; превью ссылок |
| **Reddit** | Оригиналы изображений | Обычные GIF, прямые MP4 и ограниченный незашифрованный H.264/AAC HLS VOD | Превью ссылок и контекстное сохранение |
| **VK / VK Video** | Фото, карусели и коллажи | Поддерживаемые видео ленты, плееры и штатные клипы (экспериментально) | Публикация и планирование в сообществах VK |
| **Pinterest** | Выбранные оригиналы изображений | Поддерживаемые MP4/HLS видеопины, конвертация MP4 → GIF | Inline-кнопки и контекстное меню |
| **Sankaku Complex** (`sankakucomplex.com` / `sankaku.app`) | Оригиналы выбранного поста | Прямые MP4-оригиналы | Сохранение по метаданным поста |
| **37 Booru-сайтов** | Оригиналы поддерживаемых движков (с учётом доступа сайта) | Поддерживаемые видео/анимации постов | Кнопка `✈` + автопарсинг `Source:` и автора |
| **TikTok / Instagram / RedGIFs** | Выбранные фото (Instagram, RedGIFs) | Выбранные видео/Reels, плеер RedGIFs (включая отдельную дорожку звука) | Inline Copy/Save; 12 платформ в Link Previews |
| **Другие HTTP(S)-страницы** | Атрибуты, `srcset`, метаданные и ссылки на оригинал | Захват видеокадра в родном разрешении PNG (`Alt+Shift+S`, контекстное меню; универсального поиска потокового видео нет) | Popup, контекстное меню и inline-кнопка на поддерживаемых сайтах |

<details>
<summary><strong>Папки, правила имён, кэш превью и облачные профили</strong></summary>

```text
Downloads/
└── SavedImages/
    ├── x/posting_account/Image/photo.jpg
    ├── reddit/posting_account/Videos/clip.mp4
    └── danbooru/uploader/Image/artwork.jpg
```

- **Хранилища:** `Local-First` («Загрузки» или выбранная папка), `Google Drive`, `Яндекс Диск`, `MEGA` и `Telegram`. У каждого назначения собственный профиль папок и имён; «Универсальная настройка» заполняет профили с сохранением их подпапок и меток. Обычная inline-кнопка сохраняет локально, а при подключённом облаке рядом доступны облачные действия. Подробнее: [Настройка облака](docs/CLOUD.ru.md).
- **Уровни и шаблоны:** сайт, аккаунт, тип медиа (`{type}` — по умолчанию `Image`, `Videos`, `GIF` с отдельной настройкой каждого имени; буквальное `Images` остаётся общей папкой), расширение, дата/год-месяц/год и свой шаблон. Неизвестные уровни пропускаются; правила применяются только к новым сохранениям и не переименовывают существующие файлы. Подробнее: [Папки и имена](docs/FOLDER_TEMPLATES.md).
- **Имена и коллизии:** исходное имя или составное имя по полям (сайт, аккаунт, дата начала скачивания или подтверждённая дата публикации в UTC для X и поддерживаемых Booru). При совпадении имён добавляется суффикс даже после очистки истории и статистики — существующие файлы не перезаписываются. Слишком длинные имена сокращаются; чрезмерно длинный путь Windows браузер или ОС могут отклонить.
- **Доступ к папке и резервные копии:** при повторном запросе прав используйте «Восстановить доступ к папке» в настройках. Локальный кэш хранит до `2 048` миниатюр и `256` оригиналов для превью (`128 МиБ`/файл, `512 МиБ` всего, `30 дней`). Историю (до `50 000` записей) и статистику можно экспортировать/восстановить отдельно в JSON (до `32 МиБ` UTF-8, без медиа, URL и прав на папки). Подробнее: [Формат локальных данных](docs/LOCAL_DATA.md).

</details>

<details>
<summary><strong>Технические ограничения и совместимость</strong></summary>

- **Link Previews (12 платформ):** X, Instagram, TikTok, видео/Shorts YouTube, Reddit, Pixiv, Bluesky, Threads, Twitch, Tumblr и Bilibili. Преобразование ссылки выполняется локально. Наличие кнопки **Copy** на площадке не означает поддержку скачивания её медиа.
- **VOD Twitch и внешние зеркала:** VOD Twitch сохраняют исходный адрес; воспроизведение, звук и галереи зависят от выбранного зеркала и мессенджера.
- **Обновление вкладок:** после обновления расширения перезагрузите уже открытые вкладки сайтов, чтобы обновились content scripts.
- **Не поддерживается:** DRM, прямые эфиры, универсальная загрузка HLS/DASH, произвольное выделение галереи и скачивание видео с YouTube. Ошибки `HTTP 403`, истёкшие ссылки, отсутствующий оригинал и неподдерживаемый поток отображаются как сбой без подмены файлом из соседнего поста.
- **Кодеки и пути Windows:** воспроизведение во встроенном просмотрщике зависит от кодеков браузера; лимит длины пути Windows остаётся на стороне браузера и файловой системы.

</details>

---

## Приватность (Local-First)

- **Без сервера и телеметрии:** у MediaLatch нет своего бэкенда, аналитики и рекламы. Загрузки идут напрямую к источнику/CDN, облачные отправки — напрямую выбранному провайдеру.
- **Шифрование токенов и сессий:** учётные данные `Google Drive`, `Яндекс Диска`, `MEGA`, `Telegram` и `VK` хранятся в приватном хранилище расширения и шифруются локально (AES-GCM с неэкспортируемым ключом браузера).
- **Приватный поиск оригиналов:** поиск похожих сохранений выполняется на устройстве; отправка в Google Lens, Яндекс Картинки, SauceNAO или IQDB происходит только по вашему действию и передаёт лишь уменьшенное превью `image.jpg` без оригинала, имени файла и исходного URL.
- **Google Limited Use:** использование данных Google API (`drive.file`) соответствует [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), включая требования Limited Use.
- **Контроль данных:** история, опциональная статистика, черновики и отладочный журнал остаются в профиле браузера и очищаются вручную. Проверка релизов обращается к публичному API GitHub без учётных данных.

Подробнее: [Privacy Policy](docs/PRIVACY.md) · [Политика на сайте](https://noizworks.is-a.dev/ru/privacy.html) · [Security Policy](SECURITY.md) · [Состояние проекта](docs/STATUS.md)

---

## Контакты, поддержка и лицензия

- **Обратная связь и баги:** [GitHub Issues](https://github.com/NoizWorks/MediaLatch/issues) · Telegram [@fs0x1337](https://t.me/fs0x1337) · Email [always1337@vk.com](mailto:always1337@vk.com) *(уязвимости и чувствительные данные отправляйте только на почту)*
- **Поддержать разработку:** [Boosty](https://boosty.to/fs0x1337) · [DonationAlerts](https://dalink.to/fs0x1337) · [CloudTips](https://pay.cloudtips.ru/p/da0d3dbe)
- **Документация и изменения:** [CHANGELOG.md](CHANGELOG.md) · [docs/CLOUD.ru.md](docs/CLOUD.ru.md) · [docs/STATUS.md](docs/STATUS.md)
- **Лицензия:** с версии `3.0.0` собственный код и графика распространяются по [закрытой лицензии](LICENSE) (ранее полученные GPL-версии сохраняют прежние права; сторонние компоненты — см. [THIRD_PARTY_NOTICES.txt](THIRD_PARTY_NOTICES.txt)).
