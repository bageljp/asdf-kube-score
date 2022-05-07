<div align="center">

# asdf-kube-score [![Build](https://github.com/bageljp/asdf-kube-score/actions/workflows/build.yml/badge.svg)](https://github.com/bageljp/asdf-kube-score/actions/workflows/build.yml) [![Lint](https://github.com/bageljp/asdf-kube-score/actions/workflows/lint.yml/badge.svg)](https://github.com/bageljp/asdf-kube-score/actions/workflows/lint.yml)


[kube-score](https://kube-score.com/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add kube-score
# or
asdf plugin add kube-score https://github.com/bageljp/asdf-kube-score.git
```

kube-score:

```shell
# Show all installable versions
asdf list-all kube-score

# Install specific version
asdf install kube-score latest

# Set a version globally (on your ~/.tool-versions file)
asdf global kube-score latest

# Now kube-score commands are available
kube-score --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/bageljp/asdf-kube-score/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [bageljp](https://github.com/bageljp/)
