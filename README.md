# J. Chang

**Software developer · IT consultant · photographer · radio enthusiast**

I build software around radio systems, cloud infrastructure, and digital imaging. A lot of it starts with hardware I use, a workflow that could be better, or a proprietary format that looked interesting enough to reverse engineer.

Professionally, I run a small IT consulting business working with Microsoft 365, Azure, AWS, networking, identity, security, and automation.

## Featured work

### 📻 DVMConsole NEO

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/RdWing/dvmconsole/neo/repo/neo-dark.png">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/RdWing/dvmconsole/neo/repo/neo-light.png">
  <img alt="DVMConsole NEO showing a public demo configuration with independent channel controls and the Activity sidebar" src="https://raw.githubusercontent.com/RdWing/dvmconsole/neo/repo/neo-dark.png" width="100%">
</picture>

A cross-platform operator console for **P25, DMR, and NXDN** radio systems, built with **.NET and Avalonia**. It brings independent channels, talkgroup patching, secure voice, recording, and graphical configuration into one workspace.

NEO is a ground-up rewrite of the original application, now supporting **macOS, Windows, and Linux**, with **iPhone and iPad versions in public beta**.

[**Explore the project →**](https://github.com/RdWing/dvmconsole) · [Downloads](https://github.com/RdWing/dvmconsole/releases) · [iOS/iPadOS beta](https://testflight.apple.com/join/KuYtQqja)

### 📷 NP3 Studio

[![NP3 Studio analyzing the Nlog v8 stills preset, showing tone, color blending, and color grading controls](assets/np3-studio.png?v=2)](https://www.nikonfpc.com/)

A browser-based tool for exploring Nikon's **NP3 Flexible Color Picture Controls**. I reverse-engineered the format and built an analyzer that decodes all 44 parameters, visualizes tone curves and LUTs, and exposes the color-blending and grading data inside each file.

Built with **Rust and WebAssembly**. Files are processed locally in your browser.

[**Try NP3 Studio →**](https://www.nikonfpc.com/)

### 🔬 Nikon firmware research & WonderLantern

I've also been spending quite a bit of time reverse-engineering Nikon Z camera firmware, particularly the EXPEED 7 generation. That work has taken me into embedded systems, firmware architecture, camera processing pipelines, and hardware emulation.

I'm part of the **[WonderLantern](https://github.com/WonderLantern)** team and created **[Z8 QEMU](https://github.com/WonderLantern/z8-qemu)**, a Nikon Z8 firmware emulator built on WonderLantern's earlier Z9 emulation work. It runs the camera's original firmware, including menu navigation, display rendering, simulated controls, and experimental image capture using modeled hardware and synthetic sensor data.

I've also been working on Z6III firmware emulation, EXPEED 7 internals, and tools for understanding and experimenting with Nikon's imaging pipeline.

One related public project is **[LUT to Picture Control](https://rdwing.github.io/nikon-lut-to-np3/)**, an experimental tool that fits Nikon Flexible Color settings to approximate a compatible 3D LUT.

## Beyond those projects

My radio work spans digital voice networks, HF, SDR, audio, and hardware integration. [DVMHost](https://github.com/RdWing/dvmhost) and [FNECore](https://github.com/RdWing/fnecore) are part of the wider ecosystem I work with.

I'm also a photographer, interested in both making photographs and understanding how the camera arrives at the finished image. Increasingly, that curiosity has led me from picture controls and color science all the way down to firmware, processors, and the hardware underneath.

<details>
<summary>More radio projects and forks</summary>

- [KFDtool](https://github.com/RdWing/KFDtool) — P25 keyloading software and hardware tooling
- [NetworkIcom](https://github.com/RdWing/NetworkIcom) — Icom IC-7610 Ethernet control in Swift and SwiftUI
- [P25Clients](https://github.com/RdWing/P25Clients) and [NXDNClients](https://github.com/RdWing/NXDNClients) — gateways and parrots
- [MMDVM_CM](https://github.com/RdWing/MMDVM_CM) — cross-mode conversion tools
- [anytone-flash-tools](https://github.com/RdWing/anytone-flash-tools) — Anytone radio flash tools
- [OpenHPSDR-wdsp](https://github.com/RdWing/OpenHPSDR-wdsp) — SDR and digital signal processing

Some are active work; others are older experiments or forks I used to explore a radio, protocol, or piece of hardware.

</details>

**Tools I work with:** C# · .NET · Avalonia · C/C++ · Rust · WebAssembly · Python · QEMU · Swift · JavaScript

---

Mostly, I like figuring out how complicated things work and making them easier to use.

*And occasionally fixing things that probably would have been easier not to take apart in the first place.*
