PHP extension for expect library
================================

This extension allows to interact with processes through PTY, using expect library.

This extension uses a Tcl/Expect library: https://www.tcl-lang.org/.

Original author: Michael Spector

> **Unable to build this extension for Windows because the TCL Expect is not available on Windows.**


Maintained branches:

| Version | Status                       |
|---------|------------------------------|
| master  | unmaintened :x:              |
| v0.x    | maintened :white_check_mark: |

Maintained PHP Versions compatibility:

| PHP Version | Status                 |
|-------------|------------------------|
| 5.x         | no :x:                 |
| 7.x         | no :x:                 |
| 8.0         | yes :white_check_mark: |
| 8.1         | yes :white_check_mark: |
| 8.2         | yes :white_check_mark: |
| 8.3         | yes :white_check_mark: |
| 8.4         | yes :white_check_mark: |
| 8.5         | yes :white_check_mark: |

Installation system support:

| Platform | Status                 |
|----------|------------------------|
| PECL     | no  :x:                |
| PIE      | yes :white_check_mark: |


To install the extension, install the library `tcl-dev tcl-expect-dev` first.

Debian/Ubuntu/Mint:

```shell
sudo apt-get install tcl-dev tcl-expect-dev
```

Alpine Linux:

```shell
apk add tcl-dev expect-dev
```

Fedora:

```shell
sudo dnf install tcl-devel expect-devel
```

Arch Linux:

```shell
sudo pacman -S tcl expect
```

And use PIE (PHP Installer Extension) with a command like:

```bash
pie install php-win-ext/expect
```
