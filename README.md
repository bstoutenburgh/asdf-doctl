<div align="center">

# asdf-doctl [![Build](https://github.com/bstoutenburgh/asdf-doctl/actions/workflows/build.yml/badge.svg)](https://github.com/bstoutenburgh/asdf-doctl/actions/workflows/build.yml) [![Lint](https://github.com/bstoutenburgh/asdf-doctl/actions/workflows/lint.yml/badge.svg)](https://github.com/bstoutenburgh/asdf-doctl/actions/workflows/lint.yml)

[doctl](https://github.com/digitalocean/doctl)  plugin for the [asdf version manager](https://asdf-vm.com). Check doctl's README for latest supported installation options but if they do not suit your needs this can work for 1.21.1+.

</div>

# Contents

- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Install

Plugin:

```shell
asdf plugin add doctl
# or
asdf plugin add doctl https://github.com/bstoutenburgh/asdf-doctl.git
```

doctl:

```shell
# Show all installable versions
asdf list-all doctl

# Install specific version
asdf install doctl latest

# Set a version globally (on your ~/.tool-versions file)
asdf global doctl latest

# Now doctl commands are available
doctl help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/bstoutenburgh/asdf-doctl/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Ben Stoutenburgh](https://github.com/bstoutenburgh/)
