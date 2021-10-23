# Paper Theme

<img src="./logo.png" align="right"
     alt="Size Limit logo by Anton Lovchikov" width="120" height="120">

The [Logseq](https://logseq.com/) Paper theme is a minimal theme, where the page and journal container is elevated from the user interface. Therefore putting it front and center for a distractionless writing experience.

> **🚧 NOTE**:This is an early version of this theme. There are a lot of rough edges and a couple styling issues. If you find a bug, please open an issue by [clicking here](https://github.com/wirtzdan/logseq-paper-theme/issues/new).

The theme is build on top of the great [Logseq Dev Theme](https://github.com/pengx17/logseq-dev-theme) by [Peng Xiao](https://github.com/pengx17) and inspired by the work of [Fabrizio Rinaldi](https://twitter.com/linuz90) with his [Better Roam Research](https://github.com/linuz90/better-roam-research) theme.

## Screenshot

<img src="./demo.png" />

## Usage

The easiest way to adopt this theme is to use jsDelivr CDN by adding the following lines to your `custom.css`.

```css
/* This must be the first line of the custom.css with other import rules */
@import url("https://cdn.jsdelivr.net/gh/wirtzdan/logseq-paper-theme@master/custom.css");

/* You can toggle these variables between "block" (Visible) and "none" (Hidden) to show or hide different elements of the UI */
:root {
  --display-recent-pages: block;
  --display-search-button: block;
  --display-arrow-navigation: block;
  --display-help-button: block;
}

/* You can also add other styles below to override the default theme values */
```

Alternatively, you can download this repo and load it as a Logseq Theme Plugin.
