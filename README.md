# Erratum

A [Hugo](https://gohugo.io) theme forked from [Typo](https://github.com/tomfran/typo) with mostly upstream compatible modifications made for my [personal website](https://markopejic.com).

## Changes

> :information_source: More changes will drop as I keep working on my website.

### Breaking

- Removed support for installing this theme as a Hugo module

### Other

- Added the ```params.favicons``` option to toggle favicon support
- Changed the font family to Inter everywhere except in code elements
- Added a Hugo shortcode ```{{< link "url" "name" >}}``` for an anchor tag that opens a link in a new tab
- Added an ```email``` svg icon
- Removed the prefix of forward slashes on header links
- Redesigned footer

## Setup

> :warning: If you don't already have a basic Hugo website, follow [Hugo's quick start guide](https://gohugo.io/getting-started/quick-start/) first.

To setup Erratum in your Hugo website, simply add this repo to your Hugo project as a git submodule:

```bash
git submodule add --depth=1 https://github.com/markop404/erratum.git themes/erratum
git submodule update --init --recursive
```

and change the theme in your Hugo configuration to ```erratum```. 

## Documentation

Since Erratum is mostly compatible with Typo, [Typo's wiki](https://tomfran.github.io/typo-wiki) contains relevant documentation.
