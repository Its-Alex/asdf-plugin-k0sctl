# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test k0sctl https://github.com/Its-Alex/asdf-plugin-k0sctl.git "k0sctl --help"
```

Tests are automatically run in GitHub Actions on push and PR.
