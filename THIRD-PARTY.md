# Third-party components

The installer contains five pinned Linux/amd64 images: application, public edge, PostgreSQL, Garage and LiveKit. Exact image identities appear in its BUNDLE-MANIFEST.json and in [SOURCES.json](https://github.com/alexvectorgsai/tabula-one-server/releases/download/component-sources-2026.10.24.3/SOURCES.json).

License texts and corresponding source/build materials are available in the [source-only release](https://github.com/alexvectorgsai/tabula-one-server/releases/tag/component-sources-2026.10.24.3); see [SOURCES.md](SOURCES.md) for verification and component details. Original copyright and license texts remain authoritative. Application beta expiry does not terminate the upstream rights to third-party components.

Garage source and Cargo/Nix build inputs, native sharp/libvips build scripts and dependencies, Debian/Alpine packages, Go modules/toolchains and the original build recipe are supplied. The installer keeps its included notices and SHA-256 manifest; separate source archives are optional at runtime.

The installer is currently a draft pending the first real-server acceptance. Source-only releases and GitHub's automatic Source code archives are not installable packages.
