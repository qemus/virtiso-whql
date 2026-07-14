<h1 align="center">VirtISO WHQL<br />
<div align="center">
<a href="https://github.com/qemus/virtiso-whql"><img src="https://github.com/qemus/virtiso-whql/raw/master/.github/logo.png" title="Logo" style="max-width:100%;" width="128" /></a>
</div>
<div align="center">
  
  [![Build](https://github.com/qemus/virtiso-whql/actions/workflows/build.yml/badge.svg)](https://github.com/qemus/virtiso-whql/)
  [![Version](https://img.shields.io/github/v/release/qemus/virtiso-whql?label=version&sort=semver&display_name=release&color=066da5)](https://github.com/qemus/virtiso-whql/releases)
  [![Size](https://img.shields.io/badge/size-56_MB-steelblue?style=flat&color=066da5)](https://github.com/qemus/virtiso-whql/releases)
  
</div></h1>

VirtISO is an image of the WHQL certified VirtIO drivers for Windows guests as provided by Redhat.

## Features ✨

- Provides a slim VirtIO WHQL drivers ISO for Windows guests
- Based on the Red Hat VirtIO driver image
- Reduces the official ISO from about 700 MB to about 50 MB
- Includes only 64-bit Windows drivers
- Removes x86, i386, and ARM64 drivers
- Removes debug symbol files
- Removes Guest Agent and Guest Tools

# Download

  You can download the [latest version](https://github.com/qemus/virtiso-whql/releases/download/v1.9.58-0/virtio-win-1.9.58.iso) from the [Releases](https://github.com/qemus/virtiso-whql/releases) page.
  
# Usage 🚀
  
  It contains every driver the official image has, and even the .MSI installer, so there is zero loss of functionality.

> [!TIP]
> See also [VirtISO](https://github.com/qemus/virtiso/) for a minimal image of the unsigned drivers as provided by Fedora.

## Stars 🌟
[![Stargazers](https://raw.githubusercontent.com/star-stats/stars/refs/heads/data/charts/qemus-virtiso-whql.svg)](https://github.com/qemus/virtiso-whql/stargazers)

# Disclaimer ⚖️

  *This project contains binaries provided by Red Hat, Inc. and/or its affiliates.*
