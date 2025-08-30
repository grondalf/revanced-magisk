# ReVanced Magisk Module
[![CI](https://github.com/j-hc/revanced-magisk-module/actions/workflows/ci.yml/badge.svg?event=schedule)](https://github.com/j-hc/revanced-magisk-module/actions/workflows/ci.yml)

Extensive ReVanced builder originally made by [**j-hc**](https://github.com/j-hc/revanced-magisk-module). Use [zygisk-detach](https://github.com/j-hc/zygisk-detach) to detach apps from the Play Store if you are using magisk modules. 

## Features
 * Supports current [ReVanced](https://github.com/ReVanced/revanced-patches) and [ReVanced Extended](https://github.com/inotia00/revanced-patches) patches.
 * Automatically builds optimized modules and `apk` files on a daily basis.

## To include/exclude patches or patch other apps

 * Use the repo as a [template](https://github.com/new?template_name=revanced-magisk-module&template_owner=j-hc)
 * Customize [`config.toml`](./config.toml) using [rvmm-config-gen](https://j-hc.github.io/rvmm-config-gen/)
 * Run the build [workflow](../../actions/workflows/build.yml)
 * Grab your modules and APKs from [releases](../../releases)

also see here [`CONFIG.md`](./CONFIG.md)

## Building Locally
### On Termux
```console
bash <(curl -sSf https://raw.githubusercontent.com/grondalf/revanced-magisk/main/build-termux.sh)
```

### On Desktop
```console
$ git clone https://github.com/grondalf/revanced-magisk-module
$ cd revanced-magisk
$ ./build.sh
```
