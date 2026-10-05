# Vazhion

[![Release](https://img.shields.io/github/v/release/vazhion/vazhion)](https://github.com/vazhion/vazhion/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/vazhion/vazhion/total)](https://github.com/vazhion/vazhion/releases)

<p align="center">
  <img src="docs/logo.svg" alt="Vazhion" width="96">
</p>

SSH, tunnels, Docker, and Kubernetes in one desktop app.

Local-first workstation for DevOps, SRE, and platform engineers.

## Screenshots

**Hosts and quick connect**

<img src="docs/01-hosts.png" alt="Hosts and quick connect" width="720">

**Integrated terminal**

<img src="docs/02-terminal.png" alt="Integrated terminal" width="720">

**Host monitor**

<img src="docs/03-monitor.png" alt="Host monitor" width="720">

**Remote files and Kubernetes**

<img src="docs/04-files-kubernetes.png" alt="Remote files and Kubernetes" width="720">

**Kube Console**

<img src="docs/05-kube-console.png" alt="Kube Console" width="720">

## Download

<a href="https://apps.microsoft.com/detail/vazhion"><img src="https://get.microsoft.com/images/en-us%20dark.svg" alt="Get it from Microsoft" height="48"></a>
&nbsp;
<a href="https://github.com/vazhion/vazhion/releases/latest">Windows x64 zip (unsigned)</a>

The Windows zip is unsigned. SmartScreen can warn the first time you open it.

Open [the latest release](https://github.com/vazhion/vazhion/releases/latest) and download the file named below. Check `SHA256SUMS.txt` on that release before you run a download.

| Platform | Package | File |
| --- | --- | --- |
| Windows | [Portable zip, x64, unsigned](https://github.com/vazhion/vazhion/releases/latest) | `vazhion-Windows-x64-<version>.zip` |
| Linux | [AppImage](https://github.com/vazhion/vazhion/releases/latest) | `vazhion-Linux-x64-<version>.AppImage` |
| Linux | [Debian / Ubuntu .deb](https://github.com/vazhion/vazhion/releases/latest) | `vazhion-<version>-Linux.deb` |
| Linux | [Fedora / RHEL .rpm](https://github.com/vazhion/vazhion/releases/latest) | `vazhion-<version>-Linux.rpm` |
| Linux | [Tarball](https://github.com/vazhion/vazhion/releases/latest) | `vazhion-Linux-x64-<version>.tar.gz` |
| macOS | Not in this release | — |

## Requirements

- Windows 10 version 1809 or later, 64-bit
- Linux x64

## Install

Windows zip: extract the archive and run `vazhion.exe`.

Linux AppImage:

```sh
chmod +x vazhion-Linux-x64-*.AppImage
./vazhion-Linux-x64-*.AppImage
```

Debian or Ubuntu:

```sh
sudo apt install ./vazhion-*-Linux.deb
```

Fedora or RHEL:

```sh
sudo rpm -i vazhion-*-Linux.rpm
```

## Issues

Use [Issues](https://github.com/vazhion/vazhion/issues) for bugs and feature requests. Include the version, operating system, and steps.

## License and privacy

- [EULA.txt](EULA.txt)
- [PRIVACY.md](PRIVACY.md)
- [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md)
