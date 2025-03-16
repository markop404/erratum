# typo-marko

This is a fork of the [Typo](https://github.com/tomfran/typo) ([Hugo](https://gohugo.io)) theme, optimized for the needs of my personal website on [markopejic.com](https://markopejic.com). However, it does aim to be compatible (for the most part) with the upstream theme. Changes from upstream are listed below. If you end up liking them, feel free to use this theme for your own website.

## Changes

:information_source: More changes will drop as I keep working on my website.

### Breaking

- Removed support for installing this theme as a Hugo module

### Other

- Added params.favicons option to toggle favicon support
- Changed the font family to Inter everywhere except in code elements
- Added a Hugo shortcode for an anchor tag that opens a link in a new tab (``` {{< link "url" "name" >}} ```)
- Added an email svg icon
- Removed the prefix of forward slashes on header links

## Setup

To setup your Hugo website to use this theme, simply add this repo to your Hugo project as a git submodule:

```bash
git submodule add --depth=1 https://github.com/markop404/typo-marko.git themes/typo-marko
git submodule update --init --recursive
```

and change the theme in your Hugo configuration to 'typo-marko'. 

## Configuration

The documentation of all theme features that are not listed above as broken is available in the [upstream wiki](https://tomfran.github.io/typo-wiki).
