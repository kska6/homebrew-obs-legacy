# homebrew-obs-legacy

> [!CAUTION]
> This repository was archived on 2024-12-10, because the issue was resolved by [OBS Studio 31.0.0](https://github.com/obsproject/obs-studio/releases/tag/31.0.0).

## Repository Description

This repository is a Homebrew tap that provides a previous version of OBS Studio (29.0.2) for macOS users. It allows users to install and manage this legacy version using Homebrew Cask, offering a stable and compatible option for those who experience issues with the latest releases, particularly with Virtual Camera functionality.

## Why Use This Tap?

macOS 15 introduced a known issue with OBS Studio's Virtual Camera, which may not work correctly on certain systems. Until this issue is resolved, this tap provides an option to install version 29.0.2 of OBS Studio, which may offer a more stable experience with Virtual Camera on affected macOS versions. For more details on this issue, see the [OBS Forum discussion](https://obsproject.com/forum/threads/virtual-camera-with-macos-15.180629/).

## How to Install

With the following command, you can add this repository to Homebrew and install past versions of OBS.

```zsh
brew tap kska6/obs-legacy
brew install kska6/obs-legacy/obs@29
```
