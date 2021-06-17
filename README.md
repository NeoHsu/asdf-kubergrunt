<div align="center">

# asdf-kubergrunt ![Build](https://github.com/NeoHsu/asdf-kubergrunt/workflows/Build/badge.svg) ![Lint](https://github.com/NeoHsu/asdf-kubergrunt/workflows/Lint/badge.svg)

[kubergrunt](https://www.gruntwork.io/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add kubergrunt
# or
asdf plugin add kubergrunt https://github.com/NeoHsu/asdf-kubergrunt.git
```

kubergrunt:

```shell
# Show all installable versions
asdf list-all kubergrunt

# Install specific version
asdf install kubergrunt latest

# Set a version globally (on your ~/.tool-versions file)
asdf global kubergrunt latest

# Now kubergrunt commands are available
kubergrunt --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/NeoHsu/asdf-kubergrunt/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Neo Hsu](https://github.com/NeoHsu/)
