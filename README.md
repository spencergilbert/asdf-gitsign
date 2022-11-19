<div align="center">

# asdf-gitsign [![Build](https://github.com/spencergilbert/asdf-gitsign/actions/workflows/build.yml/badge.svg)](https://github.com/spencergilbert/asdf-gitsign/actions/workflows/build.yml) [![Lint](https://github.com/spencergilbert/asdf-gitsign/actions/workflows/lint.yml/badge.svg)](https://github.com/spencergilbert/asdf-gitsign/actions/workflows/lint.yml)


[Gitsign](https://github.com/sigstore/gitsign) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add gitsign
# or
asdf plugin add gitsign https://github.com/spencergilbert/asdf-gitsign.git
```

gitsign:

```shell
# Show all installable versions
asdf list-all gitsign

# Install specific version
asdf install gitsign latest

# Set a version globally (on your ~/.tool-versions file)
asdf global gitsign latest

# Now gitsign commands are available
gitsign --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/spencergilbert/asdf-gitsign/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Spencer Gilbert](https://github.com/spencergilbert/)

