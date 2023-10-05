# Planned revisions to reproduction of Social inequities in the distribution of COVID-19 (Chakraborty 2021)
Author: Tate Sutter
## Analysis

1. Improve color scheme of GEE model weights map (lines 1864-1889).

2. Improve the formatting of the missing data table with Kable and/or KableExtra functions and/or by transposing the table to vertical orientation. (Lines 557-576)

3. Decrease the population threshold of the SpatialEpi-Kulldorf Test to 10% of points instead of the original 50% (Lines 791-821).

## Results

For step 1, the improved color scheme visualizes the data with more frequent increments. 

For step 2, the missing data table now can be easily read in a vertical format.

For step 3, decreasing the population threshold for the SpatialEpi-Kulldorf Test produces COVID counties at the county scale at a finer level. 
The original test, sets the population threshold at 50%. 
The lower threshold should produce more localized clusters. 
 

## Discussion

For step 1, the new visualization should convey the GEE model weights in a more comprehensible design.

For step 2, the table being vertically represented should increase the readability of the missing data graph.  

If, for step 3, the new analysis should produce more localized county-level COVID-19 clusters, then the inputs to the General Equalizing Equations (GEE) should be more accurate. 
This depends on the significance of the new clusters. 
