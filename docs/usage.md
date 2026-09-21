# Converter usage

The `src/converter.py` module provides temperature conversion helpers for
student-tools.

## Supported conversion units

| Unit | Symbol | Direction |
|------|--------|-----------|
| Celsius | °C | to / from Fahrenheit |
| Fahrenheit | °F | to / from Celsius |

No other units are supported in this version.

## Functions

### `celsius_to_fahrenheit(celsius)`

| Item | Description |
|------|-------------|
| Parameter | `celsius` |
| Data type | `float` or `int` |
| Return type | `float` |
| Return value | Temperature in degrees Fahrenheit |

```python
from src.converter import celsius_to_fahrenheit

celsius_to_fahrenheit(0)    # 32.0
celsius_to_fahrenheit(100)  # 212.0
```

### `fahrenheit_to_celsius(fahrenheit)`

| Item | Description |
|------|-------------|
| Parameter | `fahrenheit` |
| Data type | `float` or `int` |
| Return type | `float` |
| Return value | Temperature in degrees Celsius |

```python
from src.converter import fahrenheit_to_celsius

fahrenheit_to_celsius(32)   # 0.0
fahrenheit_to_celsius(212)  # 100.0
```
