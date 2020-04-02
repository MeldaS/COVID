
### Using NO2 as a proxy for effectiveness self-isolation / lockdown measures:

**Goal for final visual output**
- Interactive visualization showing timeseries data of NO2 levels over time (Dec/Jan until now). 
  - Time slider to allow users to move back and forth
- Graph displaying total NO2 of area of interest over time 
- Graph displaying total confirmed cases of area of interest over time 
- Initially we may select a few countries, but ideally the goal is to have this on a global scale

**Goal of outputs**
- Understand impact of existing policies
- Understand effectiveness of policies at different stages of virus spread
- Understand spatial / country / regional differences
- Make predictions based on the above

**Data:** Sentinel-2 and / or Landsat-8

**Tool:** Google Earth Engine for data access, analysis and UI features. 

**Public page:** Either embed GEE viz into a webpage or article (static or dynamic), or create GEE app

**Potential extensions:**
- Add Twitter geotagged data on top – to understand if we can predict outbreaks on a spatial level from twitter activity 
-	Add data on hospital beds or anything else that would indicate country health system preparedness 
-	Add road network data to run connectivity models / percolation analyses 
