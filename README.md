# Magick-OS

## Setup

Build image for docker env:

- `docker build buildenv -t magickos-buildenv`

## Build

- Linux or MacOS: `docker run --rm -it -v "$pwd":/root/env magickos-buildenv`
- Windows (cmd): `docker run --rm -it -v "%cd%":/root/env magickos-buildenv`
- Windows (Powershell): `docker run --rm -it -v "${pwd}:/root/env" magickos-buildenv`

Build for x86:

- `make build-x86_64`

to leave the build environment type `exit`

## Emulate

Emulate Magick-OS using Qemu

- `qemu-system-x86_64 -cdrom dist/x86_64/kernal.iso`

use this one if you have added to path and the previous doesn't work

- `"C:\Program Files\qemu\qemu-system-x86_64.exe" -cdrom dist/x86_64/kernal.iso`
