[![CLA assistant](https://cla-assistant.io/readme/badge/nfrechette/acl-ue4-plugin)](https://cla-assistant.io/nfrechette/acl-ue4-plugin)
[![All Contributors](https://img.shields.io/github/all-contributors/nfrechette/acl-ue4-plugin)](#contributors-)
[![GitHub release](https://img.shields.io/github/release/nfrechette/acl-ue4-plugin.svg)](https://github.com/nfrechette/acl-ue4-plugin/releases)
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/nfrechette/acl-ue4-plugin/master/LICENSE)
![UE](https://img.shields.io/badge/UE-4.25+-orange)
[![Discord](https://img.shields.io/discord/691048241864769647?label=discord)](https://discord.gg/UERt4bS)

# IMPORTANT NOTICE

As of Unreal Engine 5.3, this plugin comes out of the box and is distributed and maintained by Epic in their fork. See [here](https://nfrechette.github.io/2023/09/17/acl_in_ue/) for details.

This repository will remain mostly read-only following the next minor release and only accept critical fixes. Contributions should instead be directed to the Unreal Engine main development repository where the ACL Plugin fork lives (under **Engine/Plugins/Animation/ACLPlugin**).

Support questions and requests should be directed to the Unreal Developer Network (UDN).

====================================================

# Animation Compression Library Unreal Engine Plugin

This plugin integrates the [Animation Compression Library](https://github.com/nfrechette/acl) version [v2.0-develop](https://github.com/nfrechette/acl) within [Unreal Engine 4 and 5](https://www.unrealengine.com/en-US/blog). It is suitable for every animation clip and platform as it features a low memory footprint, high accuracy, and very fast compression and decompression.

Compared to **UE 4.25.0**, the ACL plugin compresses up to **2.8x smaller**, is up to **4.6x more accurate**, up to **56x faster to compress**, and up to **8.4x faster to decompress** (results may vary depending on the platform and data).

The documentation on how to use it can be found [here](./Docs/README.md) along with performance results.

You can find the ACL plugin on the Unreal Marketplace [here](https://www.unrealengine.com/marketplace/en-US/product/animation-compression-library).

## Getting started

If you would like to contribute to the ACL UE Plugin, make sure to check out the [contributing guidelines](CONTRIBUTING.md).

**NOTE: If you clone this repository, you MUST run the script under [.\Tools\prepare_release.py](./Tools/prepare_release.py) to package the plugin. It pre-processes some required files.**

## License, copyright, and code of conduct

This project uses the [MIT license](LICENSE).

Copyright (c) 2018 Nicholas Frechette

Please note that this project is released with a [Contributor Code of Conduct](CODE_OF_CONDUCT.md). By participating in this project you agree to abide by its terms.

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Meradrin"><img src="https://avatars.githubusercontent.com/u/7066278?v=4?s=100" width="100px;" alt="Meradrin"/><br /><sub><b>Meradrin</b></sub></a><br /><a href="https://github.com/nfrechette/acl-ue4-plugin/commits?author=Meradrin" title="Code">💻</a> <a href="#platform-Meradrin" title="Packaging/porting to new platform">📦</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/r-lyeh/statvs"><img src="https://avatars.githubusercontent.com/u/35402248?v=4?s=100" width="100px;" alt="r-lyeh"/><br /><sub><b>r-lyeh</b></sub></a><br /><a href="https://github.com/nfrechette/acl-ue4-plugin/commits?author=r-lyeh" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/nucleiis"><img src="https://avatars.githubusercontent.com/u/20119165?v=4?s=100" width="100px;" alt="nucleiis"/><br /><sub><b>nucleiis</b></sub></a><br /><a href="https://github.com/nfrechette/acl-ue4-plugin/issues?q=author%3Anucleiis" title="Bug reports">🐛</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/fjoanisPhxlabs"><img src="https://avatars.githubusercontent.com/u/90003066?v=4?s=100" width="100px;" alt="fjoanisPhxlabs"/><br /><sub><b>fjoanisPhxlabs</b></sub></a><br /><a href="https://github.com/nfrechette/acl-ue4-plugin/commits?author=fjoanisPhxlabs" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/EAirPeter"><img src="https://avatars.githubusercontent.com/u/5276153?v=4?s=100" width="100px;" alt="EAirPeter"/><br /><sub><b>EAirPeter</b></sub></a><br /><a href="https://github.com/nfrechette/acl-ue4-plugin/commits?author=EAirPeter" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/pmsimardeidos"><img src="https://avatars.githubusercontent.com/u/58734263?v=4?s=100" width="100px;" alt="pmsimardeidos"/><br /><sub><b>pmsimardeidos</b></sub></a><br /><a href="https://github.com/nfrechette/acl-ue4-plugin/commits?author=pmsimardeidos" title="Code">💻</a> <a href="https://github.com/nfrechette/acl-ue4-plugin/issues?q=author%3Apmsimardeidos" title="Bug reports">🐛</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!
