<div align="center">

# asdf-octopilot [![Build](https://github.com/MPV/asdf-octopilot/actions/workflows/build.yml/badge.svg)](https://github.com/MPV/asdf-octopilot/actions/workflows/build.yml) [![Lint](https://github.com/MPV/asdf-octopilot/actions/workflows/lint.yml/badge.svg)](https://github.com/MPV/asdf-octopilot/actions/workflows/lint.yml)

[octopilot](https://dailymotion-oss.github.io/octopilot/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add octopilot
# or
asdf plugin add octopilot https://github.com/MPV/asdf-octopilot.git
```

octopilot:

```shell
# Show all installable versions
asdf list-all octopilot

# Install specific version
asdf install octopilot latest

# Set a version globally (on your ~/.tool-versions file)
asdf global octopilot latest

# Now octopilot commands are available
octopilot --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/MPV/asdf-octopilot/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [@MPV](https://github.com/MPV/)
