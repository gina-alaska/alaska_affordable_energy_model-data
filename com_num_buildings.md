## com_num_buildings.md

### Responsible Party
  * Organization Name: Geographic Information Network of Alaska (GINA)
  * Email: support+aaem@gina.alaska.edu

### Data Lineage
  * Data File: com_num_buildings.csv
  * Description: Contains estimated number of buildings for Alaskan communities.
    * First line: Header
    * Column Name [units] (Column Name)
      * Community [unitless] ()
      * Buildings [number of buildings] (estimated)
  * Processing Steps
    1. Rename Community\ building\ estimates.csv to com_num_buildings.csv in the data directory.

### Source File
  * Description: Contains estimated number of buildings for Alaskan communities. The data was acquired from a number of sources.  Actual building counts were collected either through tax assessor records or through an unrelated GIS project by the Alaska Native Tribal Health Consortium.  Using this data, a regression was done against the communities' median household incomes (from the 2010 Census) and the communities' populations. For those communities without an actual non-residential building count, the population and MHI was plugged into the equation to estimate the number of non-residential buildings.
  * Filename: Community\ building\ estimates.csv
  * Date: 02/11/2016
  * Contact Name: Neil McMahon
  * Organization Name: Alaska Energy Authority/Alaska Industrial Development and Export Authority
  * Contact Email: NMcMahon@aidea.org
  * Delivery Method: Basecamp (Alaska Affordable Energy Model Project)