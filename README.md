<div align="center">

# asdf-transifex [![Build](https://github.com/ORCID/asdf-transifex/actions/workflows/build.yml/badge.svg)](https://github.com/ORCID/asdf-transifex/actions/workflows/build.yml) [![Lint](https://github.com/ORCID/asdf-transifex/actions/workflows/lint.yml/badge.svg)](https://github.com/ORCID/asdf-transifex/actions/workflows/lint.yml)


[transifex](https://github.com/transifex/cli) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add transifex https://github.com/ORCID/asdf-transifex.git
```

transifex:

```shell
# Show all installable versions
asdf list-all transifex

# Install specific version
asdf install transifex latest

# Set a version globally (on your ~/.tool-versions file)
asdf global transifex latest

# Now transifex commands are available
transifex --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

