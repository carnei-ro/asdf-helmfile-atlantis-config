# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test helmfile-atlantis-config https://github.com/carnei-ro/asdf-helmfile-atlantis-config.git "helmfile-atlantis-config"
```

Tests are automatically run in GitHub Actions on push and PR.
