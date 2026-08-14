# JINKUSU CAM

**Version 8.0.1** · Windows desktop · Real-time computer-vision pipeline

JINKUSU CAM is a licensed Windows application for **educational and research use** — exploring face detection, identity-preserving video pipelines, virtual camera routing, and on-device ML inference.

> **Educational purpose only**  
> This software is intended for learning, lab work, and authorized testing environments (computer vision, media pipelines, privacy research). **You are solely responsible** for how you deploy it and for complying with applicable laws and platform terms where you operate. JINKUSU.DEV does not encourage or endorse unlawful use.

---

## What it does

- **Face pipeline** — Load reference images, run real-time face swap on webcam or file sources (InsightFace, quality presets from Fast to Ultra)
- **Virtual camera output** — Route processed video through **OBS Virtual Camera** into any app that accepts a standard camera device
- **Voice chain** — On-device pitch morph and preset effects (use headphones to avoid feedback)
- **Scene tools** — Background blur/replace, optional enhancement, expression-related processing
- **Photo AI** — Animate still images using landmark-driven motion
- **Mobile relay** — Android companion path (`com.jinkusu.cam.app`) and emulator integration (BlueStacks / LDPlayer via OBS VCam)
- **Licensed access** — Application requires a valid license key and authenticator (TOTP) code to run

Processing runs **on your machine** (or on a rented GPU node — see below). Face/audio data used in the desktop app is not sent to a cloud inference service for the core swap graph.

---

## System requirements

| | Minimum | Recommended |
|---|---------|-------------|
| **OS** | Windows 10/11 x64 | Windows 11 x64 |
| **CPU** | 4 cores, AVX2 | 8+ cores |
| **RAM** | 16 GB | 32 GB |
| **GPU** | DirectML (AMD / Intel) | NVIDIA RTX with CUDA |
| **Other** | OBS Studio (Virtual Camera enabled) | SSD, current GPU drivers |

**No discrete GPU?** A **Virtual GPU** option (NVIDIA RTX 4090 · 32 GB, remote Windows session) is available as a monthly add-on through official support — software license sold separately.

---

## Getting the software

JINKUSU CAM is **not open-source freeware**. Builds are distributed through the official channel:

| Resource | Link |
|----------|------|
| **Website & plans** | [jinkusucam.tokyo](https://jinkusucam.tokyo/) |
| **Licensed download** | Access gate on the website (license key + TOTP after purchase) |
| **Dev hub** | [jinkusu.dev](https://jinkusu.dev) |
| **Support & orders** | [@jinkususupport](https://t.me/jinkususupport) on Telegram |
| **News channel** | [@JINKUSUDEVELOP](https://t.me/JINKUSUDEVELOP) |

Third-party dependencies (OBS, VC++ Redistributable, GPU drivers, FFmpeg for file sources) are listed on the site under **Files**.

---

## Quick start (licensed users)

1. Install **OBS Studio** and enable **Virtual Camera**
2. Install **JINKUSU CAM** from the official access gate
3. Sign in with your **license key** and **authenticator code**
4. Open the **FACE** tab → add a reference photo
5. Select webcam or file input → press **START**
6. In your target app, choose **OBS Virtual Camera** as the camera source

For a full walkthrough, use the in-app **Tutorial** button or the guides linked from the website.

---

## Plans (overview)

Pricing is in **USD** on the website. Typical options:

- **Professional** — monthly single-seat license  
- **3-month bundle** — discounted campaign tier  
- **Source code** — partner / private handover (not the public GitHub tree)  
- **Virtual GPU** — $150/month dedicated RTX 4090 node (add-on)

Checkout and payment details are handled via official support channels listed above.

---

## Privacy

The desktop client validates your license against the licensing service. **Video frames and face images you load stay local** unless you explicitly share them. See the website **Privacy Policy** for what the portal and API store.

---

## Disclaimer

JINKUSU CAM is provided **“as is”** for educational and research purposes. The authors and JINKUSU.DEV accept no liability for misuse, third-party platform actions, or damages arising from deployment. By using this software you confirm you understand these limits and will use it lawfully and ethically.

---

## Contact

- **Orders & support:** [@jinkususupport](https://t.me/jinkususupport)  
- **Web:** [jinkusu.dev](https://jinkusu.dev) · [jinkusucam.tokyo](https://jinkusucam.tokyo/)

---

© JINKUSU CAM · JINKUSU.DEV
