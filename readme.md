<h1 align="center">VirtISO<br />
<div align="center">
<a href="https://github.com/qemus/virtiso"><img src="https://github.com/qemus/virtiso/raw/master/.github/logo.png" title="Logo" style="max-width:100%;" width="128" /></a>
</div>
<div align="center">
  
  [![Build](https://github.com/qemus/virtiso/actions/workflows/build.yml/badge.svg)](https://github.com/qemus/virtiso/)
  [![Version](https://img.shields.io/github/v/tag/qemus/virtiso?label=version&sort=semver&color=066da5)](https://github.com/qemus/virtiso/releases)
  [![Size](https://img.shields.io/badge/size-25.6_MB-steelblue?style=flat&color=066da5)](https://github.com/qemus/virtiso/releases)
  
</div></h1>

VirtISO is a slim image of the KVM/QEMU VirtIO drivers for 64-bit Windows guests.

It minimizes the [official ISO](https://fedorapeople.org/groups/virt/virtio-win/direct-downloads/latest-virtio/) from 700 MB to just 25 MB in size.

# Methods used

  - Stripped ARM64/i386/x86 drivers
  - Stripped all .PDB (debug symbol) files
  - Stripped Guest Agent and Guest Tools

# Usage
  
  It contains every AMD64 driver the official image has, and even the .MSI installer, so there is zero loss of functionality.

  See also [VirtISO x86](https://github.com/qemus/virtiso-x86/) if you need x86 drivers and [VirtISO ARM](https://github.com/qemus/virtiso-arm/) for ARM64 drivers.

# Stars
[![Stars](https://starchart.cc/qemus/virtiso.svg?variant=adaptive)](https://starchart.cc/qemus/virtiso)

# Disclaimer

  This project contains binaries provided by Red Hat, Inc. and/or its affiliates.
