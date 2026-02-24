<div align="center">

# asdf-helmfile-atlantis-config [![Build](https://github.com/carnei-ro/asdf-helmfile-atlantis-config/actions/workflows/build.yml/badge.svg)](https://github.com/carnei-ro/asdf-helmfile-atlantis-config/actions/workflows/build.yml) [![Lint](https://github.com/carnei-ro/asdf-helmfile-atlantis-config/actions/workflows/lint.yml/badge.svg)](https://github.com/carnei-ro/asdf-helmfile-atlantis-config/actions/workflows/lint.yml)

[helmfile-atlantis-config](https://github.com/carnei-ro/helmfile-atlantis-config) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add helmfile-atlantis-config
# or
asdf plugin add helmfile-atlantis-config https://github.com/carnei-ro/asdf-helmfile-atlantis-config.git
```

helmfile-atlantis-config:

```shell
# Show all installable versions
asdf list-all helmfile-atlantis-config

# Install specific version
asdf install helmfile-atlantis-config latest

# Set a version globally (on your ~/.tool-versions file)
asdf global helmfile-atlantis-config latest

# Now helmfile-atlantis-config commands are available
helmfile-atlantis-config
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/carnei-ro/asdf-helmfile-atlantis-config/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Leandro Carneiro](https://github.com/carnei-ro/)
