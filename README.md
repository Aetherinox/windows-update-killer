<div align="center">
<h6>No updates until 12-31-2051</h6>
<h1>♾️ Windows Update Killer ♾️</h1>

<br />

<p>A simple windows registry tweak which allows you to pause Windows updates until 12-31-2051.</p>

<br />

</div>

<div align="center">

<!-- prettier-ignore-start -->
[![Version][github-version-img]][github-version-uri]
[![Size][github-size-img]][github-size-img]
[![Last Commit][github-commit-img]][github-commit-img]
<!-- prettier-ignore-end -->

</div>

<br />

---

<br />

- [About](#about)
  - [Why?](#why)
  - [But... Updates Good](#but-updates-good)
- [Install](#install)
- [Re-enabling Updates](#re-enabling-updates)
- [Preview](#preview)

<br />

---

<br />

## About
This is a simple no-nonsense script to pause Windows update until 2051.
Pretty much allowing you to update whenever you want instead of waking up to a rebooted machine.

<br />

> [!WARNING]
> This script is meant to be used in situations where you do not want your system automatically restarting while it is idle. I highly recommnend that you do run Windows updates once per month and ensure that you have the latest packages installed. Some of these updates could include security patches for important vulnerabilities.

<br />

### Why?
I was tired of the complicated methods. I don't like having my machine reboot and me not being able to control Windows Update. It's my biggest pet peeve with Windows. This script makes my life so much easier because now I don't have to deal with it. The point was just to have a stupid simple solution using a script anyone can open in notepad and view the code. Without fear of viruses and people injecting crap onto your system. Enjoy.

<br />

### But... Updates Good
Yes, I get it. _"Thou shalt not leave thy computer outdated too long"_.
I don't. But I keep certain apps running for work, and they can remain open for days as I work on a project. I don't like waking up to my entire machine sitting at user sign-in. I like to work on my projects, and then once I have some spare time, I'll run updates when I want to, not when the machine decides to.

<br />

---

<br />

## Install
> [!NOTE]
> Depending on your machine's configuration, you may be able to double-click the `.reg` file and auto-install it.

- Download the `.reg` file to your computer.
- Right click on the file and select `Open With`
  ![](https://github.com/user-attachments/assets/ac56d320-a712-433c-813f-4bbcf7132b84)

- Select `Registry Editor`
- Click `Yes` when prompted if you're sure you wish to continue

<br />

> [!NOTE]
> As of 08/03/2024, you no longer have to view the Windows Update window. Updates are automatically paused as soon as the registry tweak is applied. However, the instructions are still provided below:

<br />

- In Windows, click `Start` -> `Run` -> type `control update` and press ENTER.
  - You can also access the Windows Update window by clicking your start menu, selecting **Run**, and typing:
   ```shell
    ms-settings:windowsupdate
   ```
- Near the `Pause Updates` section, click the dropdown and select how long you want updates to pause for.
- Keep the script somewhere in case you need to reinstall / wipe your machine.

<br />

---

<br />

## Re-enabling Updates
To start Windows updates once again, open your start menu, type `Windows Update Settings`.

<br />

<div align="center">

<img src="https://github.com/user-attachments/assets/71bbb55d-076e-4b52-83b9-cc9bdf7f60df" width="330">

</div>

<br />

At the top of the Windows Update interface, click **Resume Updates**.

<div align="center">

<img src="https://github.com/user-attachments/assets/85310c9b-4117-4cbf-9e2a-2003c93e842c" width="530">

</div>

<br />

To pause updates again, re-run the `.reg` file in this repo.

<br />

---

<br />

## Preview

<div align="center">

<img src="https://github.com/user-attachments/assets/f8c2ef68-cfb1-4428-a07a-88ce314356a5" width="530">

</div>



<br />
<br />

<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->

<!-- BADGE > GENERAL -->
  [general-npmjs-uri]: https://npmjs.com
  [general-nodejs-uri]: https://nodejs.org
  [general-npmtrends-uri]: http://npmtrends.com/windows-update-killer

<!-- BADGE > VERSION > GITHUB -->
  [github-version-img]: https://img.shields.io/github/v/tag/Aetherinox/Windows-Update-Killer?logo=GitHub&label=Version&color=ba5225
  [github-version-uri]: https://github.com/Aetherinox/Windows-Update-Killer/releases

<!-- BADGE > VERSION > NPMJS -->
  [npm-version-img]: https://img.shields.io/npm/v/windows-update-killer?logo=npm&label=Version&color=ba5225
  [npm-version-uri]: https://npmjs.com/package/windows-update-killer

<!-- BADGE > VERSION > PYPI -->
  [pypi-version-img]: https://img.shields.io/pypi/v/windows-update-killer-plugin
  [pypi-version-uri]: https://pypi.org/project/windows-update-killer-plugin/

<!-- BADGE > LICENSE > MIT -->
  [license-mit-img]: https://img.shields.io/badge/MIT-FFF?logo=creativecommons&logoColor=FFFFFF&label=License&color=9d29a0
  [license-mit-uri]: https://github.com/Aetherinox/Windows-Update-Killer/blob/main/LICENSE

<!-- BADGE > GITHUB > DOWNLOAD COUNT -->
  [github-downloads-img]: https://img.shields.io/github/downloads/Aetherinox/Windows-Update-Killer/total?logo=github&logoColor=FFFFFF&label=Downloads&color=376892
  [github-downloads-uri]: https://github.com/Aetherinox/Windows-Update-Killer/releases

<!-- BADGE > NPMJS > DOWNLOAD COUNT -->
  [npmjs-downloads-img]: https://img.shields.io/npm/dw/%40aetherinox%2Fmkdocs-link-embeds?logo=npm&&label=Downloads&color=376892
  [npmjs-downloads-uri]: https://npmjs.com/package/windows-update-killer

<!-- BADGE > GITHUB > DOWNLOAD SIZE -->
  [github-size-img]: https://img.shields.io/github/repo-size/Aetherinox/Windows-Update-Killer?logo=github&label=Size&color=59702a
  [github-size-uri]: https://github.com/Aetherinox/Windows-Update-Killer/releases

<!-- BADGE > NPMJS > DOWNLOAD SIZE -->
  [npmjs-size-img]: https://img.shields.io/npm/unpacked-size/windows-update-killer/latest?logo=npm&label=Size&color=59702a
  [npmjs-size-uri]: https://npmjs.com/package/windows-update-killer

<!-- BADGE > CODECOV > COVERAGE -->
  [codecov-coverage-img]: https://img.shields.io/codecov/c/github/Aetherinox/Windows-Update-Killer?token=MPAVASGIOG&logo=codecov&logoColor=FFFFFF&label=Coverage&color=354b9e
  [codecov-coverage-uri]: https://codecov.io/github/Aetherinox/Windows-Update-Killer

<!-- BADGE > ALL CONTRIBUTORS -->
  [contribs-all-img]: https://img.shields.io/github/all-contributors/Aetherinox/Windows-Update-Killer?logo=contributorcovenant&color=de1f6f&label=contributors
  [contribs-all-uri]: https://github.com/all-contributors/all-contributors

<!-- BADGE > GITHUB > BUILD > NPM -->
  [github-build-img]: https://img.shields.io/github/actions/workflow/status/Aetherinox/Windows-Update-Killer/npm-release.yml?logo=github&logoColor=FFFFFF&label=Build&color=%23278b30
  [github-build-uri]: https://github.com/Aetherinox/Windows-Update-Killer/actions/workflows/npm-release.yml

<!-- BADGE > GITHUB > BUILD > Pypi -->
  [github-build-pypi-img]: https://img.shields.io/github/actions/workflow/status/Aetherinox/Windows-Update-Killer/release-pypi.yml?logo=github&logoColor=FFFFFF&label=Build&color=%23278b30
  [github-build-pypi-uri]: https://github.com/Aetherinox/Windows-Update-Killer/actions/workflows/pypi-release.yml

<!-- BADGE > GITHUB > TESTS -->
  [github-tests-img]: https://img.shields.io/github/actions/workflow/status/Aetherinox/Windows-Update-Killer/npm-tests.yml?logo=github&label=Tests&color=2c6488
  [github-tests-uri]: https://github.com/Aetherinox/Windows-Update-Killer/actions/workflows/npm-tests.yml

<!-- BADGE > GITHUB > COMMIT -->
  [github-commit-img]: https://img.shields.io/github/last-commit/Aetherinox/Windows-Update-Killer?logo=conventionalcommits&logoColor=FFFFFF&label=Last%20Commit&color=313131
  [github-commit-uri]: https://github.com/Aetherinox/Windows-Update-Killer/commits/main/

<!-- prettier-ignore-end -->
<!-- markdownlint-restore -->
