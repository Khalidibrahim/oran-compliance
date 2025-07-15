# oran-compliance
This dataset is used for the compliance testing of the O-RAN devices. 
## Description  
This dataset contains a 2D grid of complex numbers stored in `uPlaneGrid_complex.csv`. Each cell represents a point on the complex plane, formatted as `a+bi` (e.g., `0.1867+0.0619i`).  

## File Format  
- Format: CSV (Comma-Separated Values)  
- Structure:  
  - Rows represent grid rows.  
  - Columns represent grid columns.  
  - Delimiter: `,`  
  - Complex numbers are formatted as `real+imaginaryi`.  

## Metadata  
- Size: 3276 x 280  
- Domain: ORAN, Device compliance 
- License: MIT 

## Usage  
### Python Example:  
```python
import numpy as np

# Load the dataset
data = np.genfromtxt('uPlaneGrid_complex.csv', delimiter=',', dtype=np.complex128)
print(data.shape)  # Output: (rows, columns)
