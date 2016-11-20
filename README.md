# paganini :violin:
Dark Emacs Theme

[![MELPA](http://melpa.org/packages/paganini-theme-badge.svg)](http://melpa.org/#/paganini-theme)
[![License MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## Installation

### Manual

Download `paganini-theme.el` to the directory `~/.emacs.d/themes/`. Add this to your
`.emacs`:

```lisp
(add-to-list 'custom-theme-load-path "~/.emacs.d/themes/")
```

Now you can load the theme with the interactive function `load-theme` like this:

`M-x load-theme RET paganini`

### Package.el

Paganini is available in [MELPA](http://melpa.org).

You can install `paganini` with the following command:

`M-x package-install paganini-theme`

To load it automatically on Emacs startup add this to your init file:

```lisp
(load-theme 'paganini t)
```
## Screenshots
![](https://github.com/onurtemizkan/paganini/raw/master/screenshots/s1.png)
![](https://github.com/onurtemizkan/paganini/raw/master/screenshots/s2.png)
