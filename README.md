<div align="center">

# asdf-trivy [![Build](https://github.com/zufardhiyaulhaq/asdf-trivy/actions/workflows/build.yml/badge.svg)](https://github.com/zufardhiyaulhaq/asdf-trivy/actions/workflows/build.yml) [![Lint](https://github.com/zufardhiyaulhaq/asdf-trivy/actions/workflows/lint.yml/badge.svg)](https://github.com/zufardhiyaulhaq/asdf-trivy/actions/workflows/lint.yml)


[trivy](https://github.com/zufardhiyaulhaq/trivy) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add trivy https://github.com/zufardhiyaulhaq/asdf-trivy.git
```

trivy:

```shell
# Show all installable versions
asdf list-all trivy

# Install specific version
asdf install trivy latest

# Set a version globally (on your ~/.tool-versions file)
asdf global trivy latest

# Now trivy commands are available
trivy --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/zufardhiyaulhaq/asdf-trivy/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Zufar Dhiyaulhaq](https://github.com/zufardhiyaulhaq/)
