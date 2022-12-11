# ProcessWire CMS/CMF Addon with TailwindCSS, AlpineJS, and BarbaJS

This is not a **[ProcessWire CMS/CMF](https://processwire.com/) _profile_** you would use to install or set up a new ProcessWire instance. This is more a _copy & paste_ template that gives you all the necessary files, packages and scrips to use **TailwindCSS**, **AlpineJS**, and/or **BarbaJS** with sane defaults and popular plugins available (need to be activated within the _src/files_).

## TailwindCSS

Homepage: [TailwindCSS](https://tailwindcss.com/)

### TailwindCSS Plugins

- [Plugin: Typography](https://tailwindcss.com/docs/typography-plugin)
- [Plugin: Forms](https://github.com/tailwindlabs/tailwindcss-forms)
- [Plugin: Aspect ratio](https://github.com/tailwindlabs/tailwindcss-aspect-ratio)
- [Plugin: Line clamp](https://github.com/tailwindlabs/tailwindcss-line-clamp)
- [Plugin: Container queries](https://github.com/tailwindlabs/tailwindcss-container-queries)

_tailwind.config.js_

```js
./site/templates/**/*.php
./site/templates/**/*.latte
./site/templates/**/*.twig
./site/templates/**/*.html
./site/templates/**/*.js
```

---

## AlpineJS

Homepage: [AlpineJS](https://alpinejs.dev/)

### AlpineJS Plugins

- [Plugin: Mask](https://alpinejs.dev/plugins/mask)
- [Plugin: Intersect](https://alpinejs.dev/plugins/intersect)
- [Plugin: Persist](https://alpinejs.dev/plugins/persist)
- [Plugin: Focus](https://alpinejs.dev/plugins/focus)
- [Plugin: Collapse](https://alpinejs.dev/plugins/collapse)
- [Plugin: Morph](https://alpinejs.dev/plugins/morph)

---

## BarbaJS

Homepage: [BarbaJS](https://barba.js.org/)

### BarbaJS Plugins

- [Plugin: Prefetch](https://barba.js.org/docs/plugins/prefetch/)

---

### How to Update NPM Packages

#### _tl,dr_

```sh
npm install -g npm-check-updates
ncu --upgrade
npm install
```

_Initial commit: 2022-12-11_
