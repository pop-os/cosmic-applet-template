# COSMIC Applet Template

A template for developing applets for the COSMIC™ desktop environment using [libcosmic][libcosmic].

## Getting Started

> Please refer to the [COSMIC Trademark Policy][cosmic-trademark] when choosing a name for a project.

To create an applet with this template, [install `cargo generate`][cargo-generate] and run:

```sh
cargo generate gh:pop-os/cosmic-applet-template
```

A [justfile](./justfile) is included by default with common recipes used by other COSMIC projects. Install from [casey/just][just]

- `just` builds the applet with the default `just build-release` recipe
- `just run` builds and runs the applet
- `just install` installs the project into the system
- `just vendor` creates a vendored tarball
- `just build-vendored` compiles with vendored dependencies from that tarball
- `just check` runs clippy on the project to check for linter warnings
- `just check-json` can be used by IDEs that support LSP

## Documentation

Refer to the [libcosmic API documentation][api-docs] and [book][book] for help with building applets with [libcosmic][libcosmic].

[api-docs]: https://pop-os.github.io/libcosmic/cosmic/
[book]: https://pop-os.github.io/libcosmic-book/
[cargo-generate]: https://cargo-generate.github.io/cargo-generate/installation.html
[cosmic-trademark]: https://github.com/pop-os/cosmic-epoch/blob/master/TRADEMARK.md
[just]: https://github.com/casey/just
