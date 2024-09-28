# llama-find

[![PyPI version](https://badge.fury.io/py/llamafind.svg)](https://badge.fury.io/py/llamafind)
[![Python Version](https://img.shields.io/pypi/pyversions/llamafind.svg)](https://pypi.org/project/llamafind/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![CI](https://github.com/yourusername/llamafind-pkg/actions/workflows/ci.yml/badge.svg)](https://github.com/yourusername/llamafind-pkg/actions/workflows/ci.yml)
[![Documentation Status](https://img.shields.io/badge/docs-latest-blue.svg)](https://yourusername.github.io/llamafind-pkg)

## Installation

```bash
pip install -e .
```

## Usage

```python
from llama_find import LlamaFindClient

# Initialize the client
client = LlamaFindClient(api_key="your-api-key")
result = client.query("your query")
print(result)
```

## Features

- Fast and efficient
- Easy to use API
- Comprehensive documentation
- Built-in caching

## Development

### Setup

```bash
# Clone the repository
git clone https://github.com/nikjois/llama-find.git
cd llama-find

# Install development dependencies
pip install -e ".[dev]"
```

### Testing

```bash
pytest
```

## License

MIT

## Author

Nik Jois (nikjois@llamasearch.ai)
