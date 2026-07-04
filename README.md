# ax-homebrew

Homebrew tap for [ax (agentswitch)](https://github.com/noahirzinger/agentswitch), a daemonless job switchboard and control plane for command-line coding agents.

## Install

```sh
brew install noahirzinger/ax/ax
```

Or tap first, then install:

```sh
brew tap noahirzinger/ax
brew install ax
```

## About

`ax` is a thin, daemonless supervisor that routes work across multiple coding agents (Claude Code, Codex, Gemini CLI, etc.) and gives you a unified control plane from the terminal.

`Formula/ax.rb` in this repo is published automatically by [goreleaser](https://goreleaser.com/) on each tagged release. Do not hand-edit it.

## License

Apache-2.0. See the [main project](https://github.com/noahirzinger/agentswitch) for details.
