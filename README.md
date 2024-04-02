<div align="center">

# asdf-sourcedocs [![Build](https://github.com/tuist/asdf-sourcedocs/actions/workflows/build.yml/badge.svg)](https://github.com/tuist/asdf-sourcedocs/actions/workflows/build.yml) [![Lint](https://github.com/tuist/asdf-sourcedocs/actions/workflows/lint.yml/badge.svg)](https://github.com/tuist/asdf-sourcedocs/actions/workflows/lint.yml)

[SourceDocs](https://github.com/SourceDocs/SourceDocs) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add sourcedocs https://github.com/tuist/asdf-sourcedocs.git
```

sourcedocs:

```shell
# Show all installable versions
asdf list-all sourcedocs

# Install specific version
asdf install sourcedocs latest

# Set a version globally (on your ~/.tool-versions file)
asdf global sourcedocs latest

# Now sourcedocs commands are available
sourcedocs --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/tuist/asdf-sourcedocs/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Tuist](https://github.com/tuist/)
