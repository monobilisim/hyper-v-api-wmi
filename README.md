[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![GPL License][license-shield]][license-url]

[![Readme in English](https://img.shields.io/badge/Readme-English-blue)](README.md)
[![Readme in Turkish](https://img.shields.io/badge/Readme-Turkish-red)](README.tr.md)

<div align="center">
<a href="https://mono.net.tr/">
  <img src="https://monobilisim.com.tr/images/mono-bilisim.svg" width="340"/>
</a>

<h2 align="center">hyper-v-rest-wmi</h2>
<b>hyper-v-rest-wmi</b> is a tool for accessing Hyper-V VM information through RESTful API.
</div>

---

## Table of Contents

- [Table of Contents](#table-of-contents)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

---

## Installation

1. Go to the [Releases](https://github.com/monobilisim/hyper-v-rest-wmi/releases) page.
2. Download *portable* or *setup* package.
3. Run it!

## Usage

- All virtual machines: `/vms`
- CPU information: `/vms/<VM-ID>/summary`
- RAM information: `/vms/<VM-ID>/memory`
- Disk information: `/vms/<VM-ID>/vhd`
- Network information: `/vms/<VM-ID>/ip`
- Version: `/version`

---

## License

hyper-v-rest-wmi is GPL-3.0 licensed. See [LICENSE](LICENSE) file for details.

[contributors-shield]: https://img.shields.io/github/contributors/monobilisim/hyper-v-rest-wmi.svg?style=for-the-badge
[contributors-url]: https://github.com/monobilisim/hyper-v-rest-wmi/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/monobilisim/hyper-v-rest-wmi.svg?style=for-the-badge
[forks-url]: https://github.com/monobilisim/hyper-v-rest-wmi/network/members
[stars-shield]: https://img.shields.io/github/stars/monobilisim/hyper-v-rest-wmi.svg?style=for-the-badge
[stars-url]: https://github.com/monobilisim/hyper-v-rest-wmi/stargazers
[issues-shield]: https://img.shields.io/github/issues/monobilisim/hyper-v-rest-wmi.svg?style=for-the-badge
[issues-url]: https://github.com/monobilisim/hyper-v-rest-wmi/issues
[license-shield]: https://img.shields.io/github/license/monobilisim/hyper-v-rest-wmi.svg?style=for-the-badge
[license-url]: https://github.com/monobilisim/hyper-v-rest-wmi/blob/master/LICENSE
