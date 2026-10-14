# fs-watch

A portable file watcher with debouncing and ignore patterns.

## Why

The existing libraries were either abandoned or pulled in a large dependency tree.

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
