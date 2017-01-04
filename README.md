# <a href="/">
<svg xmlns="http://www.w3.org/2000/svg" width="165" height="64" viewBox="0 0 200 41">
    <defs>
        <mask id="logo-mask">
            <path fill="#fff" d="M15.65.85c6.3 0 9.6 4.17 9.6 9.4 0 5.93-4.3 11.33-11.78 11.33H8.8l-1.04 10.2H.28L3.48.85h12.17zm-5.4 7.03l-.77 7.03h4.26c2.54 0 4.04-1.67 4.04-3.9 0-1.58-1-3.12-3.13-3.12h-4.4zM23.36 21.85c0-7 5.85-12.2 12.8-12.2 5.98 0 10.65 4.4 10.65 10.43 0 7.03-6.02 12.15-12.78 12.15-6.12 0-10.66-4.35-10.66-10.38zm16.28-1.27c0-2.4-1.58-4.4-4.03-4.4-2.85 0-5.03 2.4-5.03 5.2 0 2.33 1.55 4.32 4 4.32 2.9 0 5.07-2.4 5.07-5.12zM55.66 10.1l.1 2.3s1.86-2.75 6.12-2.75c4.94 0 8.8 4.17 8.8 10.25 0 7.03-5.36 12.33-11.02 12.33-3.9 0-5.5-2.35-5.5-2.35l-1.13 10.97h-7.2l3.2-30.75h6.63zm8 10.3c0-2.32-1.55-4.22-4.14-4.22-2.77 0-4.13 2.18-4.13 2.18l-.55 5.12s.9 2.18 3.67 2.18c2.95 0 5.13-2.45 5.13-5.26zM91.18 31.78h-7.2l1.35-12.8c0-.13.05-.4.05-.67 0-1.26-.64-1.98-1.95-1.98-1.68 0-3.54 1.67-3.54 1.67l-1.46 13.78h-7.2L73.5 10.1h6.8l.1 2.18s2.98-2.54 6.3-2.54c3.53 0 4.66 2.63 4.66 2.63s3.27-2.63 6.94-2.63c4.86 0 7.08 2.72 7.08 7.12 0 .54-.05 1.13-.1 1.68l-1.35 13.24H96.7l1.33-12.38c.05-.45.05-.64.05-.9 0-1.5-.77-2.18-1.95-2.18-1.77 0-3.5 1.72-3.5 1.72l-1.45 13.74M106.16 21.85c0-7 5.85-12.2 12.8-12.2 5.98 0 10.65 4.4 10.65 10.43 0 7.03-6.02 12.15-12.78 12.15-6.13 0-10.66-4.35-10.66-10.38zm16.28-1.27c0-2.4-1.6-4.4-4.03-4.4-2.85 0-5.03 2.4-5.03 5.2 0 2.33 1.54 4.32 4 4.32 2.9 0 5.07-2.4 5.07-5.12zM140.4 10.1l.5-4.76h-7.2l-.5 4.76h-3.13l-.68 6.53h3.12l-1.6 15.15h7.23l1.58-15.15h5.18l-1.57 15.15h7.26l2.25-21.68H140.4M146.46.9l-.64 6.16h7.5l.62-6.16h-7.48M153.05 21.85c0-7 5.85-12.2 12.8-12.2 5.97 0 10.65 4.4 10.65 10.43 0 7.03-6.04 12.15-12.8 12.15-6.12 0-10.65-4.35-10.65-10.38zm16.28-1.27c0-2.4-1.6-4.4-4.04-4.4-2.86 0-5.04 2.4-5.04 5.2 0 2.33 1.54 4.32 4 4.32 2.9 0 5.07-2.4 5.07-5.12zM198 31.78h-7.2l1.26-12.02c.05-.4.05-.63.05-.95 0-1.5-.76-2.62-2.62-2.62-2.4 0-4.36 1.95-4.36 1.95l-1.4 13.65h-7.2l2.25-21.68h6.9v2.3s2.9-2.7 6.44-2.7c3.95 0 7.3 2.53 7.3 7.75 0 .4-.04 1-.08 1.5L198 31.77"></path>
        </mask>
        <linearGradient id="logo-gradient">
            <stop offset="0%" stop-color="#c000fe"></stop>
            <stop offset="100%" stop-color="#fd0c74"></stop>
        </linearGradient>
    </defs>
    <g fill="none" fill-rule="evenodd" mask="url(#logo-mask)">
        <rect fill="url(#logo-gradient)" width="200" height="41"></rect>
    </g>
</svg>
</a>
        

## The JavaScript motion engine.

Use tweens, physics and user input to create unique animations and interactions.

Popmotion is tiny, at ~8kb including full CSS, SVG and SVG `path` render support - that's 75% smaller than GreenSock. It's also flexible, allowing custom actions and renderers to be created with ease.

It also exposes its interal render loop, allowing you to schedule any callback during or after the `update` and `render` steps.

[![npm version](https://img.shields.io/npm/v/popmotion.svg?style=flat-square)](https://www.npmjs.com/package/popmotion)
[![npm downloads](https://img.shields.io/npm/dm/popmotion.svg?style=flat-square)](https://www.npmjs.com/package/popmotion)
[![Twitter Follow](https://img.shields.io/twitter/follow/espadrine.svg?style=social&label=Follow)](http://twitter.com/popmotionjs)

[Slack](https://popmotion.slack.com)

## Installation

### npm

In your project root:

```bash
npm install --save popmotion
```

In your javascript module:

```javascript
import { tween } from 'popmotion';
```

### File include

Download `popmotion.global.min.js` from our [GitHub repo](https://github.com/Popmotion/popmotion/tree/master/dist) and include it in your HTML document:

```html
<script src="path/to/popmotion.global.min.js"></script>
```

Popmotion is then available as the global variable `popmotion`.

## Quick start

Creating basic motion like tweens and physics in Popmotion is simple. For example, here's a simple tween that prints its output to the `console`:

```javascript
import { tween } from 'popmotion';

tween({
  to: 100,
  onUpdate: (v) => console.log(v)
}).start();
```

To use that tween to move an actual DOM element, we can create a CSS renderer.

```javascript
const ballRenderer = css(document.getElementById('ball'));

tween({
  to: 100,
  onUpdate: (v) => ballRenderer.set('x', v)
}).start();
```
