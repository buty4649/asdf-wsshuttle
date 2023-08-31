<div align="center">

# asdf-wsshuttle [![Build](https://github.com/buty4649/asdf-wsshuttle/actions/workflows/build.yml/badge.svg)](https://github.com/buty4649/asdf-wsshuttle/actions/workflows/build.yml) [![Lint](https://github.com/buty4649/asdf-wsshuttle/actions/workflows/lint.yml/badge.svg)](https://github.com/buty4649/asdf-wsshuttle/actions/workflows/lint.yml)

[wsshuttle](https://github.com/yabeenico/wsshuttle) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add wsshuttle
# or
asdf plugin add wsshuttle https://github.com/buty4649/asdf-wsshuttle.git
```

wsshuttle:

```shell
# Show all installable versions
asdf list-all wsshuttle

# Install specific version
asdf install wsshuttle latest

# Set a version globally (on your ~/.tool-versions file)
asdf global wsshuttle latest

# Now wsshuttle commands are available
wsshuttle --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/buty4649/asdf-wsshuttle/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [buty4649](https://github.com/buty4649/)
