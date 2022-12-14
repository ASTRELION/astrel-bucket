# astrel-bucket

[![Tests](https://github.com/ASTRELION/astrel-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/ASTRELION/astrel-bucket/actions/workflows/ci.yml)
[![Excavator](https://github.com/ASTRELION/astrel-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/ASTRELION/astrel-bucket/actions/workflows/excavator.yml)

A Scoop bucket for software not found elsewhere.

Based on the template bucket for [Scoop](https://scoop.sh), the Windows command-line installer.

# Manifests

- [mullvad-vpn](./bucket/mullvad-vpn.json)

# How do I install these [manifests](#manifests)?

## Add the bucket

```
scoop bucket add astrel-bucket https://github.com/ASTRELION/astrel-bucket
```

## Install a manifest

```
scoop install <manifest-name>
```

# How do I contribute new manifests?

To make a new manifest contribution, please read the [Contributing Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md).
