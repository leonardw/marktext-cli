# MarkText CLI

Commandline for the MarkText markdown editor.

## Prerequisite

A working installation of [MarkText](https://github.com/Tkaixiang/marktext) must exist on the system.

> Currently only macOS is supported. Support for other \*nix systems may come at some point in the future.

## Installation

Download latest [`marktext`](marktext) file and copy it into /usr/local/bin/ directory.

```sh
% cp marktext /usr/local/bin/
% chmod +x /usr/local/bin/marktext
```

## CLI Usage

Open a markdown file with MarkText

```sh
% marktext README.md

```

This opens the `README.md` markdown file in the MarkText app in a new window or, if one is already open, as a new tab.

Multiple files may be opened simultaneously, as tabs, by specifying more than one filenames

```sh
% marktext Installation.md License.md README.md
```

## License

[MIT License](LICENSE)

Copyright (c) 2025 Leonard Wu <leonard.wu92@alumni.ic.ac.uk>
