# Font Awesome SCSS packaged as a Hugo Module

This is a [Hugo module](https://gohugo.io/hugo-modules/) that packages the [Font Awesome](https://github.com/FortAwesome/Font-Awesome) SCSS source ready to be used in Hugo.

You need the [Hugo](https://github.com/gohugoio/hugo/releases) extended version and [Go](https://golang.org/dl/) to use this component.

## Use

Add the component to your Hugo site's config:

```toml
[module]
[[module.imports]]
path = "github.com/deining/hugo-mod-font-awesome-scss"
```

The Font Awesome SCSS will be mounted in `assets/scss/Font-Awesome`, so you can then import either all:

```scss
@import "Font-Awesome/fontawesome";
```

Or only what you need:

```scss
@import "Font-Awesome/variables";
@import "Font-Awesome/mixins";
@import "Font-Awesome/core";
@import "Font-Awesome/larger";
@import "Font-Awesome/fixed-width";
@import "Font-Awesome/list";
@import "Font-Awesome/bordered-pulled";
@import "Font-Awesome/animated";
@import "Font-Awesome/rotated-flipped";
@import "Font-Awesome/stacked";
@import "Font-Awesome/icons";
@import "Font-Awesome/screen-reader";
@import "Font-Awesome/shims.scss";
```

## Versions

This repository will be versioned following the minor and patch versions in the Font Awesome repository.
