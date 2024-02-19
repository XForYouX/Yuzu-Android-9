-----

**Enjoy**

**Full Changelog Alpha V.8**

(https://github.com/XForYouX/Yuzu-Android-9/releases/tag/Alpha-V.8)

**Full Changelog NCE V.256**

(https://github.com/XForYouX/Yuzu-Android-9/releases/tag/V.256)

| Pull Request | Commit | Title | Author | Merged? |
|----|----|----|----|----|
| [10529](https://github.com/yuzu-emu/yuzu//pull/10529) | [`368bf2211`](https://github.com/yuzu-emu/yuzu//pull/10529/files) | caches: make critical reclamation less eager and possible in more cases | [liamwhite](https://github.com/liamwhite/) | Yes |
| [12461](https://github.com/yuzu-emu/yuzu//pull/12461) | [`acc26667b`](https://github.com/yuzu-emu/yuzu//pull/12461/files) | Rework Nvdec and VIC to fix out-of-order videos, and speed up decoding. | [Kelebek1](https://github.com/Kelebek1/) | Yes |
| [12749](https://github.com/yuzu-emu/yuzu//pull/12749) | [`aad4b0d6f`](https://github.com/yuzu-emu/yuzu//pull/12749/files) | general: workarounds for SMMU syncing issues | [liamwhite](https://github.com/liamwhite/) | Yes |
| [13000](https://github.com/yuzu-emu/yuzu//pull/13000) | [`461eaca7e`](https://github.com/yuzu-emu/yuzu//pull/13000/files) | device_memory_manager: skip unregistered interfaces on invalidate | [liamwhite](https://github.com/liamwhite/) | Yes |
| [13006](https://github.com/yuzu-emu/yuzu//pull/13006) | [`3067bfd12`](https://github.com/yuzu-emu/yuzu//pull/13006/files) | buffer_cache: use mapped range with large vertex buffer size | [liamwhite](https://github.com/liamwhite/) | Yes |
| [13026](https://github.com/yuzu-emu/yuzu//pull/13026) | [`462ea921e`](https://github.com/yuzu-emu/yuzu//pull/13026/files) |  shader_recompiler: fix non-const offset for arrayed image types  | [liamwhite](https://github.com/liamwhite/) | Yes |
| [13031](https://github.com/yuzu-emu/yuzu//pull/13031) | [`110969e20`](https://github.com/yuzu-emu/yuzu//pull/13031/files) | service: btm: Migrate service to new IPC | [german77](https://github.com/german77/) | Yes |
| [13035](https://github.com/yuzu-emu/yuzu//pull/13035) | [`940a71422`](https://github.com/yuzu-emu/yuzu//pull/13035/files) | vi: manage resources independently of nvnflinger and refactor | [liamwhite](https://github.com/liamwhite/) | Yes |
| [13048](https://github.com/yuzu-emu/yuzu//pull/13048) | [`d45a12826`](https://github.com/yuzu-emu/yuzu//pull/13048/files) | ns: rewrite for new IPC | [liamwhite](https://github.com/liamwhite/) | Yes |


End of merge log. You can find the original README.md below the break.

-----

<!--
SPDX-FileCopyrightText: 2018 yuzu Emulator Project
SPDX-License-Identifier: GPL-2.0-or-later
-->

<h1 align="center">
  <br>
  <a href="https://yuzu-emu.org/"><img src="https://raw.githubusercontent.com/yuzu-emu/yuzu-assets/master/icons/icon.png" alt="yuzu" width="200"></a>
  <br>
  <b>yuzu</b>
  <br>
</h1>

<h4 align="center"><b>yuzu</b> is the world's most popular, open-source, Nintendo Switch emulator — started by the creators of <a href="https://citra-emu.org" target="_blank">Citra</a>.
<br>
It is written in C++ with portability in mind, and we actively maintain builds for Windows, Linux and Android.
</h4>

<p align="center">
    <a href="https://dev.azure.com/yuzu-emu/yuzu/">
        <img src="https://dev.azure.com/yuzu-emu/yuzu/_apis/build/status/yuzu%20mainline?branchName=master"
            alt="Azure Mainline CI Build Status">
    </a>
    <a href="https://discord.com/invite/u77vRWY">
        <img src="https://img.shields.io/discord/398318088170242053?color=5865F2&label=yuzu&logo=discord&logoColor=white"
            alt="Discord">
    </a>
</p>

<p align="center">
  <a href="#compatibility">Compatibility</a> |
  <a href="#development">Development</a> |
  <a href="#building">Building</a> |
  <a href="#download">Download</a> |
  <a href="#support">Support</a> |
  <a href="#license">License</a>
</p>

## Compatibility

The emulator is capable of running most commercial games at full speed, provided you meet the [necessary hardware requirements](https://yuzu-emu.org/help/quickstart/#hardware-requirements).

For a full list of games yuzu supports, please visit our [Compatibility page](https://yuzu-emu.org/game/).

Check out our [website](https://yuzu-emu.org/) for the latest news on exciting features, monthly progress reports, and more!

## Development

Most of the development happens on GitHub. It's also where [our central repository](https://github.com/yuzu-emu/yuzu) is hosted. For development discussion, please join us on [Discord](https://discord.com/invite/u77vRWY).

If you want to contribute, please take a look at the [Contributor's Guide](https://github.com/yuzu-emu/yuzu/wiki/Contributing) and [Developer Information](https://github.com/yuzu-emu/yuzu/wiki/Developer-Information).
You can also contact any of the developers on Discord in order to know about the current state of the emulator.

If you want to contribute to the user interface translation project, please check out the [yuzu project on transifex](https://www.transifex.com/yuzu-emulator/yuzu). We centralize translation work there, and periodically upstream translations.

## Building

* __Windows__: [Windows Build](https://github.com/yuzu-emu/yuzu/wiki/Building-For-Windows)
* __Linux__: [Linux Build](https://github.com/yuzu-emu/yuzu/wiki/Building-For-Linux)

## Download

You can download the latest releases automatically via the installer on our [downloads](https://yuzu-emu.org/downloads/) page.


## Support

If you enjoy the project and want to support us financially, check out our Patreon!

<a href="https://www.patreon.com/yuzuteam">
    <img src="https://c5.patreon.com/external/logo/become_a_patron_button@2x.png" width="160">
</a>

Any donations received will go towards things like:
* Switch consoles to explore and reverse-engineer the hardware
* Switch games for testing, reverse-engineering, and implementing new features
* Web hosting and infrastructure setup
* Software licenses (e.g. Visual Studio, IDA Pro, etc.)
* Additional hardware (e.g. GPUs as-needed to improve rendering support, other peripherals to add support for, etc.)

If you wish to support us a different way, please join our [Discord](https://discord.gg/u77vRWY) and talk to bunnei. You may also contact: donations@yuzu-emu.org.

## License

yuzu is licensed under the GPLv3 (or any later version). Refer to the [LICENSE.txt](https://github.com/yuzu-emu/yuzu/blob/master/LICENSE.txt) file.
