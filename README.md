# Setup a Python test environment

This actions provides a helper for setting up a Poetry based Python environment within CI jobs.

- Uses version in `.python-version` (fallback to latest 3.14)
- Handles poetry install

Example usage:

```
  ci:
    runs-on: ubuntu-latest
    steps:
      - uses: cluebotng/ci-setup-python-environment@main
```
