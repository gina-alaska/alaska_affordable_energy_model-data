## population.md

### Responsible Party
  * Organization Name: Geographic Information Network of Alaska (GINA)
  * Email: support+aaem@gina.alaska.edu

### Data Lineage
  * Data File: population.csv
  * Description: Population as a function of year for Alaska communities.
    * First line: Header
    * Column Name [units] (Column Name)
      * Community [unitless] ()
      * 1991...2050 [number of people] (1991 - 2014 measured; 2015 - 2050 forecast)
    * Processing Steps
      1. Remove column AB - containing non-population diagnostics.
      2. Reduce the place_name to just the Community name (so remove ", Alaska" and " city" and " CDP")
      3. Remove Region.
      4. Replace place_name with Community.
      5. Export the Population 1991-2050 tab into population.csv.

### Source File
  * Description: UAA's ISER community-level projections.
  * Filename: Consolidated Population ISER 01262016.xlsx
  * Date: 01/26/2016
  * Contact Name: Neil McMahon
  * Organization Name: Alaska Energy Authority/Alaska Industrial Development and Export Authority
  * Contact Email: NMcMahon@aidea.org
  * Delivery Method: Basecamp (Alaska Affordable Energy Model Project)
