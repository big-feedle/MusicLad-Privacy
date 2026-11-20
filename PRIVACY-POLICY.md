# MusicLad for Android — Privacy Policy

Last updated: 19 November 2026

MusicLad is a music player for files already stored on your device. It has no
account, no sign-in, and no analytics. This policy covers the Android apps
**MusicLad** (`com.musiclad.android`) and **MusicLad Free**
(`com.musiclad.android.free`).

## Data we collect

None. We operate no servers and receive no information about you or your use of
the app. Nothing you do in MusicLad is reported to us.

## Data stored on your device

MusicLad keeps the following in its own private storage on your phone, where
only MusicLad can read it. It is deleted when you uninstall the app.

- Your music library index: file paths, titles, artists, albums, track lengths
  and other tag data read from your own audio files.
- Your settings, playlists, favourites, queue and resume position.
- Your listening history — what you played and when — used for the Statistics
  screen in the full version.
- A crash report file, written to the app's Documents folder if the app stops
  unexpectedly, so you can read it or send it to us yourself if you choose.

None of this is transmitted anywhere.

## Permissions and why they are needed

- **Music and audio files** (`READ_MEDIA_AUDIO`, and `READ_EXTERNAL_STORAGE` on
  Android 12L and older): to find and play your audio files. Only audio files
  are read.
- **Notifications** (`POST_NOTIFICATIONS`): to show the playback notification
  with the track and its controls.
- **Foreground service** (`FOREGROUND_SERVICE`,
  `FOREGROUND_SERVICE_MEDIA_PLAYBACK`): to keep playing while the app is in the
  background or the screen is off.
- **Internet** and **network state** (`INTERNET`, `ACCESS_NETWORK_STATE`): used
  only for the optional lookups below, and for the desktop remote.

## When MusicLad uses the network

MusicLad makes no network request until you ask for one. When you do, the
request goes directly from your device to the service named, and the only
information sent is the search terms needed for that lookup — typically a track
title, artist or album from your own files. Your identity is not sent, because
the app has none to send.

| What you ask for | Where the request goes |
| --- | --- |
| Lyrics lookup, synced lyrics finder (full version) | `lrclib.net` |
| Album and track tag lookup, artwork | `musicbrainz.org`, `coverartarchive.org`, `itunes.apple.com` |
| Artist biographies | `en.wikipedia.org` |
| Headphone EQ profiles | `raw.githubusercontent.com` (the AutoEq project) |
| Desktop remote (full version) | The MusicLad desktop app on your own local network, by the address you enter |

Those services are operated by third parties and have their own privacy
policies. Each request is also visible to your network operator, as any web
request is. If you never use these features, MusicLad makes no network
requests at all.

The desktop remote talks to your own computer over your own network in plain
HTTP, because the desktop app has no certificate. That traffic never leaves
your network.

## Children

MusicLad is not directed at children and collects no data from anyone.

## Changes

If this policy changes, the updated version is posted at this address with a new
date at the top.

## Contact

Questions about this policy: 0jamesondrako@gmail.com
