# Darkpage #

[version_shield]: https://img.shields.io/badge/version-N%2FA-blue.svg
[latest_release]: https://github.com/mfederczuk/darkpage/releases/latest "Latest Release"
[![version: N/A][version_shield]][latest_release]
[![Changelog](https://img.shields.io/badge/-Changelog-blue.svg)](./CHANGELOG.md "Changelog")

## About ##

**Darkpage** is a dark themed **CSS** stylesheet that is easy to include and use.

## Adding The Stylesheet ##

The latest version of the stylesheet is available on my **GitHub Pages** site
 under the url `https://mfederczuk.github.io/darkpage/v1.min.css`.

You can either import it in your existing **CSS** file or link it in your
 **HTML** file.

```css
@import url("https://mfederczuk.github.io/darkpage/v1.min.css");
```

```html
<link rel="stylesheet" type="text/css" href="https://mfederczuk.github.io/darkpage/v1.min.css">
```

You can also download it using `wget` or from the
 [releases](https://github.com/mfederczuk/darkpage/releases) and import or link
 it locally.

```sh
wget -O 'darkpage.min.css' 'https://mfederczuk.github.io/darkpage/v1.min.css'
```

```css
@import url("./darkpage.min.css");
```

```html
<link rel="stylesheet" type="text/css" href="./darkpage.min.css">
```

## Usage ##

All elements and their children with the class `darkpage` will be targeted by
 the stylesheet.  
To style the entire page, just add the class to your `body` element.  
If you also want to have the scrollbar be styled you need to add the class to
 the `html` element.

Inline monospace (the `code` element) will not have a background by default.  
Add the `code-bg` class to a parent of the `code` element, or to the element
 itself, and a background will be added to it.

## Contributing ##

Read through the [Darkpage Contribution Guidelines](./CONTRIBUTING.md)
 if you want to contribute to this project.

## License ##

[GNU GPLv3+](./LICENSE)
