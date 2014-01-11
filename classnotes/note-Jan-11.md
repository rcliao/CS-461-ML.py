# Definitions:

## Suervise Learning:
**right answer** given

## Regression:
Predict Continues valued output

## Classification
Discrete valued output (e.g. 0 or 1)

# Note on the Python Matrix
By using pumpy, python can do matrix calculation quite easily

## Example code:
```python
import numpy as np

a1 = np.matrix("1 2 3; 4 5 6; 7 8 9") # last row doesn't need semi-colon

a1 = np.matrix("1; 0; 0")

print a1 * a2 # easy multiplication
```
