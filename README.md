<a id="readme-top"></a>
<div align="center">
  <a href="https://github.com/AMDphreak/Windows-Theme-Autochanger/graphs/contributors"><img src="https://img.shields.io/github/contributors/AMDphreak/Windows-Theme-Autochanger.svg?style=for-the-badge" alt="Contributors"></a>
  <a href="https://github.com/AMDphreak/Windows-Theme-Autochanger/network/members"><img src="https://img.shields.io/github/forks/AMDphreak/Windows-Theme-Autochanger.svg?style=for-the-badge" alt="Forks"></a>
  <a href="https://github.com/AMDphreak/Windows-Theme-Autochanger/stargazers"><img src="https://img.shields.io/github/stars/AMDphreak/Windows-Theme-Autochanger.svg?style=for-the-badge" alt="Stargazers"></a>
  <a href="https://github.com/AMDphreak/Windows-Theme-Autochanger/issues"><img src="https://img.shields.io/github/issues/AMDphreak/Windows-Theme-Autochanger.svg?style=for-the-badge" alt="Issues"></a>

  <h3 align="center">Windows Theme Autochanger</h3>
  <p align="center">
    Dark mode auto-changer for Windows 11 at night — switch between Light and Dark themes on a schedule.
    <br />
    <br />
    <a href="https://desktop-tooling.github.io/docs/windows-theme-autochanger/"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/AMDphreak/Windows-Theme-Autochanger/issues">Report Bug</a>
    &middot;
    <a href="https://github.com/AMDphreak/Windows-Theme-Autochanger/issues">Request Feature</a>
  </p>
</div>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li><a href="#getting-started">Getting Started</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

## About The Project

Windows Theme Autochanger automatically sets your Windows Theme to a pre-defined Dark Mode at night and Light Mode during the day. Both can be set. You can also have the app not change theme background and only change the window controls color mode.

The app runs in the background as a service and has an app icon that runs in the System Tray. You can enable or disable the service from the app or System Tray icon.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

* **Runtime** — [![Go][Go.dev]][Go-url] — service and tray application

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Getting Started

Clone the repository and build with Go:

```powershell
git clone https://github.com/AMDphreak/Windows-Theme-Autochanger.git
cd Windows-Theme-Autochanger
go build ./...
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Usage

Run the built binary or install as a Windows service. Configure light/dark schedule and whether to change wallpaper or window chrome only from the system tray UI.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contributing

Contributions, issues, and feature requests are welcome. Open an issue or pull request on GitHub.

### Top contributors

<a href="https://github.com/AMDphreak/Windows-Theme-Autochanger/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=AMDphreak/Windows-Theme-Autochanger" alt="contributors" />
</a>

For per-person profile links, prefer [all-contributors](https://allcontributors.org/).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Changelog

See [CHANGELOG.md](CHANGELOG.md) for the project history.

## Contact

Ryan Johnson — [@amdphreak](https://twitter.com/amdphreak)

Project Link: [https://github.com/AMDphreak/Windows-Theme-Autochanger](https://github.com/AMDphreak/Windows-Theme-Autochanger)

Site: [https://ryanjohnson.dev](https://ryanjohnson.dev)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
[Go.dev]: https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white
[Go-url]: https://go.dev/
