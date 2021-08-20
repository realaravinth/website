<div align="center">
  <img alt="WiOS logo" src="./static/logo-100x100.png" />
  <h1>Women in Open Source website</h1>

[![Build](https://github.com/wiosc/website/actions/workflows/main.yml/badge.svg)](https://github.com/wiosc/website/actions/workflows/main.yml)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg?style=flat-square)](http://www.gnu.org/licenses/agpl-3.0)

</div>

## Development environment

This website uses [Zola](https://www.getzola.org/), an easy to use static site generator.

To get started:

1. [Install Zola](https://www.getzola.org/documentation/getting-started/installation/)

2. Live reload

```bash
zola serve
```
3. Make changes and publish

```bash
zola build
```

Build artifacts should be available in `./public/`


## Deployment

This repository uses GitHub Actions to automatically build and deploy
upon each commit.
