<div align="center">

# asdf-melange-fga [![Build](https://github.com/jgburet/asdf-melange-fga/actions/workflows/build.yml/badge.svg)](https://github.com/jgburet/asdf-melange-fga/actions/workflows/build.yml) [![Lint](https://github.com/jgburet/asdf-melange-fga/actions/workflows/lint.yml/badge.svg)](https://github.com/jgburet/asdf-melange-fga/actions/workflows/lint.yml)

[melange-fga](https://melange.sh) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add melange-fga
# or
asdf plugin add melange-fga https://github.com/jgburet/asdf-melange-fga.git
```

melange-fga:

```shell
# Show all installable versions
asdf list-all melange-fga

# Install specific version
asdf install melange-fga latest

# Set a version globally (on your ~/.tool-versions file)
asdf global melange-fga latest

# Now melange-fga commands are available
melange version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/jgburet/asdf-melange-fga/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Jean-Guillaume Buret](https://github.com/jgburet/)
