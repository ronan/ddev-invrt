[![add-on registry](https://img.shields.io/badge/DDEV-Add--on_Registry-blue)](https://addons.ddev.com)
[![tests](https://github.com/ronan/ddev-invrt/actions/workflows/tests.yml/badge.svg?branch=main)](https://github.com/ronan/ddev-invrt/actions/workflows/tests.yml?query=branch%3Amain)
[![last commit](https://img.shields.io/github/last-commit/ronan/ddev-invrt)](https://github.com/ronan/ddev-invrt/commits)
[![release](https://img.shields.io/github/v/release/ronan/ddev-invrt)](https://github.com/ronan/ddev-invrt/releases/latest)

# DDEV Invrt

## Overview

This add-on integrates [Invrt](https://github.com/ronan/invrt) into your [DDEV](https://ddev.com/) project.

## Installation

```bash
ddev add-on get ronan/ddev-invrt
ddev restart
```

After installation, make sure to commit the `.ddev` directory to version control.

## Usage

| Command | Description |
| ------- | ----------- |
| `ddev invrt test` | Run a Visual Regression test on the site |
| `ddev logs -s invrt` | Check Invrt logs |


## Credits

**Contributed and maintained by [@ronan](https://github.com/ronan)**
**Based on Backstop.js by [@garris](https://github.com/garris/backstopjs)**
