# Awesome-Cross-Device-Video-Editing

# Top Cross-Device Video Editing Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Mobile-First Editing, Cloud Project Sync & Self-Hosted Cross-Platform NLEs*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Cross-Device Video Editing**. These tools enable creators to start editing on a phone, continue on a tablet or desktop, and export without losing work—ranging from mobile-first apps with cloud sync to open-source editors that run natively across operating systems.

**Examples** include CapCut, LumaFusion, KineMaster, VN Video Editor, InShot, and the open-source leader Clypra (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, avoiding watermarks and subscriptions, and controlling the editing pipeline. The open-source landscape is thinner than in other categories—cross-device video editing is dominated by commercial mobile apps—but **Clypra** provides a hardware-accelerated editor built on Rust and Tauri that targets desktop and mobile from a single codebase, with **Shotcut** and **Kdenlive** serving desktop cross-platform needs.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing | Free Tier Limit |
| :--- | :--- | :--- | :--- |
| **[CapCut](https://www.capcut.com/)** | Mobile-first editor with AI tools, cloud sync, and desktop/web versions. | **Pro**: **$19.99/month** or **$179.99/year** (web checkout; app-store pricing ~$22/mo due to platform fees). **Standard**: $9.99/month. **Team**: from $24.99/seat/month . | **Free**: Full editor, **1080p export with no watermark on standard edits**, multi-track timeline, transitions, captions. **4K export, full AI toolkit, and commercial license require Pro** . |
| **[LumaFusion](https://apps.apple.com/us/app/lumafusion/id1062022008)** | Professional-grade mobile editor for iOS/iPadOS with multicam, keyframing, and external drive support. | **$29.99** one-time purchase (base app) . Additional in-app purchases for Creator Pass (monthly/yearly), Speed Ramping, Multicam Studio, and FCPXML Export . | **No free tier**. One-time purchase required. In-app add-ons priced separately. |
| **[KineMaster](https://www.kinemaster.com/)** | Android/iOS editor with multi-layer timeline, keyframes, chroma key, and AI tools. | **Premium**: **$7.99/month** or **$51.99/year** (official listing); app-store variations range **$8.49–$59.99** . | **Free**: Access to editing tools **with advertising and KineMaster watermark**. Premium removes both and adds 10GB KineCloud storage . |
| **[VN Video Editor](https://www.vnvideoeditor.com/)** | Mobile editor popular for its clean interface and pro-oriented features. | **VN Pro**: **₹399/month** or **₹1,799/year** (India App Store) . US App Store shows **$5.99/month** or **$36.99/year** . | **Free tier** available with core editing. VN Pro unlocks advanced features and removes limitations. |
| **[InShot](https://inshot.com/)** | Mobile-first editor for vlogs and social media with effects, filters, and audio tools. | **InShot Pro**: **NT$150/month** or **NT$590/year** (Taiwan App Store) . **Lifetime**: NT$1,490. Prices vary by region. | **Free tier** with watermarked exports and ads. Pro removes watermark and unlocks full effects library. |
| **[Adobe Premiere Rush](https://www.adobe.com/products/premiere-rush.html)** | **Discontinued.** Adobe ended Premiere Rush support on **September 30, 2025**, recommending Premiere on iPhone (Android in development) . | **No longer available** for new users. Existing subscribers may retain access temporarily. | N/A (discontinued). |
| **[Splice](https://spliceapp.com/)** | Mobile video editor with music integration, transitions, and social-ready templates. | **Subscription**: **$9.99/week**, **$9.99/month**, or yearly (App Store listing) . | **Free tier** available with core editing. Subscription unlocks premium music, effects, and exports. |
| **[PowerDirector Mobile](https://www.cyberlink.com/)** | Mobile version of CyberLink's editor with AI tools and 4K export. | **Pro+**: ₪19.90/month or ₪115.90/year; **Premium**: ₪23.90/month (Israel App Store pricing; varies by region) . | **Free tier** with watermarked exports. Subscription removes watermark and unlocks AI features. |

## Open-Source GitHub Projects

- **[Clypra](https://github.com/AIEraDev/Clypra)** [![GitHub Stars](https://img.shields.io/github/stars/AIEraDev/Clypra?style=social&color=white)](https://github.com/AIEraDev/Clypra/stargazers)  
  **The hardware-accelerated cross-platform editor.** **MIT licensed**, fully free with **no watermarks, no paywalls, and no subscriptions**. **Built on Rust/Tauri v2 + React 19** with a native FFmpeg decoder pool, GPU decoding (VideoToolbox, D3D11VA, VAAPI), and **sub-10ms frame decoding latency** . **Platforms**: macOS (Apple Silicon & Intel), Windows 10/11, Linux, **plus iOS and Android via Capacitor**—making it the closest open-source match for the cross-device category. **Features**: frame-accurate multi-track timeline, real-time waveform rendering, text/overlay compositing, and ProRes/H.264 export. **Install**: `brew install AIEraDev/tap/clypra` (macOS), or download `.msi`/`.AppImage` for Windows/Linux . Best for developers and creators wanting a genuinely free, cross-platform editor without subscription lock-in.

- **[Shotcut](https://github.com/mltframework/shotcut)** [![GitHub Stars](https://img.shields.io/github/stars/mltframework/shotcut?style=social&color=white)](https://github.com/mltframework/shotcut/stargazers)  
  **The desktop cross-platform workhorse.** GPL-3.0 licensed, ~15,400 stars. Runs on Windows, macOS, and Linux with native FFmpeg format support, 4K editing, and a robust filter set. **Not mobile-native**—Shotcut is a desktop NLE—but it's the most mature open-source editor for users who edit on a computer and want project portability across platforms. Best for desktop-first workflows where mobile editing is not required.

- **[Kdenlive](https://github.com/KDE/kdenlive)** [![GitHub Stars](https://img.shields.io/github/stars/KDE/kdenlive?style=social&color=white)](https://github.com/KDE/kdenlive/stargazers)  
  **The feature-rich multi-track NLE.** GPL-3.0 licensed, ~5,900 stars. Runs on Linux, Windows, macOS, and BSD with unlimited tracks, proxy editing for 4K/HDR, and advanced color grading. Like Shotcut, it's desktop-only—not a mobile app—but serves cross-platform desktop editing needs. Best for users wanting a full NLE experience on any desktop OS.

### Additional Strong Open-Source Options

- **OpenShot** — Beginner-friendly desktop editor with drag-and-drop timeline. Best for simple projects on Linux/Windows/macOS.
- **Blender (Video Sequence Editor)** — Built-in video editor within Blender. Best when 3D/compositing is the primary job and editing is secondary.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- **Adobe Premiere Rush is discontinued**: Adobe ended support on September 30, 2025, and recommends Premiere on iPhone as the replacement (Android in development). Do not select for new projects .
- **Open-source cross-device editing is nascent**: Clypra is the only open-source editor found that explicitly targets both desktop and mobile from one codebase, but it is early-stage. Shotcut and Kdenlive are mature desktop editors without mobile versions .
- **Free tiers vary significantly**: CapCut's free tier is unusually generous (1080p export, no watermark on standard edits) ; KineMaster and InShot add watermarks to free exports ; LumaFusion requires a one-time purchase with no free tier .
- **App-store pricing differs from web pricing**: CapCut Pro is ~$22/month via app stores vs $19.99 on the web due to platform commissions . Subscribe on the web where possible.

---

**Made for mobile creators, social media editors, and anyone who wants to edit video across devices without subscription lock-in.**  
Let's make cross-device video editing more open, watermark-free, and self-hostable.
