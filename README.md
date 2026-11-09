# Fast SSH releases

Windows installers for Fast SSH, a fast desktop SSH client.

## Install

1. Open the [latest release](https://github.com/itisvincent/fast-ssh-releases/releases/latest).
2. Download `fast-ssh-<version>-setup.exe` and run it.
3. Fast SSH installs for your user only. It needs no administrator rights.

Windows SmartScreen may warn that the publisher is unknown. Click **More info**, then **Run anyway**.

## Updates

Fast SSH checks this page for new versions. When one is out, the app shows a banner. Click **Download and install** to update.

Each release has a `latest.json` file. It holds the version, the installer link, the installer's SHA-256, and an Ed25519 signature. The app accepts an update only when the signature matches the public key built into the app, and runs the installer only when its SHA-256 matches. The update check downloads this one public file and sends nothing about you or your hosts.

You can turn off the startup check in **Settings > Updates**.
