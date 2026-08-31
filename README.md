# J. Chang

**Software developer · IT consultant · photographer · radio enthusiast**

I build things where software meets complicated real-world systems — radio networks, cloud infrastructure, camera workflows, hardware integration, and the occasional proprietary format that looked interesting enough to reverse engineer.

<p>
  <img alt=".NET" src="https://img.shields.io/badge/.NET-512BD4?logo=dotnet&logoColor=white">
  <img alt="Avalonia" src="https://img.shields.io/badge/Avalonia-8B44AC">
  <img alt="C%23" src="https://img.shields.io/badge/C%23-239120?logo=csharp&logoColor=white">
  <img alt="Rust" src="https://img.shields.io/badge/Rust-000000?logo=rust&logoColor=white">
  <img alt="Azure" src="https://img.shields.io/badge/Azure-0078D4?logo=microsoftazure&logoColor=white">
  <img alt="AWS" src="https://img.shields.io/badge/AWS-232F3E?logo=amazonwebservices&logoColor=white">
</p>

Professionally, I run a small IT consulting business working across Microsoft 365, Azure, AWS, networking, identity, security, virtualization, automation, and cloud/systems infrastructure and architecture.

Outside client work, I build software around digital and HF radio, cross-platform applications, photography, hardware integration, reverse engineering, and signal processing.

---

## Featured work

### 📻 [DVMConsole NEO](https://github.com/RdWing/dvmconsole)

Operator console for FNE-connected digital voice radio systems.

The repository still carries its history as a fork, but NEO has since become an entirely different application. The original WPF application is gone; the architecture, interface, audio system, configuration model, diagnostics, and platform layers were rewritten from scratch.

Built with **.NET + Avalonia**, NEO supports P25, DMR, and NXDN traffic with independent channel state, multi-channel transmit routing, global PTT, talkgroup patching, secure voice, event history, recording, and graphical configuration.

Current releases support **Apple Silicon macOS, Intel macOS, and Windows x64**.

### 📷 [NP3 Studio](https://www.nikonfpc.com/)

Browser-based analyzer for Nikon's NP3 Flexible Color Picture Control format.

It grew out of reverse engineering Nikon's NP3 binary structure and can decode all 44 Picture Control parameters, visualize tone curves and LUT data, expose Nikon's color blending and three-zone color grading controls, and export the underlying data.

The parser is written in **Rust + WebAssembly**, so files stay local to the browser.

### 📡 [DVMHost](https://github.com/RdWing/dvmhost) + [FNECore](https://github.com/RdWing/fnecore)

Core pieces of the wider digital voice ecosystem that NEO works with, covering modem-host functionality, fixed-network communications, radio hardware, consoles, bridges, and networked endpoints.

---

## Cloud, IT, and infrastructure

`Microsoft 365` · `Entra ID` · `Azure` · `AWS` · `Windows` · `Linux`

`Networking` · `Virtualization` · `Identity` · `Security` · `Automation`

The work I enjoy most rarely belongs to one product. It might begin as an authentication problem, turn out to involve DNS and networking, and end with an application that made a perfectly reasonable assumption nobody documented.

I’ve also been working with practical uses of AI and workflow automation, particularly where they save time without ignoring identity, security, governance, or the business processes already in place.

---

## Radio and communications

A large part of my development work centers on professional and amateur radio systems, digital and otherwise.

`P25` · `DMR` · `NXDN` · `SDR` · `HF` · `RF` · `Digital Voice` · `Audio` · `FNE`

Other projects and forks include:

- [P25Clients](https://github.com/RdWing/P25Clients) — gateway and parrot applications for P25
- [NXDNClients](https://github.com/RdWing/NXDNClients) — gateway and parrot applications for NXDN
- [MMDVM_CM](https://github.com/RdWing/MMDVM_CM) — cross-mode conversion tools for MMDVM systems
- [KFDtool](https://github.com/RdWing/KFDtool) — P25 keyloading software and hardware tooling
- [anytone-flash-tools](https://github.com/RdWing/anytone-flash-tools) — independent flash tools for Anytone radios
- [NetworkIcom](https://github.com/RdWing/NetworkIcom) — Icom IC-7610 Ethernet control experiment in Swift/SwiftUI
- [OpenHPSDR-wdsp](https://github.com/RdWing/OpenHPSDR-wdsp) — software-defined radio and DSP work

Some are current projects; others are older experiments or forks that were useful for understanding a particular radio, protocol, or piece of hardware.

---

## Photography and digital imaging

I am a photographer with a strong interest in what happens between light reaching the sensor and the finished image appearing on screen.

`Nikon` · `Picture Controls` · `RAW` · `Color science`

`Image sensors` · `Optics` · `Computational photography` · `Image processing`

The appeal is split between making photographs and understanding what the camera is doing to them. **NP3 Studio is what happens when those two interests get too close to each other.**

---

## Software and tools

`C#` · `.NET` · `Avalonia` · `C` · `C++`

`Rust` · `WebAssembly` · `Python` · `JavaScript`

`macOS` · `Windows` · `Linux`

I am less attached to a particular language or framework than I am to understanding the system, finding the right boundary, and choosing something that will still make sense six months later.

---

I like building things that make complicated hardware and systems easier to understand, automate, and use.

*And occasionally fixing things that probably would have been easier not to take apart in the first place.*
