# MCP Server Deepdive Deployment

A Model Context Protocol (MCP) server implementation using FastMCP for deployment demonstrations.

## Overview

This project demonstrates a simple MCP server built with FastMCP that provides basic mathematical operations. It's designed to showcase MCP server deployment patterns and best practices.

## Features

- **Addition Tool**: Simple addition operation for two integers
- **FastMCP Integration**: Built using the FastMCP framework
- **Python Package Structure**: Proper Python packaging with setuptools
- **CLI Entry Point**: Command-line interface for easy server execution

## Project Structure

```
mcp-server-deepdive-deployment/
├── src/
│   └── mcpserver/
│       ├── __init__.py
│       ├── __main__.py
│       └── deployment.py
├── main.py
├── pyproject.toml
└── README.md
```

## Installation

1. Clone this repository:
```bash
git clone https://github.com/IshayBalash/mcpserverexmaple.git
cd mcpserverexmaple
```

2. Install the package:
```bash
pip install -e .
```

## Usage

### Running the Server

You can run the MCP server in several ways:

1. **Using the package entry point:**
```bash
mcp-server
```

2. **Using Python module execution:**
```bash
python -m mcpserver
```

3. **Direct execution:**
```bash
python main.py
```

### Available Tools

#### Add Tool
- **Function**: `add(a: int, b: int) -> int`
- **Description**: Adds two integers and returns the result
- **Parameters**:
  - `a`: First integer
  - `b`: Second integer
- **Returns**: Sum of the two integers

## Development

### Requirements

- Python >= 3.11
- mcp[cli] >= 1.19.0

### Project Configuration

The project uses `pyproject.toml` for configuration:
- Package metadata and dependencies
- Entry points for CLI execution
- Setuptools build configuration

## MCP Protocol

This server implements the Model Context Protocol (MCP), which enables:
- Standardized communication between AI models and external tools
- Tool discovery and execution
- Resource management
- Secure and controlled access to external capabilities

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Add tests if applicable
5. Submit a pull request

## License

This project is open source and available under the MIT License.

## Author

Ishay Balash - [GitHub](https://github.com/IshayBalash)