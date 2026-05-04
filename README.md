# asdf-azcopy

[azcopy](https://github.com/Azure/azure-storage-azcopy) plugin for the [asdf version manager](https://asdf-vm.com).

## Contents

- [Plugin Dependencies](#plugin-dependencies)
- [Install](#install)
- [License](#license)

## Plugin Dependencies

- `curl` - for azcopy downloads from upstream releases

## Install

Plugin:

```shell_session
$ asdf plugin add azcopy https://github.com/el-aasi/asdf-azcopy
```

azcopy:

```shell_session
# Show all installable versions
$ asdf list all azcopy

# Install latest version
$ asdf install azcopy latest

# Set version
$ asdf set -u azcopy latest

# Run azcopy
$ azcopy --version
azcopy version                      10.32.3
[...]
```

Refer to the [upstream azure-cli repository](https://github.com/Azure/azure-storage-azcopy) for documentation and usage instructions.

Check the [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to install & manage versions.

## License

See [LICENSE](LICENSE)
