#### ⚠️ Do not download modules from 3rd party sources like random websites you found on Google. There are many that uses my modules and impersonates ReVanced.

# ReVanced Magisk Module
[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/rvc_magisk)
[![CI](https://github.com/j-hc/revanced-magisk-module/actions/workflows/ci.yml/badge.svg?event=schedule)](https://github.com/j-hc/revanced-magisk-module/actions/workflows/ci.yml)

Extensive ReVanced builder  

Get the [latest CI release](https://github.com/j-hc/revanced-magisk-module/releases).

Use [**zygisk-detach**](https://github.com/j-hc/zygisk-detach) to detach YouTube and YT Music from Play Store if you are using magisk modules. 

## Features
 * Support all present and future ReVanced and [ReVanced Extended](https://github.com/inotia00/revanced-patches) apps
 * Can build Magisk modules and non-root APKs
 * Updated daily with the latest versions of apps and patches
 * Optimize APKs and modules for size
 * Modules
     * recompile invalidated odex for faster usage
     * receive updates from Magisk app
     * do not break safetynet or trigger root detections
     * handle installation of the correct version of the stock app and all that
     * support Magisk and KernelSU

#### **Note that the [CI workflow](../../actions/workflows/ci.yml) is scheduled to build the modules and APKs everyday using GitHub Actions if there is a change in ReVanced patches. You may want to disable it.**

## To include/exclude patches or patch more ReVanced Apps
[**See the list of patches**](https://j-hc.github.io/rvmm-config-gen/)

 * Star the repo :eyes:
 * [Fork the repo](https://github.com/j-hc/revanced-magisk-module/fork) or use it as a template
 * Customize [`config.toml`](./config.toml) using [rvmm-config-gen](https://j-hc.github.io/rvmm-config-gen/)
 * Run the build [workflow](../../actions/workflows/build.yml)
 * Grab your modules and APKs from [releases](../../releases)

also see here [`CONFIG.md`](./CONFIG.md)

# Building Locally
## On Termux
```console
bash <(curl -sSf https://raw.githubusercontent.com/j-hc/revanced-magisk-module/main/build-termux.sh)
```

## On Desktop
```console
$ git clone https://github.com/j-hc/revanced-magisk-module
$ cd revanced-magisk-module
$ ./build.sh
```
