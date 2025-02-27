# BK Switch Theme JS
> Easily switch themes in your website

<img src="img/switcher.png" alt="gif" width="500" height="250" />

[![GitHub stars](https://img.shields.io/github/stars/PuneetGopinath/switch-theme-js)](https://github.com/PuneetGopinath/switch-theme-js/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/PuneetGopinath/switch-theme-js)](https://github.com/PuneetGopinath/switch-theme-js/network)
[![GitHub issues](https://img.shields.io/github/issues/PuneetGopinath/switch-theme-js)](https://github.com/PuneetGopinath/switch-theme-js/issues)
![GitHub repo size](https://img.shields.io/github/repo-size/PuneetGopinath/switch-theme-js)
![Lines of code](https://img.shields.io/tokei/lines/github/PuneetGopinath/switch-theme-js?label=total%20lines%20of%20code)
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.0-4baaaa.svg)](https://github.com/PuneetGopinath/switch-theme-js/blob/main/.github/CODE_OF_CONDUCT.md)
[![Join the chat at https://gitter.im/BaalKrshna/switch-theme](https://badges.gitter.im/BaalKrshna/switch-theme.svg)](https://gitter.im/BaalKrshna/switch-theme?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![Discord Chat](https://img.shields.io/discord/836854115526770708?color=7289da&label=discord)](https://discord.gg/EQas36CjmN)

## Features
- Themes switch without page reload
- Quick debugging
- Add your own themes and some themes ready-made in [`themes`](https://github.com/PuneetGopinath/switch-theme-js/tree/v1-dev/themes) folder
- Minified version of `index.js` automatically available in `index.min.js`
- And many more features coming

## v0
If you are looking for help with v0, you should head to the [`main` branch](https://github.com/PuneetGopinath/switch-theme-js/tree/main).
This branch is developing code for v1 release.

## Docs
See [`docs` folder](https://github.com/PuneetGopinath/switch-theme-js/tree/main/docs).

## Live demo
See [live demo](https://puneetgopinath.github.io/switch-theme-js/)

Click on "Dark theme" refresh the page, you see the page is default now set to dark theme.

## FAQs
These are the frequently asked questions:

### 1. What happens actually
This is a basic JS code, that stores the theme name in a cookie that stays for 10 days and adds the theme name to the `data-theme` attribute of the html tag.

### 2. How to design a theme?
You need to know CSS for that.

1. Think of a cool theme name
2. To select the theme in CSS, use `[data-theme="themeName"]` where `themeName` is your theme name
3. To add a button for user to switch the theme (use the html `a` tag e.g. `<a href="javascript:switchTheme.switch('dark');">Dark theme</a>`)
4. Add `onload="switchTheme.get();"` to your `body` tag
5. Add `<script async defer src="https://cdn.jsdelivr.net/gh/PuneetGopinath/switch-theme-js@v1-dev/src/index.min.js"></script>` in the head tag.
6. Set a default theme by adding `data-theme` attribute to `html` tag, with your default theme name as value
7. That's all, test it out in your website, or submit a bug report for us to Analyse the bug.

## Contributing
You can find the contributing guidelines [here](https://github.com/PuneetGopinath/switch-theme-js/blob/main/.github/CONTRIBUTING.md)

## Changelog
See [CHANGELOG.md](https://github.com/PuneetGopinath/switch-theme-js/blob/main/CHANGELOG.md)

## Supporters
👏 A big thank you goes to all the supporters of this project!

You prove that the switch-theme-js Action has some value for you!

### Stargazers
[![Stargazers for @PuneetGopinath/switch-theme-js](https://reporoster.com/stars/PuneetGopinath/switch-theme-js)](https://github.com/PuneetGopinath/switch-theme-js/stargazers)
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FPuneetGopinath%2Fswitch-theme-js.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2FPuneetGopinath%2Fswitch-theme-js?ref=badge_shield)

### Contributors
Thanks to all contributors again!

[![GitHub Contributors Image](https://contrib.rocks/image?repo=PuneetGopinath/switch-theme-js)](https://github.com/PuneetGopinath/switch-theme-js/contributors)


## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FPuneetGopinath%2Fswitch-theme-js.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2FPuneetGopinath%2Fswitch-theme-js?ref=badge_large)