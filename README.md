# Custom Fedora

This is a opinionate fedora distribution with the help of image builder.

## Image Builder

Image builder is a command line tool, which is part of the tools in [osbuild](https://osbuild.org).

List all types

    image-builder list --filter distro:fedora-44

## Customization

The image-builder will generate a minimal-installer

    sudo image-builder build image-installer --distro fedora-44 --blueprint custom_fedora.toml
