### Hey, I'm NergYR 👋

Network & security student, mostly writing C++ and shell.
This GitHub is still a bit messy — school projects, old bots, experiments — but one project
is where most of my time goes now:

<br>

<p align="center">
  <a href="https://github.com/Endorium-Group/EndoriumFort-CE">
    <img src="https://raw.githubusercontent.com/Endorium-Group/EndoriumFort-CE/master/assets/logo-full-blue.png" alt="EndoriumFort" height="60">
  </a>
</p>

<p align="center">
  <b>A self-hosted PAM bastion.</b><br>
  One gateway for SSH, HTTP, RDP, VNC, Kubernetes and raw TCP, with an audit trail you can actually prove.
</p>

<p align="center">
  <a href="https://github.com/Endorium-Group/EndoriumFort-CE">Repository</a> ·
  <a href="https://endorium.space">Website</a> ·
  <a href="https://endorium.space/docs/">Docs</a> ·
  <a href="https://github.com/Endorium-Group/EndoriumFort-CE/releases">Releases</a>
</p>

<p align="center">
  <img src="https://img.shields.io/github/v/release/Endorium-Group/EndoriumFort-CE?style=flat-square&label=release" alt="release">
  <img src="https://img.shields.io/badge/C%2B%2B17-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++17">
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React">
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go">
</p>

Instead of handing out SSH keys and admin passwords, people connect through EndoriumFort.
The browser is the client, credentials stay in the vault, and every session leaves a
hash-chained trace. A few things it does today:

- web SSH terminal, HTTP proxy and remote browser isolation, no client to install
- MFA with TOTP and passkeys, encrypted credential vault, per-user access scope
- live session shadowing, command guard, audit export and reporting
- runs on your own hardware, works air-gapped, no phone-home

Try it in one command:

```bash
docker run -d -p 80:80 ghcr.io/endorium-group/endoriumfort:latest
```

The Community Edition is public. Around it there's also
[DrawBridge](https://github.com/Endorium-Group/EndoriumFort-DrawBridge) (the agent),
[Bird](https://github.com/Endorium-Group/EndoriumFort-Bird) (manage your bastion from your phone)
and [EndoriumSpace](https://github.com/Endorium-Group/EndoriumSpace) (the website).
Issues, feedback and stars are all welcome.

<br>

#### Other stuff I've built

- [SAE-PentestAD](https://github.com/NergYR/SAE-PentestAD) — Active Directory pentest, BUT R&T
- [Projet_securite](https://github.com/NergYR/Projet_securite) — access control system for my high school's entrance
- [DHCP-KEA-Configurator](https://github.com/NergYR/DHCP-KEA-Configurator) — config helper for ISC Kea
- [NergBot](https://github.com/NergYR/NergBot) — an old JavaScript bot, still here for nostalgia

#### Usually working with

C++ · C · Go · Python · Bash · PowerShell · Linux · Docker · networking (lots of it)

<br>

<sub>Find me through <a href="https://endorium.space">endorium.space</a> or open an issue on any repo.</sub>
