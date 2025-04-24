# odiff-py

<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->

[![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square)](#contributors-)

<!-- ALL-CONTRIBUTORS-BADGE:END -->

[![PyPi Version](https://img.shields.io/pypi/v/odiff_py.svg)](https://pypi.org/project/odiff-py/)
[![Supported Python Versions](https://img.shields.io/pypi/pyversions/odiff_py.svg)](https://pypi.org/project/odiff-py/)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

[![Actions Status](https://github.com/s-weigand/odiff-py/workflows/Tests/badge.svg)](https://github.com/s-weigand/odiff-py/actions)
[![Documentation Status](https://readthedocs.org/projects/odiff-py/badge/?version=latest)](https://odiff-py.readthedocs.io/en/latest/?badge=latest)
[![codecov](https://codecov.io/gh/s-weigand/odiff-py/branch/main/graph/badge.svg)](https://codecov.io/gh/s-weigand/odiff-py)
[![Documentation Coverage](https://raw.githubusercontent.com/s-weigand/odiff-py/main/docs/_static/interrogate_badge.svg)](https://github.com/s-weigand/odiff-py)

[![All Contributors](https://img.shields.io/github/all-contributors/s-weigand/odiff-py)](#contributors)

[![Ruff](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/ruff/main/assets/badge/v2.json)](https://github.com/astral-sh/ruff)

Use [`odiff`](https://github.com/dmtrKovalenko/odiff) from python without the file dump and `subprocess` hassle.

<details open="true">
  <summary>Animated image diff</summary>

![animated diff](https://github.com/s-weigand/odiff-py/raw/refs/heads/main/tests/data/tiger-compare.apng)

</details>

## Installation

### Generic installation

No matter your dependency and environment management system you can install `odiff-py` using
[`pip`](https://pip.pypa.io/en/stable/getting-started/) with:

```console
pip install odiff-py
```

### Generic installation using `uv`

For a quicker installation into any python environment you can use [`uv`](https://docs.astral.sh/uv/) and the following command:

```console
uv pip install odiff-py
```

### Add to project with `uv`

You most likely want to use `odiff-py` in visual regression testing and thus add it to your project.
If you are `uv` this is easily done using.

```console
uv add odiff-py
```

> [!NOTE]
> Only add it as optional dependency using the `--optional` CLI option (e.g. `uv add odiff-py --optional test`)
> or as `uv` development dependency with the `--dev` flag (`uv add odiff-py --dev`)

## Features

- Pythonic API for Image comparison using `odiff`
- Pillow images as input and result in result
- Support for all `odiff` options
- First class notebook support
- Support for ignore areas including optional overlay in result images
- [APN](https://en.wikipedia.org/wiki/APNG) generation for result (`base` -> `compare` -> `diff` cycle)

## Road Map

Future planned features are:

- Remote image usage (http links)
- `pytest` plugin
- `behave` plugin

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/s-weigand"><img src="https://avatars.githubusercontent.com/u/9513634?v=4?s=100" width="100px;" alt="Sebastian Weigand"/><br /><sub><b>Sebastian Weigand</b></sub></a><br /><a href="https://github.com/s-weigand/odiff-py/commits?author=s-weigand" title="Code">💻</a> <a href="#ideas-s-weigand" title="Ideas, Planning, & Feedback">🤔</a> <a href="#maintenance-s-weigand" title="Maintenance">🚧</a> <a href="#projectManagement-s-weigand" title="Project Management">📆</a> <a href="#infra-s-weigand" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a> <a href="https://github.com/s-weigand/odiff-py/commits?author=s-weigand" title="Tests">⚠️</a> <a href="https://github.com/s-weigand/odiff-py/commits?author=s-weigand" title="Documentation">📖</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!
