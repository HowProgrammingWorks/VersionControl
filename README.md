# Version Control

| [English](README.md) | [Russian](README.ru.md) |

This repo aggregates useful links, tutorials and infographics for those
learning to use Git so that they'll be able to develop their own projects with
confidence, work on collaborative projects with their friends/classmates or
contribute to existing open-source software.

Repository maintainers:

 * Alexey Orlenko ([@aqrln](https://github.com/aqrln))
   &lt;eaglexrlnk@gmail.com&gt;
 * Timur Shemsedinov ([@tshemsedinov](https://github.com/tshemsedinov))
   &lt;timur.shemsedinov@gmail.com&gt;

If you feel like something is missing or unclear there, feel free to [open an
issue](https://github.com/HowProgrammingWorks/VersionControl/issues/new) or
submit a pull request with your suggestions, but if you don't know how to do it
yet and you need any assistance with the very basics, don't hesitate to contact
us via the emails above ;)

## Install Git

### Common links

* Git official site: <https://git-scm.com>
* Desktop GUI clients (optional and only for those who absolutely cannot live
  without them; we recommend you to get comfortable with the CLI shell):
   - most IDEs (including but not limited to WebStorm, PyCharm and other
     JetBrains products, Xcode, Visual Studio) include their own Git tools
     and using them is far more appropriate that installing a separate
     GUI client if you use an IDE;
   - [GitHub Desktop](https://desktop.github.com/) (easy to use but very
     limited in functionality)
   - [Tortoise Git](https://tortoisegit.org/)
   - More examples: <https://git-scm.com/downloads/guis>

### Windows

If you only want Git itself, download the installer at
<https://git-scm.com/download/win>.  Alternatively, if you'd prefer to use
[GitHub's desktop client](https://windows.github.com), keep in mind that it
includes a bundled version of Git, so you don't need it installed separately.

### macOS

The easiest way to install Git on macOS is to install the Xcode Command Line Tools.
Your system will automatically prompt you to do so the first time you try to
run Git, so there's actually nothing special you should do.

Alternatively, if you want a newer version, you can install it from the
official package at <https://git-scm.com/download/mac> or using
the [Homebrew](https://brew.sh) package manager via `$ brew install git`.

### Linux

Use your distro's package manager to install the corresponding package.
Examples:

* Debian-based systems (including Ubuntu with its flavors and Linux Mint):
  `$ sudo apt-get install git-all`
* Fedora: `$ sudo dnf install git`
* Arch: `$ sudo pacman -S git`
