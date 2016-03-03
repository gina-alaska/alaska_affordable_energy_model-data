## com_building_estimates.md

### Responsible Party
  * Organization Name: Geographic Information Network of Alaska (GINA)
  * Email: support+aaem@gina.alaska.edu

### Data Lineage
  * Data File: com_building_estimates.csv
  * Description: Model parameters to estimate non-residential building electric and fuel consumption when no data is available.
    * Line 1: ",Gal/sf Low,Gal/sf Mid,Gal/sf High,kWh/sf Low,kWh/sf Mid,kWh/sf High,Sqft Low ,Sqft Mid,Sqft High,HDD Low,HDD Mid,HDD High"
    * Line 2 : "Estimate units,Gal/sf,Gal/sf,Gal/sf,kWh/sf,kWh/sf,kWh/sf,Sqft,Sqft,Sqft,HDD,HDD,HDD"
      * HDD is heating degree day
      * sf and "Sqft" are equivalent - square footage
    * Line 3:
      * "Lower Limit" [square feet] (12 entries)
    * Line 4:
      * "Upper Limit" [square feet] (12 entries, the upper limit of the high size building is "inf")
  * Processing Steps
    1. Create a com_building_estimates.csv by hand and fill in data using the template as given.
    2. Line 1 is a units descriptor for the estimates as a function of building size (low, mid, high)
    3. Line 2 is a units descriptor for the estimates as a function of building size (low, mid, high)
    4. Line 3 is the lower limit on the 3 building sizes for the 4 categories (Av Gal/sf, Avg kWh/sf, Average sf, Average of HDD); entered from the source file.
    5. Line 4 is the upper limit on the 3 building sizes for the 4 categories (Av Gal/sf, Avg kWh/sf, Average sf, Average of HDD); entered from the source file.

### Source File
  * Description: Estimates of energy use for buildings of 3 sizes, 13 building types, and the average.  An assistant economist with AEA performed statistics on when the estimates for an individual building type/community size should be used and when substitutions with an average should be used (either by building type or by community size). The method - used the proxy suitability at 35% error.  For those with insufficient data, used average for building type.  If building type unusable, used average for community tranche.  Caveats - Square footage was sometimes maintained if the averages that were going to be inserted were logically too high.  Original average maintained.  
  * Filename: Non Res Estimates to Model 02252016.xlsx
  * Date: 02/25/2016
  * Contact Name: Neil McMahon
  * Organization Name: Alaska Energy Authority/Alaska Industrial Development and Export Authority
  * Contact Email: NMcMahon@aidea.org
  * Delivery Method: Basecamp (Alaska Affordable Energy Model Project)
