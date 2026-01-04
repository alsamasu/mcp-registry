# phpIPAM MCP Server

MCP server for [phpIPAM](https://phpipam.net/) IP Address Management.

## Documentation

Full documentation available at: https://github.com/alsamasu/phpipam-mcp

## Features

- List and search IP addresses, subnets, and sections
- Allocate and release IP addresses
- Support for token and password authentication
- Configurable write operations with safety toggles

## Quick Start

```bash
docker run -i --rm \
  -e PHPIPAM_BASE_URL=https://phpipam.example.com \
  -e PHPIPAM_APP_ID=myapp \
  -e PHPIPAM_TOKEN=your-api-token \
  mcp/phpipam-mcp
```
