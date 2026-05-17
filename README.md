# Image Builder

[osbuild](https://osbuild.org)

List all types

    image-builder list --filter distro:fedora-44

# Customization

The image-builder will generate a minimal-installer

    sudo image-builder build image-installer --distro fedora-44 --blueprint custom_fedora.toml
