# student-tools

A small collection of student utilities.

## Converter

The converter module currently supports these units:

- Celsius (°C)
- Fahrenheit (°F)

### How to call the functions

```python
from src.converter import celsius_to_fahrenheit, fahrenheit_to_celsius

# Celsius → Fahrenheit
# Parameter: celsius (float | int)
# Returns: float (degrees Fahrenheit)
celsius_to_fahrenheit(0)      # 32.0
celsius_to_fahrenheit(100)    # 212.0

# Fahrenheit → Celsius
# Parameter: fahrenheit (float | int)
# Returns: float (degrees Celsius)
fahrenheit_to_celsius(32)     # 0.0
fahrenheit_to_celsius(212)    # 100.0
```

See [docs/usage.md](docs/usage.md) for parameter types, return values, and
more usage notes.
