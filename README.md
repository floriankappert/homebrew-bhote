# homebrew-bhote

Homebrew tap for [bhote](https://github.com/floriankappert/bhote), the topics and agents side panel for herdr.

```sh
brew install floriankappert/bhote/bhote
bhote skills install        # the Claude Code skills bhote and bhote-install
```

Then, in Claude Code: `/bhote-install` sets up the rest (herdr plugin, hooks, machines, monitors).

To open the panel next to your agents when herdr starts:

```sh
herdr plugin link "$(brew --prefix bhote)/share/bhote/herdr-plugin"
```
