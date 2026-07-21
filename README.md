![](../../workflows/gds/badge.svg) ![](../../workflows/docs/badge.svg) ![](../../workflows/test/badge.svg) ![](../../workflows/fpga/badge.svg)

# Tiny Tapeout Verilog Project Template

- [Read the documentation for project](docs/info.md)

## What is Tiny Tapeout?

Tiny Tapeout is an educational project that aims to make it easier and cheaper than ever to get your digital and analog designs manufactured on a real chip.

To learn more and get started, visit https://tinytapeout.com.

<img width="1240" height="588" alt="Screenshot_20-7-2026_204757_gds-viewer tinytapeout com" src="https://github.com/user-attachments/assets/7ac7cbda-5590-4871-b507-1a087cf793ab" />
<img width="1240" height="588" alt="Screenshot_20-7-2026_204846_gds-viewer tinytapeout com" src="https://github.com/user-attachments/assets/ae08e25a-aba7-4a3f-bb63-e2fa809b0be1" />
<img width="1240" height="588" alt="Screenshot_20-7-2026_20495_gds-viewer tinytapeout com" src="https://github.com/user-attachments/assets/6b7f70e7-c114-4260-a674-28b0b9d8cec1" />
<img width="1240" height="588" alt="Screenshot_20-7-2026_204923_gds-viewer tinytapeout com" src="https://github.com/user-attachments/assets/c1264535-22c4-43c6-847d-b81c13cae38d" />
<img width="1240" height="588" alt="Screenshot_20-7-2026_204941_gds-viewer tinytapeout com" src="https://github.com/user-attachments/assets/a8f89696-e385-4ad5-ac58-923d2589e8e2" />
<img width="1240" height="588" alt="Screenshot_20-7-2026_205152_gds-viewer tinytapeout com" src="https://github.com/user-attachments/assets/c78407e1-d90a-478d-a2b7-f8c15f85d638" />



1. Add your Verilog files to the `src` folder.
2. Edit the [info.yaml](info.yaml) and update information about your project, paying special attention to the `source_files` and `top_module` properties. If you are upgrading an existing Tiny Tapeout project, check out our [online info.yaml migration tool](https://tinytapeout.github.io/tt-yaml-upgrade-tool/).
3. Edit [docs/info.md](docs/info.md) and add a description of your project.
4. Adapt the testbench to your design. See [test/README.md](test/README.md) for more information.

The GitHub action will automatically build the ASIC files using [LibreLane](https://www.zerotoasiccourse.com/terminology/librelane/).

## Enable GitHub actions to build the results page

- [Enabling GitHub Pages](https://tinytapeout.com/faq/#my-github-action-is-failing-on-the-pages-part)

## Resources

- [FAQ](https://tinytapeout.com/faq/)
- [Digital design lessons](https://tinytapeout.com/digital_design/)
- [Learn how semiconductors work](https://tinytapeout.com/siliwiz/)
- [Join the community](https://tinytapeout.com/discord)
- [Build your design locally](https://www.tinytapeout.com/guides/local-hardening/)

## What next?

- [Submit your design to the next shuttle](https://app.tinytapeout.com/).
- Edit [this README](README.md) and explain your design, how it works, and how to test it.
- Share your project on your social network of choice:
  - LinkedIn [#tinytapeout](https://www.linkedin.com/search/results/content/?keywords=%23tinytapeout) [@TinyTapeout](https://www.linkedin.com/company/100708654/)
  - Mastodon [#tinytapeout](https://chaos.social/tags/tinytapeout) [@matthewvenn](https://chaos.social/@matthewvenn)
  - X (formerly Twitter) [#tinytapeout](https://twitter.com/hashtag/tinytapeout) [@tinytapeout](https://twitter.com/tinytapeout)
  - Bluesky [@tinytapeout.com](https://bsky.app/profile/tinytapeout.com)


