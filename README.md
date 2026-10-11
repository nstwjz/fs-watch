# fs-watch

A portable file watcher with debouncing and ignore patterns.

## Why

Extracted from a larger codebase where it had grown organically.

## Install

```bash
pip install fs-watch
```

## Usage

```python
from fs_watch import fsWatch

result = fsWatch("example")
print(result)
```

## Notes

- No runtime dependencies outside the standard library.
- Tested on Python 3.9 and newer.

## License

MIT
