# short-uid
Because UUIDs can be very long, indexing becomes a challenge. This mini library creates relatively short Unique IDs based on the current timestampt to the micro second.

### Setup
```shell
pip install short-uid
```

### Usage in code
```python
uid62() # Generates case sensitive ID
uid36() # Generates ID with only lowercase letters
```