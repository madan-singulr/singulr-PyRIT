# PyRIT - SQLAlchemy 2.x Compatible Version

This project is a modified version of [PyRIT (Python Risk Identification Tool for LLMs)](https://github.com/Azure/PyRIT) updated to work with SQLAlchemy 2.x releases, including 2.0.x and newer.

## Overview

PyRIT is a library used to assess the robustness of Large Language Models (LLMs). This fork maintains the functionality of the original PyRIT while ensuring compatibility with modern SQLAlchemy 2.x environments.

## Key Updates

- Updated ORM models to be compatible with SQLAlchemy 2.x
- Replaced deprecated SQLAlchemy 1.4-style imports and relationship patterns
- Updated model declaration patterns for SQLAlchemy 2.x
- Kept compatibility with current Pydantic-based model usage

## Installation

```bash
pip install pyrit-sqlalchemy14
```

Or with Poetry:

```bash
poetry add pyrit-sqlalchemy14
```

## Requirements

- Python 3.10 or higher
- SQLAlchemy 2.0.6 or newer
- Pydantic 2.x

## Usage

The usage is identical to the original PyRIT library. Please refer to the [official PyRIT documentation](https://github.com/Azure/PyRIT) for details.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Original PyRIT developed by Microsoft AI Red Team
- This SQLAlchemy 2.x compatible version is maintained independently
