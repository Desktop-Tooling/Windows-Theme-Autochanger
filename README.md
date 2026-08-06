<a id="readme-top"></a>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]

<div align="center">
  <h1>Windows Theme Autochanger</h1>
  <p>Dark mode auto-changer for Windows 11 at night — switch between Light and Dark themes on a schedule.</p>
  <p>
    <a href="https://github.com/AMDphreak/Windows-Theme-Autochanger/issues">Report Bug</a>
    ·
    <a href="https://github.com/AMDphreak/Windows-Theme-Autochanger/issues">Request Feature</a>
  </p>
</div>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#getting-started">Getting Started</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#built-with">Built With</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

## About The Project

Windows Theme Autochanger automatically sets your Windows Theme to a pre-defined Dark Mode at night and Light Mode during the day. Both can be set. You can also have the app not change theme background and only change the window controls color mode.

The app runs in the background as a service and has an app icon that runs in the System Tray. You can enable or disable the service from the app or System Tray icon.

## Getting Started

Clone the repository and build with Go:

```powershell
git clone https://github.com/AMDphreak/Windows-Theme-Autochanger.git
cd Windows-Theme-Autochanger
go build ./...
```

## Usage

Run the built binary or install as a Windows service. Configure light/dark schedule and whether to change wallpaper or window chrome only from the system tray UI.

## Built With

* [Go](https://go.dev/) — service and tray application

## Contributing

Contributions, issues, and feature requests are welcome. Open an issue or pull request on GitHub.

## Contact

Ryan Johnson — [@amdphreak](https://twitter.com/amdphreak)

Project Link: https://github.com/AMDphreak/Windows-Theme-Autochanger

Site: https://ryanjohnson.dev

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
[contributors-shield]: https://img.shields.io/github/contributors/AMDphreak/Windows-Theme-Autochanger.svg?style=for-the-badge
[contributors-url]: https://github.com/AMDphreak/Windows-Theme-Autochanger/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/AMDphreak/Windows-Theme-Autochanger.svg?style=for-the-badge
[forks-url]: https://github.com/AMDphreak/Windows-Theme-Autochanger/network/members
[stars-shield]: https://img.shields.io/github/stars/AMDphreak/Windows-Theme-Autochanger.svg?style=for-the-badge
[stars-url]: https://github.com/AMDphreak/Windows-Theme-Autochanger/stargazers
[issues-shield]: https://img.shields.io/github/issues/AMDphreak/Windows-Theme-Autochanger.svg?style=for-the-badge
[issues-url]: https://github.com/AMDphreak/Windows-Theme-Autochanger/issues
