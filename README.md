<div align="center">
  <img src="https://raw.githubusercontent.com/FajarKim/pycx/master/image/logo.svg" alt="PYCX Logo" width="140"/>
  <h1>PYCX</h1>
  <p><a href="https://github.com/FajarKim/pycx/blob/master/README-ID.md">Indonesia</a></p>
  <p><a href="https://github.com/FajarKim/pycx/issues/new?assignees=&labels=bug&projects=&template=bug_report.yml">Report Bug</a> · <a href="https://github.com/FajarKim/pycx/issues/new?assignees=&labels=enhancement&projects=&template=feature_request.yml">Request Feature</a></p>
  <p>
    <a href="https://pypi.org/project/pycx"><img src="https://img.shields.io/pypi/v/pycx?label=PyPI&labelColor=302d41&color=8aadf4&logoColor=d9e0ee&logo=pypi&style=for-the-badge" alt="PyPI Version"/></a>
    <a href="https://github.com/FajarKim/pycx/stargazers/"><img src="https://custom-icon-badges.demolab.com/github/stars/FajarKim/pycx?label=Stars&logo=star&labelColor=302d41&color=c9cbff&logoColor=d9e0ee&style=for-the-badge" alt="Stars"></a>
    <a href="https://github.com/FajarKim/pycx/network/members/"><img src="https://custom-icon-badges.demolab.com/github/forks/FajarKim/pycx?label=Forks&logo=fork&labelColor=302d41&color=b5e8e0&logoColor=d9e0ee&style=for-the-badge" alt="Forks"/></a>
    <a href="https://github.com/FajarKim/pycx/issues"><img src="https://custom-icon-badges.demolab.com/github/issues/FajarKim/pycx?label=Issues&labelColor=302d41&color=f5a97f&logoColor=d9e0ee&logo=issue&style=for-the-badge" alt="Issues"/></a>
    <a href="https://github.com/FajarKim/pycx/archive/refs/heads/master.zip"><img src="https://custom-icon-badges.demolab.com/github/languages/code-size/FajarKim/pycx?label=Download&logo=download&labelColor=302d41&color=b7bdf8&logoColor=d9e0ee&style=for-the-badge" alt="Download Size"/></a>
  </p>
</div>

## Table of Content

1. [Introduction](#introduction)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [License](#license)
6. [Donate](#donate)
7. [Changelog](#changelog)

## Introduction

PYCX is a Python 3 code compiler that utilizes Cython for performance enhancements. It provides a straightforward way to compile Python 3.8 and above code, aiming to improve execution speed and efficiency, especially for legacy Python code optimization.

## Features

- **Python >=3.8 Support:** Specifically designed for compiling Python 3.8 and above code.
- **Cython Integration:** Utilizes Cython to generate C extensions for enhanced performance.
- **Command-Line Interface:** Easy-to-use CLI for compiling Python 2 code.

## Installation

You can install `pycx` using `pip`:

```bash
pip install pycx
```

## Usage

Basic usage with command CLI:

```bash
pycx source_file.py
```

Using import module:

```python
from pycx import compile as compile_

compile_.compile("source_file.py" #, True/False for enable verbose mode)
```

## License

PYCX is released under the AGPL-3.0 license, which grants the following permissions:
- Commercial use
- Modification
- Distribution
- Patent use
- Private use

For more convoluted language, see the [LICENSE](https://github.com/FajarKim/pycx/blob/main/LICENSE).

## Donate

Love the project? Please consider donating to help it improve!

[![GitHub](https://img.shields.io/badge/GitHub-Sponsor-blue?labelColor=302d41&color=f5bde6&logo=github&logoColor=d9e0ee&style=for-the-badge)](https://github.com/sponsors/FajarKim/)
[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-Donate-blue?labelColor=302d41&color=eed49f&logo=buymeacoffee&logoColor=d9e0ee&style=for-the-badge)](https://buymeacoffee.com/fajarkim/)
[![Trakteer](https://custom-icon-badges.demolab.com/badge/Trakteer-Donate-blue?labelColor=302d41&color=ed8796&logo=trakteerid&logoColor=d9e0ee&style=for-the-badge)](https://trakteer.id/fajarkim/)

## Changelog

Stay updated on the latest changes and updates to PYCX by referring to the [Changelog](https://github.com/FajarKim/pycx/releases).

Thank you for choosing PYCX! We aim to provide a secure and reliable solution for encrypting source file Python.

<div align="center">
  <img src="https://raw.githubusercontent.com/FajarKim/FajarKim/master/images/line.svg?sanitize=true"/>
</div>

<p align="center">Made with ❤️ and Python</p>
<p align="center">Copyright © 2024 Rangga Fajar Oktariansyah</p>
<div align="center">
  <a href="https://github.com/FajarKim/pycx/blob/main/LICENSE"><img src="https://custom-icon-badges.demolab.com/github/license/FajarKim/pycx?label=License&labelColor=302d41&color=91d7e3&logo=law&logoColor=d9e0ee&style=for-the-badge" alt="License"></a>
</div>
