<div align="center">

# asdf-cryptobox [![Build](https://github.com/mrjk/asdf-cryptobox/actions/workflows/build.yml/badge.svg)](https://github.com/mrjk/asdf-cryptobox/actions/workflows/build.yml) [![Lint](https://github.com/mrjk/asdf-cryptobox/actions/workflows/lint.yml/badge.svg)](https://github.com/mrjk/asdf-cryptobox/actions/workflows/lint.yml)

[cryptobox](https://github.com/mrjk/cryptobox) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add cryptobox
# or
asdf plugin add cryptobox https://github.com/mrjk/asdf-cryptobox.git
```

cryptobox:

```shell
# Show all installable versions
asdf list-all cryptobox

# Install specific version
asdf install cryptobox latest

# Set a version globally (on your ~/.tool-versions file)
asdf global cryptobox latest

# Now cryptobox commands are available
bin/cryptobox --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/mrjk/asdf-cryptobox/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [mrjk](https://github.com/mrjk/)
