# typo-marko

This is a fork of the [Typo](https://github.com/tomfran/typo) theme for [Hugo](https://gohugo.io). It's optimized for the needs of my personal website on [markopejic.com](https://markopejic.com). However, everything except the small list of changes listed below is the same as the upstream theme, so if you end up liking the changes made in this fork, feel free to use it for your own website.

## Changes

#### Breaking
- Removed support for favicons
- Removed support for installing this theme as a Hugo module

#### Other

- Changed the font family to Inter everywhere except in code elements
- Added a Hugo shortcode for an anchor tag that opens a link in a new tab (``` {{< link "url" "name" >}} ```)
- Added an email svg icon
- Removed the prefix of forward slashes on header links

## Getting Started

To get started with this theme, simply add this repo to your Hugo project as a git submodule:
```bash
git submodule add --depth=1 https://github.com/markop404/typo-marko.git themes/typo-marko
git submodule update --init --recursive
```
and change the theme in your Hugo configuration to 'typo-marko'. The documentation of all the configuration options that are not listed above as broken is available in the [upstream wiki](https://tomfran.github.io/typo-wiki).