# @nharox/css-reset

A modern CSS reset.

## Installation

1. Install package as a dev dependency:

```bash
npm install --save-dev @nharox/css-reset
```

2. Import `reset.css`, preferably with [postcss-import](https://github.com/postcss/postcss-import) in your global CSS:

```css
/* Without @layer */
@import url('node_modules/@nharox/css-reset/reset.css');

/* With @layer */
@import url('node_modules/@nharox/css-reset/reset.css') layer(base);
```
