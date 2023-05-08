<div align="center">

# asdf-plugin-k0sctl [![Build](https://github.com/Its-Alex/asdf-plugin-k0sctl/actions/workflows/build.yml/badge.svg)](https://github.com/Its-Alex/asdf-plugin-k0sctl/actions/workflows/build.yml) [![Lint](https://github.com/Its-Alex/asdf-plugin-k0sctl/actions/workflows/lint.yml/badge.svg)](https://github.com/Its-Alex/asdf-plugin-k0sctl/actions/workflows/lint.yml)


[k0sctl](https://github.com/k0sproject/k0sctl) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [asdf-plugin-k0sctl  ](#asdf-plugin-k0sctl--)
- [Contents](#contents)
- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add k0sctl
# or
asdf plugin add k0sctl https://github.com/Its-Alex/asdf-plugin-k0sctl.git
```

k0sctl:

```shell
# Show all installable versions
asdf list-all k0sctl

# Install specific version
asdf install k0sctl latest

# Set a version globally (on your ~/.tool-versions file)
asdf global k0sctl latest

# Now k0sctl commands are available
k0sctl --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/Its-Alex/asdf-plugin-k0sctl/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [ItsAlex](https://github.com/Its-Alex/)
