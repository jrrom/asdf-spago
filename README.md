<div align="center">

# asdf-spago [![Build](https://github.com/jrrom/asdf-spago/actions/workflows/build.yml/badge.svg)](https://github.com/jrrom/asdf-spago/actions/workflows/build.yml) [![Lint](https://github.com/jrrom/asdf-spago/actions/workflows/lint.yml/badge.svg)](https://github.com/jrrom/asdf-spago/actions/workflows/lint.yml)

[spago](https://github.com/purescript/spago) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `node` and `purs`

# Install

Plugin:

```shell
asdf plugin add spago https://github.com/jrrom/asdf-spago.git
```

spago:

```shell
# Show all installable versions
asdf list-all spago

# Install specific version
asdf install spago latest

# Set a version globally (on your ~/.tool-versions file)
asdf global spago latest

# Now spago commands are available
spago --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/jrrom/asdf-spago/graphs/contributors)!

# Thanks

Special thanks to [asdf](https://github.com/asdf-vm/asdf)

[nsaunders](https://github.com/nsaunders/asdf-spago) (Now archived)

# License

See [LICENSE](LICENSE) © [jrrom](https://github.com/jrrom/)
