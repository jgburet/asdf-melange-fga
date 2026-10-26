<div align="center">

# asdf-melange-fga [![Build](https://github.com/jgburet/asdf-melange-fga/actions/workflows/build.yml/badge.svg)](https://github.com/jgburet/asdf-melange-fga/actions/workflows/build.yml) [![Lint](https://github.com/jgburet/asdf-melange-fga/actions/workflows/lint.yml/badge.svg)](https://github.com/jgburet/asdf-melange-fga/actions/workflows/lint.yml)

[melange](https://melange.sh) (OpenFGA-to-PostgreSQL authorization compiler) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Why `melange-fga`?](#why-melange-fga)
- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Why `melange-fga`?

The `melange` name in the asdf plugin registry already belongs to
[chainguard-dev/melange](https://github.com/chainguard-dev/melange), an unrelated APK package builder.
This plugin installs [pthm/melange](https://github.com/pthm/melange).

Both tools ship a binary named `melange`, so installing both plugins makes their shims collide.

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `sha256sum` or `shasum`, to verify downloads against the release `checksums.txt`.
- Supported platforms: Linux and macOS, on `amd64` and `arm64`.

# Install

Plugin:

```shell
asdf plugin add melange-fga https://github.com/jgburet/asdf-melange-fga.git
```

melange:

```shell
# Show all installable versions
asdf list all melange-fga

# Install specific version
asdf install melange-fga latest

# Set a version in your home directory's .tool-versions file
asdf set -u melange-fga latest

# Now melange commands are available
melange version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/jgburet/asdf-melange-fga/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Jean-Guillaume Buret](https://github.com/jgburet/)
