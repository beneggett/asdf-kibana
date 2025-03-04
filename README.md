<div align="center">

# asdf-kibana [![Build](https://github.com/beneggett/asdf-kibana/actions/workflows/build.yml/badge.svg)](https://github.com/beneggett/asdf-kibana/actions/workflows/build.yml) [![Lint](https://github.com/beneggett/asdf-kibana/actions/workflows/lint.yml/badge.svg)](https://github.com/beneggett/asdf-kibana/actions/workflows/lint.yml)

[kibana](https://github.com/beneggett/asdf-kibana) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add kibana
# or
asdf plugin add kibana https://github.com/beneggett/asdf-kibana.git
```

kibana:

```shell
# Show all installable versions
asdf list-all kibana

# Install specific version
asdf install kibana latest

# Set a version globally (on your ~/.tool-versions file)
asdf global kibana latest

# Now kibana commands are available
kibana --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/beneggett/asdf-kibana/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Ben Eggett](https://github.com/beneggett/)
