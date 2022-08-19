# OHW22 - Extreme Events & Anomaly Detection 

---
## About 

This is a collaborative project undertaken as part of Ocean Hack Week 2022. 
---
### Collaborators

- Hung Nguyen (email: hung.nguyen@uconn.edu)
- De'Marcus (email: demarcus1.robinson@atmos.ucla.edu)
- Adam Kemberling (email: akemberling@gmri.org)

---
### Background

Extreme events (heatwaves, severe weather, droughts, floods) have gained an increased level of research attention in recent years. However, tracking and describing these events in multiple dimensions (time + space) can be difficult with current tools, often sacrificing one in favor of the other.

The Northwest Atlantic is sensitive to climate change due to its location near the crossroads of the subtropical and subpolar circulations (Claret et al., 2018). Recent analysis shows that Gulf Stream (warm circulation) is changing regime toward north (Gangopadhyay et al., 2019). So, we decide to use Northwest Atlantic as a test case for this project. 

### Goals

The goal of this project was to collaborate on a tool the would aid in the detecction and tracking of extreme events in spatio-temporal arrays.

### Datasets

This project uses sea surface temperature (SST) data, and the detection of marine heatwave events as a testing ground for spatio-temporal tracking of extreme events. SST data are retrieved from NOAA Daily Optimum Interpolation Sea Surface, spanning from 1981 to 2022. 

### Workflow

 1. Load an observation dataset to check for extreme events
 2. Determine extreme event criterion (percentile, hard-thresholds)
 3. Check for extreme events against a threshold dataset
 4. Track events temporally for each grid cell
 5. Track events spatially, across neighboring cells

### References:
Claret, M., Galbraith, E. D., Palter, J. B., Bianchi, D., Fennel, K., Gilbert, D., & Dunne, J. P. (2018). Rapid coastal deoxygenation due to ocean circulation shift in the northwest Atlantic. Nature Climate Change, 8(10), 868–872. https://doi.org/10.1038/s41558-018-0263-1

Gangopadhyay, A., Gawarkiewicz, G., Silva, E. N. S., Monim, M., & Clark, J. (2019). An Observed Regime Shift in the Formation of Warm Core Rings from the Gulf Stream. Scientific Reports, 9(1), 12319. https://doi.org/10.1038/s41598-019-48661-9

Hobday, A. J., Alexander, L. V., Perkins, S. E., Smale, D. A., Straub, S. C., Oliver, E. C., ... & Wernberg, T. (2016). A hierarchical approach to defining marine heatwaves. Progress in Oceanography, 141, 227-238. 

Seidov, D., Mishonov, A., & Parsons, R. (2021). Recent warming and decadal variability of Gulf of Maine and Slope Water. Limnology and Oceanography, 66(9), 3472–3488. https://doi.org/10.1002/lno.11892


