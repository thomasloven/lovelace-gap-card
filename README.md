gap-card
========

[![hacs_badge](https://img.shields.io/badge/HACS-Default-orange.svg)](https://github.com/custom-components/hacs)

A dummy card that is invisible, but has a height. It's most useful together with [layout-card](https://github.com/thomasloven/lovelace-layout-card)

![gap_card](https://user-images.githubusercontent.com/1299821/53566682-32b17a00-3b5d-11e9-9794-eace8ae8c0c2.jpg)


# Installation instructions

For installation instructions [see this guide](https://github.com/thomasloven/hass-config/wiki/Lovelace-Plugins).

The recommended type of this plugin is: `module`.

```yaml
resources:
  url: /local/gap-card.js
  type: module
```

# Usage instructions

```yaml
type: custom:gap-card
height: <height>
size: <size>
```

### `<height>`
Optional. Default: 50

The height of the gap, in pixels.

### `<size>`
Optional. Default: `<height>`/50

The size of the card as seen by the layouting engine.

---
<a href="https://www.buymeacoffee.com/uqD6KHCdJ" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/white_img.png" alt="Buy Me A Coffee" style="height: auto !important;width: auto !important;" ></a>
