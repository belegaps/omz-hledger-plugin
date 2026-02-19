# hledger plugin

This plugin provides aliases and completions for [hledger](https://hledger.org/), a powerful, double-entry accounting tool.

## Installation

### oh-my-zsh

1. Clone this repository into your custom plugins directory:
   ```bash
   git clone https://github.com/your-username/hledger-zsh-plugin.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/hledger
   ```
2. Add the plugin to the list of plugins for Oh My Zsh to load (inside `~/.zshrc`):
   ```bash
   plugins=(... hledger)
   ```
3. Restart your shell or run `source ~/.zshrc`.

## Aliases

```markdown
| Alias  | Command       | Description                         |
| :----- | :------------ | :---------------------------------- |
| `hl`   | `hledger`     | Execute hledger                     |
| `hlis` | `hledger is`  | Generate an Income Statement        |
| `hlbs` | `hledger bs`  | Generate a Balance Sheet            |
| `hlr`  | `hledger reg` | Display matched postings (Register) |
```

## Features

- Standard aliases for common hledger commands.
- (Future) Auto-completion for accounts and descriptions.

## Usage

Simply run any of the aliases provided above:
```bash
hl is
hlbs
```
