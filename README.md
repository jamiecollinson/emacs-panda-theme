<p align="center"><img src="https://raw.githubusercontent.com/PandaTheme/Panda-Kit/master/Kit/Panda.jpg" width="200px"/></p>

<p align="center">A superminimal, dark syntax theme for <a href="https://www.gnu.org/software/emacs">Emacs</a>.</p>

<p align="center">Based on the <a href="http://panda.siamak.work">Panda</a> color palette.</p>

---

## Installation

### Manual

[Download](https://github.com/jamiecollinson/emacs-panda-theme/releases/latest/) the latest version or clone the repository and copy the [`panda-theme.el`](https://github.com/jamiecollinson/emacs-panda-theme/blob/master/panda-theme.el) theme file to your `~/.emacs.d/themes` directory.

#### Activation
Make sure that the `themes` directory has been added to the load path:
```lisp
(add-to-list 'custom-theme-load-path (expand-file-name "~/.emacs.d/themes/"))
```

Use Panda as your default theme by adding it to your `.init.el`
```lisp
(load-theme 'panda t)
```
or change it on-the-fly by running <kbd>M-x</kbd> `load-theme` <kbd>RET</kbd> `panda` <kbd>RET</kbd>.

### Package.el

Coming soon.

## Screenshots

![Screenshot](img/screenshot-elisp.png)
