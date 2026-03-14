[![add-on registry](https://img.shields.io/badge/DDEV-Add--on_Registry-blue)](https://addons.ddev.com)
[![tests](https://github.com/ronan/ddev-invrt/actions/workflows/tests.yml/badge.svg?branch=main)](https://github.com/ronan/ddev-invrt/actions/workflows/tests.yml?query=branch%3Amain)
[![last commit](https://img.shields.io/github/last-commit/ronan/ddev-invrt)](https://github.com/ronan/ddev-invrt/commits)
[![release](https://img.shields.io/github/v/release/ronan/ddev-invrt)](https://github.com/ronan/ddev-invrt/releases/latest)

# DDEV Invrt

## Overview

This add-on integrates Invrt into your [DDEV](https://ddev.com/) project.

## Installation

```bash
ddev add-on get ronan/ddev-invrt
ddev restart
```

After installation, make sure to commit the `.ddev` directory to version control.

## Usage

| Command | Description |
| ------- | ----------- |
| `ddev describe` | View service status and used ports for Invrt |
| `ddev logs -s invrt` | Check Invrt logs |

## Advanced Customization

To change the Docker image:

```bash
ddev dotenv set .ddev/.env.invrt --invrt-docker-image="ddev/ddev-utilities:latest"
ddev add-on get ronan/ddev-invrt
ddev restart
```

Make sure to commit the `.ddev/.env.invrt` file to version control.

All customization options (use with caution):

| Variable | Flag | Default |
| -------- | ---- | ------- |
| `INVRT_DOCKER_IMAGE` | `--invrt-docker-image` | `ddev/ddev-utilities:latest` |

## Credits

**Contributed and maintained by [@ronan](https://github.com/ronan)**
