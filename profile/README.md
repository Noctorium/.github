<div align="center">

<img src="noctorium.png" width="112" alt="Noctorium">

# Noctorium

**All your music. One player.**

YouTube Music, SoundCloud, Bandcamp, Spotify and VK Music in one library: on Windows, macOS, Linux and Android, in a terminal, and in any browser.

[Website](https://noctorium.vercel.app) · [Play in the browser](https://noctorium-music.vercel.app) · [Download](https://github.com/Noctorium/Noctorium-Installer/releases/latest) · [What's new](https://noctorium.vercel.app/#whats-new) · [Release notes](https://github.com/Noctorium/Noctorium-Installer/tree/main/notes)

[![Latest release](https://img.shields.io/github/v/release/Noctorium/Noctorium-Installer?label=release&color=b47cff)](https://github.com/Noctorium/Noctorium-Installer/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/Noctorium/Noctorium-Installer/total?color=b47cff)](https://github.com/Noctorium/Noctorium-Installer/releases)
[![Licence](https://img.shields.io/badge/licence-GPL--3.0-b47cff)](https://github.com/Noctorium/Noctorium-Base/blob/main/LICENSE)

</div>

Noctorium is a music player with one home, one search, one library, one queue and one player for all of
them. It uses your own accounts. When you like a song or edit a playlist in Noctorium, the change is made on
the service itself, not kept in a copy here. Open that service tomorrow on any other device and it is there.

## What it does

- **Every service side by side.** One search shows results from all of them, or from the one you pick.
  Playlists and liked songs from each sit in the same library, and a queue can mix songs from any of them.
- **Your real accounts.** Likes, and playlists you can create, rename, make private or delete, all live on
  the service. On YouTube Music you can also reorder your playlists and follow artists, and your plays go
  into your history there, so its own recommendations learn from what you play here. A heart saves to
  Liked Songs on Spotify, and to My music on VK.
- **Signing in on their page.** Your password goes to the service's own page — Google's, SoundCloud's,
  Spotify's or VK's — and never to a form of ours. Only the session is kept, and it stays on your device.
  The desktop can also be signed in by scanning a QR code with the phone.
- **Spotify, two ways.** With any account: your playlists and Liked Songs in the library, Spotify in search
  with its albums and artists, your top songs and what you played lately on Home. Spotify serves no audio
  to other players, so each song is matched to the same recording on YouTube Music when it plays. With
  Premium, Spotify songs play on Spotify itself instead, in your own Spotify app — on the computer, the
  phone or a speaker — while Noctorium tells it what to play and follows along. Noctorium never decodes
  Spotify's audio.
- **Bandcamp, with nothing to sign in to.** Search it, open its albums and artists, and get its
  best-sellers and new releases on Home, in the genres you pick. Give your Bandcamp name and your
  collection and wishlist are in the library. Bandcamp songs are bought there, not downloaded.
- **VK Music.** Sign in on VK's own page: My music and your VK playlists in the library, VK in search, and
  its suggestions on Home. VK offers its music to no other app, so Noctorium uses your session the way VK's
  web player does. VK's terms do not allow that, and VK may freeze an account it takes for automated; many
  songs do not play outside Russia, and VK songs cannot be downloaded.
- **Up next, from the same service.** When the queue is about to run out, what comes after it is lined up
  underneath, from the service of the song that ends it: YouTube Music's radio, SoundCloud's related
  tracks, more from a Bandcamp artist, VK's suggestions, Spotify's own autoplay. Play one, keep one or drop
  it, or switch autoplay on and off right there in the queue. Close Noctorium and the queue is there next time, with the song you were in
  picked up where you left it.
- **In a terminal, and in a browser.** `noctorium` is the whole player in a terminal — covers drawn in it,
  synced lyrics, every theme, by keyboard or mouse, and it keeps itself up to date. In a browser, [noctorium-music.vercel.app](https://noctorium-music.vercel.app)
  plays YouTube Music and SoundCloud with nothing to install and no account, your likes and playlists kept
  in the browser.
  With your own accounts, `noctorium web` serves the same player from your computer to every browser on
  your network: open the link, or scan its code with a phone, and the music plays out of that device, while
  your sessions never leave the computer.
- **Noctorium Connect.** Take the music off one device and carry on from the same second on another,
  phone to desktop or back again, over your own network.
- **Lyrics**, synced where a synced version exists, from LRCLIB, Musixmatch, Genius and others. Switch
  source right on the lyrics, and Noctorium remembers your pick.
- **Scrobbling** to Last.fm and ListenBrainz, and what you are playing shown on Discord.
- **Downloads.** Save songs for offline listening. On the desktop they are saved as MP3s with their covers.
  Bandcamp and VK songs stay on their service.
- **Out of the way when you want it.** On the desktop, keep the music playing in the tray when you close
  the window (the menu bar on a Mac), and start Noctorium with the computer, in its window or straight into the tray. On the phone, it
  keeps playing with the screen locked, even on phones that like to close apps, and a song that will not
  start after the phone has slept starts itself again where it was. The queue is a button away on Now
  playing.
- **Make it yours.** Nineteen themes, among them Catppuccin, Nord, Dracula, Gruvbox, Rosé Pine, Tokyo
  Night and three pure black crimson ones for OLED screens. Or make one of your own. Accent colours,
  including one taken from the artwork. Liquid glass, and animations throughout that you can switch off.
  Eleven seek bars, from a hairline to a row of bars like SoundCloud's, a glowing neon line or a ruler.
  Ten player bar layouts on the desktop — a floating dock, an island that opens when you point at it, a
  stereo's display, a taskbar — and nine on the phone. Eleven layouts for the now playing screen on the
  desktop and six on the phone: the cover filling the screen, Cover flow through the queue, the record on a
  turntable with its arm crossing as the song plays, the title set as a poster, lyrics that fill the
  screen. Playback speed from half to double, on a button of its own beside the volume, an equaliser, a
  sleep timer that fades out, and in the terminal, keys of your own.
- **Windows 98 and XP, for real.** Pick 98 and Noctorium becomes that desktop: grey bevelled buttons,
  navy title bars, scroll bars with arrows, Settings as a Control Panel, and Now playing in windows on the
  teal desktop. Pick XP for Luna's blue title bars, Explorer's task pane and the green start button. Both
  have a taskbar whose clock you can put away, on the desktop, the phone, in a terminal and in the browser.

## Get it

In one line, from PowerShell on Windows or a terminal on macOS or Linux. It asks whether you want Noctorium, the
Noctorium CLI or both, and checks what it downloads against the release's checksums:

```powershell
irm https://noctorium.vercel.app/install | iex
```

```bash
curl -fsSL https://noctorium.vercel.app/install | sh
```

<details>
<summary>If the website is ever down: the same, straight from GitHub</summary>

```powershell
irm https://raw.githubusercontent.com/Noctorium/Noctorium-Installer/main/scripts/install.ps1 | iex
```

```bash
curl -fsSL https://raw.githubusercontent.com/Noctorium/Noctorium-Installer/main/scripts/install.sh | sh
```

</details>

Or nothing at all: [play in the browser](https://noctorium-music.vercel.app). Every file is also here:

| Platform | Download |
| --- | --- |
| Windows | [`Noctorium-Installer-windows-x64.exe`](https://github.com/Noctorium/Noctorium-Installer/releases/latest/download/Noctorium-Installer-windows-x64.exe), or the setup `.exe` or `.msi` from the [release](https://github.com/Noctorium/Noctorium-Installer/releases/latest) |
| macOS | The `.dmg` from the [release](https://github.com/Noctorium/Noctorium-Installer/releases/latest): `-macos-arm64` for Apple silicon, `-macos-x64` for Intel. Open it and drag Noctorium into Applications; it is not signed by Apple, so the first time choose Open Anyway in System Settings, Privacy & Security — or use the one line above, which skips that |
| Debian, Ubuntu, Mint | The `.deb` from the [release](https://github.com/Noctorium/Noctorium-Installer/releases/latest), or [`noctorium-installer-linux-x64`](https://github.com/Noctorium/Noctorium-Installer/releases/latest/download/noctorium-installer-linux-x64) |
| Fedora, RHEL, openSUSE | The `.rpm` from the [release](https://github.com/Noctorium/Noctorium-Installer/releases/latest), or the same Linux installer |
| Arch, Manjaro, EndeavourOS | The `.pkg.tar.zst` from the [release](https://github.com/Noctorium/Noctorium-Installer/releases/latest), or the same Linux installer. From a terminal it is `noctorium-desktop`; `noctorium` is the CLI |
| Any Linux | The `.AppImage`, or the `.flatpak` (which carries its own mpv), from the [release](https://github.com/Noctorium/Noctorium-Installer/releases/latest) |
| A terminal, and `noctorium web` | `noctorium-cli-<version>-windows-x64.zip`, `-linux-x64.tar.gz`, `-macos-arm64.tar.gz` or `-macos-x64.tar.gz` from the [release](https://github.com/Noctorium/Noctorium-Installer/releases/latest), or the one line above |
| A browser | Nothing to download: [noctorium-music.vercel.app](https://noctorium-music.vercel.app) |
| Android | The `.apk` from the [release](https://github.com/Noctorium/Noctorium-Installer/releases/latest), or [`Noctorium-Installer-android.apk`](https://github.com/Noctorium/Noctorium-Installer/releases/latest/download/Noctorium-Installer-android.apk) |

The installers — a window, or `noctorium-installer-cli` in a terminal — are small programs that install
Noctorium, the Noctorium CLI or both. They fetch the right files for your machine, four pieces at a time
and both at once, and check them against the published checksums before running anything. The desktop
packages carry everything they need, so nothing has to be installed first. After that, both update
themselves. On Windows, Noctorium asks once for permission, shows a progress bar with nothing to click
through, and opens again when it is done. The CLI checks once a day and takes over the new version after
you quit.

Every release has a `SHA256SUMS.txt` beside its files. The APK is signed with Noctorium's release key, and
its certificate SHA-256 fingerprint is
`46:CF:8B:96:C4:37:49:7A:93:AF:76:2B:91:94:AD:11:09:5D:D6:4A:B6:AB:EA:E9:60:C0:A5:98:C5:63:49:ED`.

## The repositories

| Repository | What it is |
| --- | --- |
| [Noctorium-Base](https://github.com/Noctorium/Noctorium-Base) | The shared Kotlin core: library, queue, providers, playlists, settings, scrobbling, lyrics, Connect. Every Noctorium is built on it, so they behave the same rather than nearly the same. Beside it, `jvm`: yt-dlp, mpv and the rest a computer shares. |
| [Noctorium-Desktop](https://github.com/Noctorium/Noctorium-Desktop) | Windows, macOS and Linux. Compose Desktop, mpv for audio, yt-dlp for the services, an embedded Chromium for sign-in. |
| [Noctorium-cli](https://github.com/Noctorium/Noctorium-cli) | The terminal player, and `noctorium web`, which serves the web player to the browsers in the house. |
| [noctorium-web-player](https://github.com/Noctorium/noctorium-web-player) | The web player: the page `noctorium web` serves, and the hosted player at [noctorium-music.vercel.app](https://noctorium-music.vercel.app), whose music comes straight from the services to the browser. |
| [Noctorium-Mobile](https://github.com/Noctorium/Noctorium-Mobile) | Android. Compose, Media3 for audio, NewPipeExtractor for the services, the system WebView for sign-in. |
| [Noctorium-Installer](https://github.com/Noctorium/Noctorium-Installer) | The release pipeline, the releases themselves, the small installers and the one-line install scripts. This is what the in-app updater watches. |
| [Noctorium-Service](https://github.com/Noctorium/Noctorium-Service) | The optional Noctorium account, which keeps your listening statistics. |
| [Noctorium-Website](https://github.com/Noctorium/Noctorium-Website) | [noctorium.vercel.app](https://noctorium.vercel.app), which always offers the latest release. |

To build the desktop app you need JDK 21:

```bash
git clone --recursive https://github.com/Noctorium/Noctorium-Desktop.git
cd Noctorium-Desktop && ./gradlew run
```

---

<sub>Noctorium was called Spiceity before 0.4. It is an independent third-party client, free software
under the GPL-3.0, and not affiliated with Google, YouTube, SoundCloud, Bandcamp, Spotify, VK, Last.fm,
ListenBrainz or Discord.</sub>
