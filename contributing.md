# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test gitsign https://github.com/spencergilbert/asdf-gitsign.git "gitsign --help"
```

Tests are automatically run in GitHub Actions on push and PR.
