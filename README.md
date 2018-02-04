<p align="center"><img src="https://raw.githubusercontent.com/PandaTheme/Panda-Kit/master/Kit/Panda.jpg" width="200px"/></p>

<p align="center">A superminimal, dark syntax theme for <a href="https://www.gnu.org/software/emacs">Emacs</a>.</p>

<p align="center">Based on the <a href="http://panda.siamak.work">Panda</a> color palette.</p>

<p align="center">
  <a href="https://melpa.org/#/panda-theme">
    <img alt="MELPA" src="https://melpa.org/packages/panda-theme-badge.svg"/>
  </a>
</p>

## Installation

### Automatically with `use-package`

If you're using `use-package` add this snippet (taken from my personal [config](https://github.com/jamiecollinson/dotfiles/blob/master/config.org#appearance)) to your `init.el` and panda theme will be installed and enabled.

``` emacs-lisp
(use-package panda-theme
  :ensure t
  :config
  (load-theme 'panda t))
```

### Automatically using `package.el`

<kbd>M-x</kbd> `package-refresh-contents` then <kbd>M-x</kbd> `package-install` and choose `panda-theme`.
  
You'll now need to enable the theme, see instructions below.

### Manually using `package.el`

[Download](https://github.com/jamiecollinson/emacs-panda-theme/releases/latest/) the latest version or clone the repository to your location of choice, e.g.

``` bash
git clone https://github.com/jamiecollinson/emacs-panda-theme.git
```

To install into Emacs use <kbd>M-x</kbd> `package-install-file` and select `panda-theme.el` from the download / clone location.

You'll now need to enable the theme, see instructions below.

## Enabling the theme

To enable the theme either <kbd>M-x</kbd> `load-theme` then select `panda`, or add the following to your `init.el`:

``` emacs-lisp
(load-theme 'panda t)
```

To disable the theme <kbd>M-x</kbd> `disable-theme` then select `panda`.

## Screenshots

![Screenshot](img/screenshot-elisp.png)
