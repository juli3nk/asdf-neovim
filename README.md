# neovim plugin for the asdf version manager

## Dependencies

- `bash`, `curl`, `tar`.

## Install
### Plugin

```shell
asdf plugin add neovim https://github.com/juli3nk/asdf-neovim.git
```

### neovim

```shell
# Show all installable versions
asdf list-all neovim

# Install specific version
asdf install neovim latest

# Set a version globally (on your ~/.tool-versions file)
asdf global neovim latest

# Now neovim commands are available
neovim -version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to install & manage versions.
