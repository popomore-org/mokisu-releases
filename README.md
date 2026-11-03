# Mokisu Desktop Releases

Public release assets for Mokisu Desktop. The source code and build workflows remain in a separate private repository.

Published builds are available on the [Releases page](https://github.com/popomore-org/mokisu-releases/releases).

Each release contains a macOS installer (`.dmg`), an updater archive (`.app.tar.gz`), its signature (`.sig`), and the update manifest (`latest.json`).

## Release contract

This repository is a distribution channel. Mokisu builds, signs and verifies artifacts in its source repository through the shared meta release adapters; this channel does not rebuild private source. Historical release tags and published assets remain immutable.
