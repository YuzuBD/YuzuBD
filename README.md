<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="assets/banner-light.svg">
    <img src="assets/banner-light.svg" alt="Yuzu — AIMP 插件开发，C++/Win32/COM 与 Python" width="100%">
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
  写 C++/Win32/COM 插件和 Python 小工具，顺手把常用的桌面软件补齐。
  <br>
  <sub>C++/Win32/COM plugins and Python helpers for the desktop.</sub>
</p>

## 在维护的项目 · What I maintain

**[AIMP-NCM](https://github.com/cirtuslab/AIMP-NCM)** · `C++`
在 AIMP 里直接播放网易云音乐：Cookie 登录（DPAPI 加密存储）、八档音质、歌单一键同步，本地代理在播放时注入 ID3v2 标签，封面标题歌手全都正常显示。
<sub>NetEase Cloud Music inside AIMP — cookie login sealed with DPAPI, eight quality tiers, playlist sync, and a loopback proxy that injects ID3v2 tags into the stream.</sub>

**[AIMPLyricsSaver](https://github.com/cirtuslab/AIMPLyricsSaver)** · `C++`
播放时自动从四个平台抓歌词，合并双语与逐字时间轴，把 `.lrc` 写到音频旁边，已有歌词不会被覆盖。
<sub>Fetches lyrics from four providers on playback, merges bilingual and word-timed lines, writes a <code>.lrc</code> beside the audio.</sub>

**[aimp_desktop_lyrics](https://github.com/cirtuslab/aimp_desktop_lyrics)** · `C++`
AIMP 5+ 的桌面歌词悬浮窗，支持多显示器定位与点击穿透。
<sub>Desktop lyric overlay for AIMP 5+, with per-monitor placement and click-through behaviour.</sub>

**[aimp-obs-now-playing](https://github.com/cirtuslab/aimp-obs-now-playing)** · `Python`
给 OBS 和手机用的正在播放桥接：八套主题的浏览器源、桌面悬浮窗，以及需要逐设备审批才能读取或控制播放的局域网页面。
<sub>Now-playing bridge for OBS and phones — browser source with eight themes, floating window, and a LAN page that requires per-device approval.</sub>

**[SongMetaFixer](https://github.com/cirtuslab/SongMetaFixer)** · `Python`
按歌名歌手去网易云 / iTunes / MusicBrainz 查完整元信息，再写回音频文件。
<sub>Repairs audio metadata by looking the track up on NetEase / iTunes / MusicBrainz and writing the result back.</sub>

## 技术与工具链 · Toolchain

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=cpp,python,windows,cmake,githubactions,git,visualstudio&theme=dark">
    <source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=cpp,python,windows,cmake,githubactions,git,visualstudio&theme=light">
    <img src="https://skillicons.dev/icons?i=cpp,python,windows,cmake,githubactions,git,visualstudio&theme=light" alt="C++, Python, Windows, CMake, GitHub Actions, Git, Visual Studio">
  </picture>
</p>

<p align="center">
  <code>C++17</code> · <code>Win32 / COM</code> · <code>MSVC + CMake</code> · <code>Python 3.10+</code> · <code>GitHub Actions（Windows，x64 + x86）</code>
</p>

## 数据 · By the numbers

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=YuzuBD&show_icons=true&hide_border=true&include_all_commits=true&hide=stars,issues&hide_rank=true&bg_color=00000000&card_width=420&title_color=F97316&icon_color=F97316&text_color=F5F5F4">
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api?username=YuzuBD&show_icons=true&hide_border=true&include_all_commits=true&hide=stars,issues&hide_rank=true&bg_color=00000000&card_width=420&title_color=EA580C&icon_color=EA580C&text_color=1C1917">
    <img src="https://github-readme-stats.vercel.app/api?username=YuzuBD&show_icons=true&hide_border=true&include_all_commits=true&hide=stars,issues&hide_rank=true&bg_color=00000000&card_width=420&title_color=EA580C&icon_color=EA580C&text_color=1C1917" alt="GitHub 统计 / GitHub stats">
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=YuzuBD&hide_border=true&background=00000000&card_width=420&ring=F97316&fire=F97316&currStreakNum=F5F5F4&sideNums=F5F5F4&currStreakLabel=F97316&sideLabels=78716C&dates=78716C">
    <source media="(prefers-color-scheme: light)" srcset="https://streak-stats.demolab.com?user=YuzuBD&hide_border=true&background=00000000&card_width=420&ring=EA580C&fire=EA580C&currStreakNum=1C1917&sideNums=1C1917&currStreakLabel=EA580C&sideLabels=78716C&dates=78716C">
    <img src="https://streak-stats.demolab.com?user=YuzuBD&hide_border=true&background=00000000&card_width=420&ring=EA580C&fire=EA580C&currStreakNum=1C1917&sideNums=1C1917&currStreakLabel=EA580C&sideLabels=78716C&dates=78716C" alt="贡献连续天数 / contribution streak">
  </picture>
</p>

## 说明 · Notes

全部以 MIT 许可发布。C++ 插件在每次 push 和 pull request 时都会在 Windows runner 上构建 x64 与 x86；需要真实播放器才能验证的部分，由我手动测试。
<sub>Everything is MIT licensed. The C++ plugins build for both x64 and x86 on hosted Windows runners; the parts that need a real player are tested by hand.</sub>

插件本体都在 [@cirtuslab](https://github.com/cirtuslab) · All plugin work lives in [@cirtuslab](https://github.com/cirtuslab).
