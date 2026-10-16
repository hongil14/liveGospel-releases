# LiveGospel releases

Downloads and the update feed for LiveGospel, a live Korean sermon caption and
translation app for Apple Silicon Macs (macOS 15 or later). The source code is
not in this repository.

## Install

1. Download the newest `LiveGospel-<version>.zip` from the
   [updates release](https://github.com/hongil14/liveGospel-releases/releases/tag/updates).
2. Unzip it and move **LiveGospel.app** to **Applications**.
3. Open it. The app is not notarized by Apple, so macOS blocks the first
   launch: open **System Settings → Privacy & Security**, scroll down, and
   click **Open Anyway** next to the LiveGospel message.

After that, LiveGospel updates itself: it checks for a new version every hour
and installs it when you quit the app, never during a session.

`appcast.xml` is the update feed the app reads.
