# Release history

**English** · [Türkçe](CHANGELOG.tr.md)

Newest releases appear first. This is an English summary of the development history; the [Turkish history](CHANGELOG.tr.md) retains the detailed original notes. Entries before 1.0 were reconstructed from development records and available APKs, and are not a complete change log.

## 1.0.14

- Added automatic device-language selection with English as the fallback, plus a manual picker in Settings → Language.
- Added English, Turkish, German, Spanish, Italian, Japanese, Brazilian Portuguese, Russian and Simplified Chinese. Reviewed interface text, remote instructions and terminology for TV use.
- Changing language preserves playlists, accounts, and audio / subtitle preferences. Translations work offline.

## 1.0.13

- Fixed focus jumping from the settings content to the section menu when navigating up or down. Off-screen options scroll into view; press Left to return to sections.
- Enlarged the Hittite artwork in About and removed the repeated logo beneath it.
- Moved the Enterla and MemoriBox QR cards to the bottom under “Our other apps.”

## 1.0.12

- Added a dedicated Updates section with version status, last-check time, release notes and an update action.
- Update prompts show what's new with Update / Later choices while playback continues in the background.
- Deferred updates remain accessible beside the M3U / Xtream preview and in Settings, including after reopening the app. The reminder clears after installation.
- Refreshed About with Hittite artwork, app identity, developer details and compact Enterla / MemoriBox QR links.
- Added remote-selectable license cards for AndroidX Media3, FFmpeg / io.put and AndroidX Core, opening full license texts in separate dialogs.

## 1.0.11

- Added in-app update notifications, download progress and Android's user-approved installation screen.
- Added a manual check and automatic-check toggle in Settings → About. Automatic checks run only while the app is open, once a day after a successful check; network errors do not interrupt playback.
- Updates preserve the standard / startup-helper variant. Downloads are checked for size, SHA-256, package identity, version, variant and signing certificate. Playlists and preferences are kept.
- Added an offline release history from the first prototype onward.
- Moved APK downloads to a separate public distribution repository without publishing the application source.

## 1.0.10

- Preview startup places remote focus on the last channel's row or card instead of Search, including after sleep. Open settings and dialogs are left alone.
- Preserved full-screen / list-only startup and the user's focus after they manually move to Search.

## 1.0.9

- Prepared signed, R8-minified standard and startup-helper APKs for distribution outside app stores, using the same certificate. Build checks cover signatures, debugging flags and 16 KB package alignment.
- Renamed the app to Enterla IPTV while keeping its package identity and local data.
- Added About with Enterla / MemoriBox HTTPS links, offline QR codes and a short free-player description.
- Kept the E icon and added Enterla IPTV branding to the Android TV launcher banner.

## 1.0.8

- Combined playback smoothness and device compatibility under Performance. Working mode and buffering appear first; quality limits, decoder and display timing are in advanced options.
- Fixed clipped or shifted borders on multiline cards and gave cards in a row matching heights.
- Refined borders, corners and spacing while keeping remote focus distinct from the selected setting.
- Let headings, buttons, rows and cards adapt to larger text. The toolbar wraps only when needed; cards without artwork no longer reserve empty poster space.

## 1.0.7

- Added Automatic / Balanced / High quality device modes, with Balanced as the default. Existing text size, layout, theme and startup choices are kept.
- Allow suitable quality, including 4K / 8K, when the decoder and TV support it. Removed the general 1080p / 12 Mb/s cap while retaining protection for the older aquaman Mi Stick. Quality selection does not convert a single-source stream.
- Adapted artwork detail, color depth, cache budgets and transitions to the device and mode. Low-memory protection remains active in every mode.
- Added a one-time device summary that does not take focus, plus visual feedback when changing mode without stopping playback.

## 1.0.6

- Strengthened remote focus across toolbars, settings, channel rows, cards and the full-screen panel.
- Added a two-tone preview border and an OK-to-open hint, hidden during full-screen playback.
- Kept playback, buffering, decoder and startup behavior unchanged; no extra video filter was added.

## 1.0.5

- Added fresh-player channel switching for older aquaman / Amlogic Mi Sticks, avoiding reuse of the previous decoder state in M3U and Xtream. Audio fallback and display matching are preserved.
- Added Automatic / Normal / Fresh start compatibility choices, applied to the next stream without interrupting the current one.
- Enabled asynchronous video queueing on the older Mi Stick when no user choice exists. Existing preferences and other devices' defaults are kept. Reported results included smoother playback, with occasional stutter remaining.
- Added AVC scan-header and long frame-scheduling diagnostics. Tested switching between synthetic progressive and interlaced sources with real audio / video decoding.
- This release did not establish a fix for device reboots or guarantee smooth playback of every interlaced stream.

## 1.0.4

- Updated to Media3 1.11.1 and added FFmpeg audio fallback, including MP2 verification on the physical Mi Stick.
- Shared M3U / Xtream playback configuration and added three memory-bounded buffer profiles with a larger reserve after interruptions.
- Added automatic refresh-rate matching, TV-default and manual options. Verified 50 Hz output with measured 25 fps content on the Mi Stick.
- Added actual decoded video dimensions, reported or estimated frame rate, and buffer / audio / video diagnostics without private URLs or account details.
- Kept channel switching available during unsupported-format errors, fixed queued Xtream input during loading and preserved pause state when resizing movie / series views.
- Added third-party licenses and source / relinking information for the bundled FFmpeg version.

## 1.0.3

- Added the #070F1C navy theme, blue focus / selection states, six preset colors, custom HEX input and automatic text contrast.
- Made enabled and disabled switches visually distinct.
- Made OK pause / resume and Left / Right seek 10 seconds in Xtream movies and episodes, without live-TV controls getting in the way.
- Added multi-digit channel-number input with category-consistent numbering and safe handling of invalid numbers.

## 1.0.2

- Added one persistent settings window with sections on the left, options on the right, in-place switches and clear radio selections.
- Applied audio, subtitle and picture settings without restarting playback. Resizing keeps the current settings window and section.
- Clarified startup layouts and the full-screen channel panel, enlarged full-screen info and extended its display time from four to seven seconds.
- Removed the E TV wordmark from the top bar and enlarged the icon, keeping common controls aligned.

## 1.0.1

- Added a preparation screen so saved playlists are not briefly shown as missing. Loading ends when data is ready, without an artificial delay.
- Removed intermediate screens and slide transitions when switching M3U ↔ Xtream.
- Clarified Xtream Back navigation and aligned the shared toolbar across sources.
- Moved Xtream-specific view, refresh and inner Back controls into the content area.

## 1.0.0

- Direct switching between separate M3U and Xtream areas, with a shared live-channel list and right-side preview.
- Optional two-column artwork cards, independently sized text / lists and a paged full-screen channel panel.
- Full-screen playback info, channel switching during errors, and protection from stale connections or retries.
- Last-channel / category caching, full-screen / preview / list-only startup and wake layouts.
- Android 9 startup support and an optional helper for newer Android TV versions.
- Xtream movie / series categories, artwork, seasons and episodes; audio / subtitle preferences.
- E TV branding, a TV launcher banner and Exit to the system home screen.

## 0.1.11 · Preview

- Shared live-channel list / preview layout, two-column artwork cards and playback info.
- Source selection, last-channel / startup layout and Xtream live cache.

## 0.1.10 · Preview

- Work on Android 15 / 16 TV compatibility and an optional startup helper.
- Larger text and remote-navigation improvements.

## 0.1.9 · Preview

- Separate interface / channel-list sizing, a quick sizing button and more size options.

## 0.1.8 · Preview

- Visible playlist loading / error feedback, improved address handling, Exit and playback preferences.

## 0.1.7 · Preview

- Initial E TV branding with the E / IPTV icon and simpler setup explanations.

## 0.1.6 · Preview

- OK opens a channel panel during playback, with Left / Right paging and optional source-provided logos.

## 0.1.5 · Preview

- Xtream Live TV / Movies / Series areas, provider categories, seasons, episodes and artwork.

## 0.1.4 · Preview

- Xtream sign-in, M3U / Xtream setup choice and adjusted live-TV remote directions.

## 0.1.3 · Preview

- Correct HLS handling for live streams with a `.m3u` extension.

## 0.1.2 · Preview

- Improved automatic startup on the Android 9 Mi Stick.

## 0.1.1 · Preview

- Initial APK installation and Mi Stick compatibility adjustments.

## 0.1.0 · First prototype

- Turkish Android TV player under the original Ev TV name, with M3U file / URL import, channel list, preview and full-screen viewing.
- Initial focus on large text, simple remote navigation and resuming the last channel.
