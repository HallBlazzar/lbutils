# lbutils

**lbutils** is a library for helping you build customized Debian images.

Full online document - https://hallblazzar.github.io/lbutils/source/index.html

**lbutils** is a Python wrapper of [Debian Live Build](https://live-team.pages.debian.net/live-manual/html/live-manual/index.en.html). It provides a set of declarative targets to define customization options supported by `Live Build`. Including:
- Aptitude packages
- Importing static files
- Customized `.deb` pacckages
- Hook scripts
- Bootloaders

Additionally, **lbutils** provides extensions to help you quickly define common targets like AppImages and GRUB to help you simplify configuration work.

No matter you're not familiar with `Live Build`, the [document](https://hallblazzar.github.io/lbutils/source/index.html) is a great start for helping you understand the tool and **lbutils**.

Feel free to submit PR and file issues if needed :)
