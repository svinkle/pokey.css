# pokey.css

<a href="https://github.com/svinkle/pokey.css"><img
  src="https://emojipedia-us.s3.amazonaws.com/thumbs/160/emoji-one/5/horse-face_1f434.png" alt="pokey.css"
  width="160" height="160" align="right"></a>

> Make things visually clickable 👆

[![npm][npm-image]][npm-url] [![license][license-image]][license-url]
[![changelog][changelog-image]][changelog-url]

**NPM**

```sh
npm install --save pokey.css
```

**CDN**

See https://unpkg.com/pokey.css/pokey.css

**Download**

See https://svinkle.github.io/pokey.css/latest/pokey.css

## Usage

**Sass Import**

```css
@import '../node_modules/pokey.css/pokey.css';
```

**HTML (via unpkg)**

```html
<link rel="stylesheet" href="https://unpkg.com/pokey.css/pokey.css">
```

## What does it do?

* Adds extra visual affordance to _some_ "clickable" HTML elements via `cursor: pointer` CSS property
* Adds an added bonus: `cursor: not-allowed` CSS property on `disabled` elements

## Why?

**Why not?** Why not add that visual affordance for users to get through an app even faster. Provide the "hand" cursor pointer on things that are clickable in order to get the point across, "Yes, you can click this."

This also come in handy with today’s flat design. People are making transparent buttons with colored borders, essentially link styles with minor affordance of a `border`. Let's help inform our users and give them a sense of confidence.

> “What is this thing? I don’t have time to figure it out, but I _do_ see the little hand here, gonna click!” :fire:

Who stands to benefit? Everyone.

## Browser support

* Chrome
* Edge
* Firefox
* Internet Explorer 10+
* Safari 8+
* Opera

[changelog-image]: https://img.shields.io/badge/changelog-md-blue.svg?style=flat-square
[changelog-url]: CHANGELOG.md
[license-image]: https://img.shields.io/npm/l/pokey.css.svg?style=flat-square
[license-url]: LICENSE.md
[npm-image]: https://img.shields.io/npm/v/pokey.css.svg?style=flat-square
[npm-url]: https://npmjs.com/package/pokey.css
