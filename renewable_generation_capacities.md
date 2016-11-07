## renewable_generation_capacities.md

### Responsible Party
  * Organization Name: Geographic Information Network of Alaska (GINA)
  * Email: support+aaem@gina.alaska.edu

### Data Lineage
  * Data File: renewable_generation_capacities.csv
  * Description: upper bounds on the kWh genereation for RE sources in communities
    * First line: Header
    * Column Name [units] (Column Name)
      * Community [unitless] 
      * Project Name [unitless]
      * Resource Type [unitless]
      * Resource Sub-type [unitless]
      * Capacity (kW) [kW]
      * Average Annual Generation (kWh) [kWh]
  * Processing Steps
    1. export RE Capacity For Model tab of 'RE Capacity For Model.xlsx'
    2. rename 'row labels' column to 'community'

### Source File
  * Description: list of RE (wind and/or hydro) generation capacities for given communities
  * Filename: RE Capacity For Model.xlsx
  * Date: 2016-04-13
  * Contact Name: Neil McMahon
  * Organization Name: Alaska Energy Authority/Alaska Industrial Development and Export Authority
  * Contact Email: NMcMahon@aidea.org
  * Delivery Method: Basecamp (Alaska Affordable Energy Model Project)
  * Data from Alaska Energy Authority databases for wind and hydro generation capacities, not otherwise publicly available.
