# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test kube-score https://github.com/bageljp/asdf-kube-score.git "kube-score --help"
```

Tests are automatically run in GitHub Actions on push and PR.
