# Magick-OS

    ## Build
        - Linux or MacOS: `docker run --rm -it -v "$pwd":/root/env magickos-buildenv`
        - Windows (cmd): `docker run --rm -it -v "%cd%":/root/env magickos-buildenv`
        - Windows (Powershell): `docker run --rm -it -v "${pwd}:/root/env" magickos-buildenv`

    Build for x86:
        - `make build-x86_64`
