# Yuzu

Windows desktop tooling — C++/Win32/COM plugin work and Python helpers, mostly around the
**AIMP** audio player, which is closed source and extensible only through its COM plugin SDK.

## What I maintain

**[AIMP-NCM](https://github.com/cirtuslab/AIMP-NCM)** · `C++`
NetEase Cloud Music inside AIMP: cookie login with DPAPI-sealed credentials, eight quality tiers,
one-click playlist sync, and a loopback proxy that resolves the real CDN URL at playback time and
injects ID3v2 tags into the stream, so the player shows real titles, artists and cover art.

**[AIMPLyricsSaver](https://github.com/cirtuslab/AIMPLyricsSaver)** · `C++`
Fetches lyrics from four providers while you play, merges bilingual and word-timed lines, and
writes a `.lrc` next to the audio file — no overwriting what is already there.

**[aimp_desktop_lyrics](https://github.com/cirtuslab/aimp_desktop_lyrics)** · `C++`
Desktop lyric overlay for AIMP 5+, with per-monitor placement and click-through behaviour.

**[aimp-obs-now-playing](https://github.com/cirtuslab/aimp-obs-now-playing)** · `Python`
Now-playing bridge for OBS and phones: browser source with eight themes, a floating desktop window,
and a LAN page that requires per-device approval before it can read or control playback.

**[SongMetaFixer](https://github.com/cirtuslab/SongMetaFixer)** · `Python`
Repairs audio metadata by looking the track up on NetEase / iTunes / MusicBrainz and writing the
result back to the file.

## Toolchain

`C++17` · `Win32 / COM` · `MSVC + CMake` · `Python 3.10+` · `GitHub Actions (Windows, x64 + x86)`

## Notes

Everything I publish is MIT licensed. The C++ plugins build for both x64 and x86 on hosted Windows
runners on every push and pull request; the parts that need a real player are tested by hand.

All plugin work lives in [@cirtuslab](https://github.com/cirtuslab).
