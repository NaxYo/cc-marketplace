# Claude Code Plugin Marketplace

## Available Plugins

| Plugin | Description |
|--------|-------------|
| [charon](https://github.com/NaxYo/charon) | Event-driven workflows - await external events, schedule tasks, chain workflows |

## Installing Charon

1. Start the Charon service:
   ```bash
   npx charon-hooks
   ```

2. In Claude Code, add the marketplace and install:
   ```
   /plugin marketplace add NaxYo/cc-marketplace
   /plugin install charon@cc-marketplace
   ```

For system service setup and configuration options, see the [Advanced Installation Guide](https://github.com/NaxYo/charon/blob/main/docs/INSTALL.md).

## Contributing

Add an entry to `plugins.json` and submit a PR.

## License

MIT
