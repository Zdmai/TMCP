# Weather MCP Server

This is a Model Context Protocol (MCP) server that provides weather information and forecasts.

## Features

- Get weather forecasts for any location with latitude and longitude
- Get weather alerts for US states
- Simple API for LLM integration

## Usage

To run the server:

```bash
uv --directory /path/to/weather run weather
```

## Tools

### get_forecast
Gets a weather forecast for a specific location using latitude and longitude.

### get_alerts
Gets active weather alerts for a US state using a two-letter state code.

## Dependencies

- mcp (Model Context Protocol)
- httpx
- fastmcp

## License

MIT
