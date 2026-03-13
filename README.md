# claude-plugins

Claude Code plugin marketplace for [RageLtd](https://github.com/RageLtd).

## Install

Add this marketplace to Claude Code:

```
/plugin marketplace add RageLtd/claude-plugins
```

Then install any plugin:

```
/plugin install goldfish@rageltd
/plugin install claude-rules@rageltd
/plugin install cartographer@rageltd
```

## Available Plugins

| Plugin | Description |
|--------|-------------|
| [goldfish](https://github.com/RageLtd/Goldfish) | Persistent agent memory — because your AI shouldn't have the memory of a goldfish |
| [claude-rules](https://github.com/RageLtd/claude-rules) | Distributable coding standards and workflow rules |
| [cartographer](https://github.com/RageLtd/cartographer) | Codebase structure mapping via Tree-sitter AST parsing |

## How it works

This repo is just a marketplace catalog. Plugin code lives in each plugin's own repo. When a plugin publishes a new release, it dispatches an event to this repo, which automatically updates the version in `marketplace.json`.

## License

[Unlicense](LICENSE) — public domain.
