# Amulet Map Editor (Personal Fork)

> **⚠️ Disclaimer**
>
> This is a **personal fork** for learning purposes, not the official repository.
> - I am **not affiliated** with the Amulet Team.
> - Official version (paid) : [Amulet-Team/Amulet-Map-Editor](https://github.com/Amulet-Team/Amulet-Map-Editor)
> - **No pre-built binaries provided** - please build yourself using GitHub Actions.
> - If you appreciate the project, consider **purchasing the official version** to support the developers.
> - For bug reports and feature requests, please refer to the [official repository](https://github.com/Amulet-Team/Amulet-Map-Editor/issues).

![cover](resource/img/cover.jpg)

## Differences from Official Repo

- Removed code signing (personal fork has no certificate)
- Modified GitHub Actions to support manual triggering
- For personal learning and research only

## Build Yourself

1. Go to `Actions` tab
2. Select `Build Windows (Simplified)` workflow
3. Click `Run workflow`
4. Download the installer from `Artifacts`

## About Amulet

A Minecraft world editor and converter that supports all versions since Java 1.12 and Bedrock 1.7.

Official repo: [Amulet-Team/Amulet-Map-Editor](https://github.com/Amulet-Team/Amulet-Map-Editor)

## Running from Source

**If you are running a compiled build you do NOT need to do this.**

See instructions on [amuletmc.com](https://www.amuletmc.com/installing-from-source)

## Running with Docker (Linux)

The Docker image runs on any Linux distro with Docker support.\
To run the Docker image, clone this repository and run `rundocker.sh`.\
Compatibility with wayland is done through xwayland for x11 support.

## Legacy builds

Old versions (prior to 0.10.45) can be found on the [official releases page](https://github.com/Amulet-Team/Amulet-Map-Editor/releases).

Extract the contained folder to a location on your computer and run `amulet_app.exe`.

## Contributing

For information about contributing to this project, please read the [contribution](contributing.md) file.
