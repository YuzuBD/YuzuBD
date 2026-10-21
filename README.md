<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="assets/banner-light.svg">
    <img src="assets/banner-light.svg" alt="Yuzu — AIMP plugins, C++/Win32/COM, Python" width="100%">
  </picture>
</p>

<p align="center">
  <a href="https://github.com/cirtuslab/AIMP-NCM"><img alt="C++" src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white"></a>
  <a href="https://github.com/cirtuslab/AIMP-NCM"><img alt="Win32 / COM" src="https://img.shields.io/badge/Win32%20%2F%20COM-0078D6?style=flat-square&logo=windows&logoColor=white"></a>
  <a href="https://github.com/cirtuslab/aimp-obs-now-playing"><img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"></a>
  <img alt="AIMP 5" src="https://img.shields.io/badge/AIMP%205-FF7A00?style=flat-square">
  <img alt="MIT" src="https://img.shields.io/badge/license-MIT-2EA043?style=flat-square">
  <img alt="Windows build" src="https://img.shields.io/github/actions/workflow/status/cirtuslab/AIMP-NCM/windows-build.yml?style=flat-square&label=build">
</p>

<p align="center">
  Windows desktop tooling — C++/Win32/COM plugin work and Python helpers, mostly around the
  <b>AIMP</b> audio player, which is closed source and extensible only through its COM plugin SDK.
</p>

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

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=cpp,python,windows,cmake,githubactions,git,visualstudio&theme=dark">
    <source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=cpp,python,windows,cmake,githubactions,git,visualstudio&theme=light">
    <img src="https://skillicons.dev/icons?i=cpp,python,windows,cmake,githubactions,git,visualstudio&theme=light" alt="C++, Python, Windows, CMake, GitHub Actions, Git, Visual Studio">
  </picture>
</p>

`C++17` · `Win32 / COM` · `MSVC + CMake` · `Python 3.10+` · `GitHub Actions (Windows, x64 + x86)`

## By the numbers

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=YuzuBD&show_icons=true&hide_border=true&include_all_commits=true&hide=stars,issues&hide_rank=true&bg_color=00000000&card_width=420&title_color=F97316&icon_color=F97316&text_color=F5F5F4">
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api?username=YuzuBD&show_icons=true&hide_border=true&include_all_commits=true&hide=stars,issues&hide_rank=true&bg_color=00000000&card_width=420&title_color=EA580C&icon_color=EA580C&text_color=1C1917">
    <img src="https://github-readme-stats.vercel.app/api?username=YuzuBD&show_icons=true&hide_border=true&include_all_commits=true&hide=stars,issues&hide_rank=true&bg_color=00000000&card_width=420&title_color=EA580C&icon_color=EA580C&text_color=1C1917" alt="GitHub stats">
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=YuzuBD&hide_border=true&background=00000000&card_width=420&ring=F97316&fire=F97316&currStreakNum=F5F5F4&sideNums=F5F5F4&currStreakLabel=F97316&sideLabels=78716C&dates=78716C">
    <source media="(prefers-color-scheme: light)" srcset="https://streak-stats.demolab.com?user=YuzuBD&hide_border=true&background=00000000&card_width=420&ring=EA580C&fire=EA580C&currStreakNum=1C1917&sideNums=1C1917&currStreakLabel=EA580C&sideLabels=78716C&dates=78716C">
    <img src="https://streak-stats.demolab.com?user=YuzuBD&hide_border=true&background=00000000&card_width=420&ring=EA580C&fire=EA580C&currStreakNum=1C1917&sideNums=1C1917&currStreakLabel=EA580C&sideLabels=78716C&dates=78716C" alt="Contribution streak">
  </picture>
</p>

## Notes

Everything I publish is MIT licensed. The C++ plugins build for both x64 and x86 on hosted Windows
runners on every push and pull request; the parts that need a real player are tested by hand.

All plugin work lives in [@cirtuslab](https://github.com/cirtuslab).
