# mcp-server-oracle
Model Context Protocol server to access oracle

[![Python 3.12](https://img.shields.io/badge/python-3.12-blue.svg)](https://www.python.org/downloads/release/python-3120/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


## Quickstart

To try this in Claude Desktop app, add this to your claude config files:

```json
{
  "mcpServers": {
    "docker-mcp": {
      "command": "uvx",
      "args": [
        "mcp-server-oracle"
      ]
    }
  }
}
```

### Prerequisites

- UV (pacakge manager)
- Python 3.12+
- Claude Desktop

### Installation

#### Claude Desktop Configuration

Add the server configuration to your Claude Desktop config file:

**MacOS**: `~/Library/Application\ Support/Claude/claude_desktop_config.json`  
**Windows**: `%APPDATA%/Claude/claude_desktop_config.json`


## Contributing

1. Fork the repository from [docker-mcp](https://github.com/QuantGeekDev/docker-mcp)
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.