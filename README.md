# Enterla IPTV — IPTV Player for Android TV

**English** · [Türkçe](README.tr.md)

A free IPTV player app for **Android TV and Google TV**. Watch your own **M3U playlists** and **Xtream accounts**, with live TV, movies and series in a simple interface built for a TV remote.

**[Download the latest APK](https://github.com/Ninken1997/Enterla-IPTV/releases/latest)** · [Release history](CHANGELOG.md)

Enterla IPTV is a player. **No channels, playlists or subscriptions are included.** Bring your own playlist or provider account.

## What's new in 1.0.16

A sharper vector wordmark, a remote-friendly color palette, clearer Home-button setup and Back-to-exit confirmation. Theme changes preserve playback, and light colors automatically use dark text.

## Designed for everyday TV viewing

- Load an M3U file or playlist URL, or sign in with an Xtream server, username and password.
- Browse live channels beside a video preview. Open a channel panel over full-screen TV and jump through long lists page by page.
- Browse your provider's movie and series categories, artwork, seasons and episodes.
- Adjust text size and channel rows independently. Choose a plain list or two-column channel cards when artwork is available.
- Use clear remote focus, optional channel logos, custom colors, audio and subtitle preferences.
- Resume your last channel in full screen or preview, or open the list without starting playback. Automatic startup is available where the device allows it.
- See actual video resolution and download speed in the playback info panel.

## Install or update

1. Open the [latest release](https://github.com/Ninken1997/Enterla-IPTV/releases/latest) on your Android TV / Google TV device.
2. Download the **standard APK** first. The **startup-helper APK** is an alternative for devices that need the optional automatic-startup helper.
3. Open the APK and allow installation from the app you used to download it, if Android asks.
4. Add your own M3U playlist or Xtream account. You can change these later in **Settings → Accounts and playlists**.

Both APKs are variants of the same application; they cannot be installed side by side. **Update over your existing installation without uninstalling it**, using the same variant. Your playlists and settings are kept.

For in-app updates, open **Settings → Updates → Check again**. Download the update, then confirm **Install** in Android. The first time, Android may ask you to allow Enterla IPTV to install apps. Versions 1.0.10 and earlier need one manual APK update to get in-app updates.

## Languages

English, Turkish, German, Spanish, Italian, Japanese, Brazilian Portuguese, Russian and Simplified Chinese.

The app follows your Android language by default and falls back to English when that language is unsupported. Choose a language in **Settings → Language** to keep your own preference. Provider channel names and categories stay as supplied; audio and subtitle preferences are separate.

## Device compatibility

| Device or operating system | Support |
| --- | --- |
| Android TV / Google TV, Android 8.0 or newer | Target platform. Includes compatible Xiaomi TV Stick / TV Box, NVIDIA Shield and Android TV televisions. |
| Sony, TCL, Philips and other TV brands | Check the operating system: the TV must run Android TV or Google TV. The brand alone does not establish compatibility. |
| Samsung Tizen / LG webOS | This APK does not run directly. Use an external Android TV / Google TV device over HDMI. |
| Apple TV (tvOS) / Roku | This Android APK does not run directly. |
| Android 7.1 or older | Not supported. Android 8.0 is the minimum. |
| Android phones / tablets | Designed for TVs and remotes; a mobile interface is not supported. |
| Windows / macOS / iPhone / iPad | Not a native app for these platforms. |

**Tested environments:** an Android 9 Xiaomi Mi TV Stick, plus targeted tests on Android 9 and Android 16 TV emulators. Not every device or model has been tested.

**Video and audio:** 4K / 8K, HDR, codecs, audio output and DRM support depend on the source, device and TV. The player does not turn a lower-resolution stream into native 4K or guarantee playback of every format.

**Automatic startup:** verified with the standard variant on the Android 9 Mi Stick. Newer Android TV devices may need the startup-helper variant and an Android accessibility permission. Power and HDMI-CEC behavior must be checked on the actual device.

## About this download repository

This is the official **APK distribution and release-notes repository**. The application source code is maintained separately and is not published here.

The player uses AndroidX Media3 (Apache 2.0), io.put / FFmpeg audio support (Apache 2.0 / LGPL 2.1+) and AndroidX components. Notices and license texts are available in **Settings → About** and in the distribution ZIP. The matching [FFmpeg audio component source / rebuild package](https://github.com/Ninken1997/Enterla-IPTV/releases/download/v1.0.14/FFmpeg-audio-1.11.1-1-source.tar.xz) is provided separately; it is not Enterla IPTV's application source code.

[Enterla](https://www.enterla.net/) · [MemoriBox](https://www.memoribox.net/)
