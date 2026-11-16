# Awesome-Full-Test-Session-Video-Recording

## Top Full Test Session Video Recording Ecosystem

**Curated List of SaaS Platforms & Open-Source GitHub Projects**  
*Focused on Async Video Messaging, Screen Capture & Self-Hosted Recording Infrastructure*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Full Test Session Video Recording**. These tools help QA teams, developers, and support engineers capture screen recordings with audio and annotations—covering everything from polished async video messaging platforms with free tiers to open-source recorders you can self-host for complete data sovereignty.

**Examples** include Loom, Screenity, OpenScreen, Cap, OBS Studio, and ShareX (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted screen recording, open-source video capture, and community-driven async communication—ideal for teams seeking data sovereignty and avoiding per-creator or per-video SaaS pricing. The open-source landscape is genuinely functional: **Cap** is an open-source Loom alternative with a self-hostable web app , **Screenity** offers a free Chrome extension with no account required , and **OBS Studio** remains the professional standard for high-performance recording .

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global dedicated screen recording and async video capture market is estimated at **$2.5B to $2.95B** in 2025–2026 (expanding beyond $12B when bundled into broader enterprise video collaboration suites). The sector is **moderately fragmented**: while entry-level utility creation is highly fragmented with numerous niche browser extensions and lightweight recorders, enterprise market share and revenue are increasingly concentrated among major platforms (e.g., Loom/Atlassian) and bundled unified communications giants (Zoom Clips, Slack, Microsoft Teams).

## SaaS/Hosted Platforms

| Product | Company Size (Valuation / Revenue) | Starting Paid Pricing | Free Tier / Trial Limits | Description |
|---------|-----------------------------------|-----------------------|--------------------------|-------------|
| **[Loom](https://www.loom.com/)** | **$975M valuation** (acquired by Atlassian; ~$50M ARR at exit) | **$12.50/user/month** (annual) or **$15/user/month** (monthly) | **Free Forever**: 25 videos/creator storage limit, up to 5 minutes per recording, screen + camera bubble recording | **The async video messaging standard.** Record screen and camera, get instant shareable links, and let viewers comment on the timeline. Business plan unlocks unlimited videos, no duration limits, and 4K recording. |
| **[Camtasia](https://www.techsmith.com/)** | **~$65M ARR** (TechSmith parent company; estimated ~$260M–$500M valuation) | **$179.88/year** (~$14.99/month, Essentials plan) or **$39.00/year** (Starter plan) | **Indefinite Free Trial** (no expiration date, but all exported videos include a watermark; companion Snagit has a 15-day trial, Audiate has a 7-day trial) | **Professional screen recorder and video editor.** Industry standard for high-polish training, tutorial, and documentation workflows with multitrack editing, cursor effects, and audio tools. |
| **[Vidyard](https://www.vidyard.com/)** | **~$35M–$45M ARR** (~$91M venture/debt funding raised) | **$59/user/month** (billed annually) or **$89/user/month** (monthly, Starter plan) | **Free Forever**: 5 videos per month, up to 30 minutes per recording, basic analytics | **Video messaging and hosting platform.** Tailored for sales outreach, marketing video distribution, and customer success teams with CRM integrations and viewer tracking. |
| **[Zight (CloudApp)](https://zight.com/)** | **~$5M–$8M ARR** (~$21M venture funding raised) | **$9.95/user/month** (billed annually, Create plan) | **Free Forever**: 50 captures maximum workspace retention, up to 5 minutes per video recording, 15-second max GIF creation, 25 MB upload cap | **Visual communication and capture suite.** Fast screen recording, screenshot capture, and GIF creation designed for support, QA bug reports, and quick async team updates. |
| **[Screencastify](https://www.screencastify.com/)** | **~$3M–$5M ARR** (Seed/Series A venture-backed) | **$7/user/month** (billed annually, Starter plan) | **Free Forever**: 10 videos maximum storage in library, up to 30 minutes per recording, 1080p export, up to 5 collaborator seats | **Lightweight Chrome-based screen recorder.** Seamless Google Drive integration, popular in education, training, and fast browser-based bug filing with drawing tools and trims. |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Cap](https://github.com/CapSoftware/Cap)** | [![Stars](https://img.shields.io/github/stars/CapSoftware/Cap?style=social&color=white)](https://github.com/CapSoftware/Cap/stargazers) | **The most complete open-source Loom alternative with self-hosting support.** **Cross-platform desktop app** (macOS, Windows) built with **Rust, React, Tauri, and MySQL**. **Record screen and camera, edit, and share videos in seconds** . **Self-host the web app** via Docker or Railway—the full stack includes the web application, an ffmpeg media server for transcoding, MySQL for accounts/workspaces/recordings, and S3-compatible object storage for video files . **License**: Cap Camera crates are MIT; all other code is **AGPLv3** . **Best for teams wanting a Loom-style async video workflow** on their own infrastructure. |
| **[Screenity](https://github.com/alyssaxuu/screenity)** | [![Stars](https://img.shields.io/github/stars/alyssaxuu/screenity?style=social&color=white)](https://github.com/alyssaxuu/screenity/stargazers) | **The most popular free and open-source Chrome screen recorder.** **GPLv3 licensed**, **18.2k+ GitHub stars**, used by **280,000+ people** . **Records without an account**—install the extension and hit record. **No time limits, no watermarks, no data collection** . **Annotations while recording**: pen, arrows, shapes, text, **live blur** for private information, camera bubble, and cursor spotlight with click ripple . **Records any tab, window, or full screen** at up to **4K/60fps** (device-dependent) . **Trade-off**: recordings save locally—the **cloud editor with share links requires a paid subscription** . **Best for quick bug reports, tutorials, and demos** where local recording is sufficient. |
| **[OpenScreen](https://github.com/getopenscreen/openscreen)** | [![Stars](https://img.shields.io/github/stars/getopenscreen/openscreen?style=social&color=white)](https://github.com/getopenscreen/openscreen/stargazers) | **The most actively maintained cross-platform open-source screen recorder.** **Free, GPU-accelerated, no watermarks, no subscriptions** . **Windows, macOS, and Linux** with native capture pipelines (ScreenCaptureKit on macOS, Windows Graphics Capture, PipeWire on Linux) . **Full editor**: zooms, backgrounds, motion blur, crop/trim/speed, blur regions, annotations, **auto-captions, and AI editing** . **Best for teams wanting a modern, actively developed recorder** without a SaaS dependency—no cloud features, pure local recording and editing. |
| **[OBS Studio](https://github.com/obsproject/obs-studio)** | [![Stars](https://img.shields.io/github/stars/obsproject/obs-studio?style=social&color=white)](https://github.com/obsproject/obs-studio/stargazers) | **The professional standard for high-performance video recording and live streaming.** **Free and open-source** (GPL-2.0), **Windows, Mac, and Linux** . **Real-time video/audio capturing and mixing** with unlimited scenes, window captures, images, text, browser windows, webcams, and capture cards . **Intuitive audio mixer** with per-source filters (noise gate, noise suppression, gain, VST plugins) . **Studio Mode** for previewing scenes before going live; **Multiview** for monitoring 8 scenes simultaneously . **Powerful API** for plugins and scripts (Lua/Python) . **Trade-off**: more complex than dedicated async video tools—designed for production-grade recording and streaming rather than quick bug-report captures . **Best for QA teams needing high-fidelity, multi-source recordings** (e.g., console + screen + camera simultaneously). |
| **[ShareX](https://github.com/ShareX/ShareX)** | [![Stars](https://img.shields.io/github/stars/ShareX/ShareX?style=social&color=white)](https://github.com/ShareX/ShareX/stargazers) | **The most feature-complete free screen capture tool for Windows.** **Free, open-source, no account required** . **Over 18 years of active development** . **Screen recording** (video and GIF), scrolling capture, region capture, and full-screen capture . **Built-in image editor** with annotation, redaction, crop, and callouts . **Automated after-capture tasks** (upload, copy link, OCR, QR code scan) . **Best for Windows-based QA engineers** wanting a Swiss-army-knife capture tool—not a dedicated async video platform, but excellent for quick evidence capture and sharing. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Isocast](https://github.com/r44vc0rp/isocast)** | [![Stars](https://img.shields.io/github/stars/r44vc0rp/isocast?style=social&color=white)](https://github.com/r44vc0rp/isocast/stargazers) | **Modern macOS/Linux recorder with OBS scene import and multi-canvas support.** **Records every source to its own file plus an ISO file per source**—nothing re-encoded or copied . **Studio Mode, Multiview, masks, vertical canvas for 9:16**, and streaming to multiple destinations simultaneously . **Imports OBS scene collections** on first launch . **Trade-off**: macOS (Apple silicon) and Linux only—no Windows yet . **Best for Mac-based teams** wanting OBS-like power with a cleaner async workflow. |

**Frameworks for building custom systems**: Choose **Cap** for a self-hosted Loom-style async video platform with share links and comments , **Screenity** for zero-friction Chrome-based recording without an account , or **OBS Studio** for high-fidelity multi-source recordings where evidence quality matters most —all without per-creator or per-video SaaS fees.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Screen recording tools capture potentially sensitive screens and audio; enforce recording consent, blur/redaction for PII, and secure storage of test session evidence.
- **Free tiers and recording limits vary significantly.** **Loom's free Starter plan caps at 25 videos and 5-minute recordings**—limits that appear as failed recordings mid-sentence rather than on the pricing page . **Screenity's extension is genuinely free with no limits and no account**, but the **cloud editor with share links requires a paid subscription** . **Cap's self-hosted version has no per-video limits**—the trade-off is operating MySQL, an ffmpeg media server, and S3 storage . **OpenScreen and OBS Studio are fully free with no cloud dependency**—recordings stay local. **Validate whether you need async sharing (Loom, Cap), quick local capture (Screenity, ShareX), or production-grade recording (OBS)** before committing.

---

**Made for QA engineers, developers, and teams building async video communication infrastructure.**  
Let's make full test session video recording more open, private, and cost-predictable.
