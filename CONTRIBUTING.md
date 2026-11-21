# Contributing to Taara

Thank you for helping. Taara apps are small, so every contribution matters.

## Before you start

- For anything bigger than a small fix, open an issue first so we can agree on the approach.
- Every app follows the GNOME Human Interface Guidelines and the Taara design system in its `design/` folder. Use the libadwaita widgets each component guide names, and don't add custom colours, fonts or title bars.
- Taara apps work offline, never send data anywhere without the person asking, and keep files in standard formats.

## Building an app

Each repository's README explains how to build it. In short:

1. Install GNOME Builder, or `flatpak-builder` with the GNOME SDK.
2. Clone the repository and open it in Builder, or build the development manifest in `build-aux/`.
3. Run the tests and linters listed in the README before sending a change.

## Sending a change

1. Fork the repository and create a branch for your change.
2. Keep each pull request to one change, with a clear title and a short description of what and why.
3. Make sure the app builds, the tests pass, and any new interface follows the design system.
4. Be patient: Taara is maintained in spare time.

## Translations and design

Translations and design feedback are very welcome. Open an issue to get started.

By contributing, you agree that your work is released under the repository's license (GPL-3.0-or-later), and you agree to follow our [Code of Conduct](CODE_OF_CONDUCT.md).
