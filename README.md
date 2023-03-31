# ProcessWire CMS/CMF Addon with TailwindCSS, AlpineJS, and BarbaJS

**Caution:** This is not a **[ProcessWire CMS/CMF](https://processwire.com/) _profile_** you would use to install or set up a new ProcessWire instance. This is more a _copy & paste_ template that gives you all the necessary files, packages and scrips to use **TailwindCSS**, **AlpineJS**, and/or **BarbaJS** with sane defaults and popular plugins available right from the start (just uncomment in their specific file within _**src/files**_).

## What this addon brings to the table

### [TailwindCSS](https://tailwindcss.com/) - A utility-first CSS framework.

#### TailwindCSS Plugins

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

### [AlpineJS](https://alpinejs.dev/) - Your new, lightweight, JavaScript framework.

#### AlpineJS Plugins

- [Plugin: Mask](https://alpinejs.dev/plugins/mask)
- [Plugin: Intersect](https://alpinejs.dev/plugins/intersect)
- [Plugin: Persist](https://alpinejs.dev/plugins/persist)
- [Plugin: Focus](https://alpinejs.dev/plugins/focus)
- [Plugin: Collapse](https://alpinejs.dev/plugins/collapse)
- [Plugin: Morph](https://alpinejs.dev/plugins/morph)

---

### [BarbaJS](https://barba.js.org/) - Create badass, fluid and smooth transitions between your website’s pages.

#### BarbaJS Plugins

- [Plugin: Prefetch](https://barba.js.org/docs/plugins/prefetch/)

---

### How to Update NPM Packages

#### _tl,dr_

```sh
npm install -g npm-check-updates
ncu --upgrade
npm install
```

## Should this be a simple starter profile?

In case you think that this should be a starter profile for ProcessWire CMS/CMF please let me know. So I can create a profile and update the respository.

_Initial commit: 2022-12-11_

## Changelog

### Latest package update 2023-03-31

```
@alpinejs/collapse               ^3.11.1  →   ^3.12.0
@alpinejs/focus                  ^3.11.1  →   ^3.12.0
@alpinejs/intersect              ^3.11.1  →   ^3.12.0
@alpinejs/mask                   ^3.11.1  →   ^3.12.0
@alpinejs/morph                  ^3.11.1  →   ^3.12.0
@alpinejs/persist                ^3.11.1  →   ^3.12.0
@tailwindcss/container-queries    ^0.1.0  →    ^0.1.1
@tailwindcss/line-clamp           ^0.4.2  →    ^0.4.4
alpinejs                         ^3.11.1  →   ^3.12.0
esbuild                         ^0.17.10  →  ^0.17.14
prettier                          ^2.8.4  →    ^2.8.7
prettier-plugin-tailwindcss       ^0.2.3  →    ^0.2.6
tailwindcss                       ^3.2.7  →    ^3.3.1
```

### Latest package update 2023-02-21

```
@alpinejs/collapse            ^3.10.5  →   ^3.11.1
@alpinejs/focus               ^3.10.5  →   ^3.11.1
@alpinejs/intersect           ^3.10.5  →   ^3.11.1
@alpinejs/mask                ^3.10.5  →   ^3.11.1
@alpinejs/morph               ^3.10.5  →   ^3.11.1
@alpinejs/persist             ^3.10.5  →   ^3.11.1
@tailwindcss/typography        ^0.5.8  →    ^0.5.9
alpinejs                      ^3.10.5  →   ^3.11.1
esbuild                      ^0.16.10  →  ^0.17.10
prettier                       ^2.8.1  →    ^2.8.4
prettier-plugin-tailwindcss    ^0.2.1  →    ^0.2.3
tailwindcss                    ^3.2.4  →    ^3.2.7
```
