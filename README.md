# oran-compliance

## Description 
This dataset is used for the compliance testing of the O-RAN devices. Each cell contains a complex IQ sample for a Resource Element (RE), as used in real-time transmission. This dataset corresponds to the time-frequency resource map in the O-RAN fronthaul U-Plane for a 100 MHz 5G NR signal using 30 kHz SCS:  



## File Format  
- Format: CSV
- Structure:  
  - Rows represent grid rows ( frequency domain).  
  - Columns represent grid columns (time domain).  
  - Delimiter: `,`  
  - Complex numbers are formatted as `real+imaginaryi`.  

## Metadata  
- Size: 3276 × 280 (Frequency × Time)
- Frequency: 3276 subcarriers = 273 PRBs × 12 subcarriers.  
- Time: 280 OFDM symbols = 20 slots × 14 symbols per slot.  
- Domain: ORAN, 5G
- License: CC-BY 4.0 
