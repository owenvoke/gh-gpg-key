# `gh gpg-key` GitHub CLI extension

This adds functionality to list and add GPG keys to GitHub until [cli/cli#3822](https://github.com/cli/cli/pull/3822) is merged.

## Install

```shell
gh extension install owenvoke/gh-gpg-key
```

### Usage

```shell
# List the help
gh gpg-key

# Display a list of GPG keys assigned to your account
gh gpg-key list

# Add a GPG key to your account based on the id or email
gh gpg-key add [keyid|email]
```

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
