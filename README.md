# homebrew-tap

Homebrew tap for [`aolbeam-ask`](https://pypi.org/project/aolbeam-ask/) — a lightweight, stateless terminal AI CLI that knows when to search the web.

## Install

```bash
brew install sinhaKAN-ra/tap/ask
```

Then run:

```bash
ask "what is the capital of France?"
```

The command is `ask`. On first run it needs an API key for an OpenAI-compatible provider — you bring your own key (the package ships none). See the main project:

- Website: https://ask.aolbeam.com
- Source & docs: https://github.com/sinhaKAN-ra/ask
- PyPI: https://pypi.org/project/aolbeam-ask/

## What this tap contains

| Formula | Installs | Command |
|---|---|---|
| `Formula/ask.rb` | `aolbeam-ask` from PyPI into an isolated virtualenv | `ask` |

## Upgrading

```bash
brew update
brew upgrade ask
```

## License

The formula is MIT, matching the upstream project.
