# aliases for bash and zsh shells

## installation

1. copy the `aliases` file to a directory and add the following code block to load it into the `.bashrc` or `.zshrc` file. Example

```bash
if [[ -f "$HOME/.config/shell/aliases" ]]; then
    source "$HOME/.config/shell/aliases"
fi
```
---
