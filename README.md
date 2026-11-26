# Aktar for Scoop

[![Tests](https://github.com/getaktar/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/getaktar/scoop-bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/getaktar/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/getaktar/scoop-bucket/actions/workflows/excavator.yml)

[Aktar](https://getaktar.com) uploads files, screenshots and the clipboard to your own Amazon S3, Cloudflare R2, Backblaze B2, DigitalOcean Spaces or MinIO bucket and puts the link on your clipboard.

```pwsh
scoop bucket add aktar https://github.com/getaktar/scoop-bucket
scoop install aktar/aktar
```

The manifest runs Aktar's own installer (per user, into `%LOCALAPPDATA%\Aktar`), so it gets its Start menu entry, Explorer menu and self-updates like any other copy. `scoop update aktar` installs the newest version too; the manifest follows each release of [getaktar/desktop](https://github.com/getaktar/desktop) within a few hours.

Aktar is also in the [Microsoft Store](https://apps.microsoft.com/detail/9PHJL211PWM7).
