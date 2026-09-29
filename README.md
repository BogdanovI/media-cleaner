# Media Cleaner

Find duplicate photos, blurry shots and large files — entirely on your device.
No account, no uploads, works offline.

## Download

| Platform | Get it |
| --- | --- |
| **Android** | [Google Play](https://play.google.com/store/apps/details?id=io.github.bogdanovi.media_cleaner) |
| **Windows 10 / 11** (64-bit) | [Latest release](https://github.com/BogdanovI/media-cleaner/releases/latest) — installer or portable zip |
| **Linux** | Coming soon |
| **macOS** | Coming soon |

<a href="https://play.google.com/store/apps/details?id=io.github.bogdanovi.media_cleaner"><img alt="Get it on Google Play" src="https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png" height="80"></a>

### Windows: which file to pick

Each [release](https://github.com/BogdanovI/media-cleaner/releases/latest) has two files:

- `MediaCleaner-<version>-windows-x64-setup.exe` — installer. Adds a Start menu
  entry and an uninstaller; installs for the current user, no admin rights needed.
- `MediaCleaner-<version>-windows-x64-portable.zip` — no installation. Unzip
  anywhere and run `media_cleaner.exe`.

The app is not code-signed yet, so Windows SmartScreen may show
“Windows protected your PC” on first launch. Click **More info → Run anyway**.

## What it finds

- **Duplicate photos** — compared by how they look, not just by name or size,
  so re-saved and resized copies are caught too. Exact copies of videos and
  other media are found as well.
- **Blurry photos** — measures sharpness and shows the worst first, with an
  adjustable sensitivity.
- **Large files** — the photos and videos taking the most space, with your own
  size threshold.
- **Messenger media** *(Android)* — images and videos saved by WhatsApp,
  Telegram, Viber and similar apps.

Nothing is deleted automatically: every result comes with a preview, folder and
file size, and you choose exactly what goes. Safe Folders keep chosen
directories out of every scan.

## Desktop version

On Windows (and later Linux and macOS) you pick a folder or a whole drive to
scan — handy for camera archives and external disks. The desktop version is
**free, with no ads and no limits**: every setting is unlocked.

Scanning speed depends mostly on the drive: photos have to be read in full to be
compared, so an external disk on a USB 2.0 port is several times slower than
the same disk on USB 3.

## Privacy

The scanning engine is written in C++ and runs locally on all CPU cores. Your
photos and videos are never uploaded, copied or shared, and no account is
needed. See the [privacy policy](https://bogdanovi.github.io/media-cleaner-privacy/).
