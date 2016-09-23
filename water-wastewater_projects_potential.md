## water-wastewater_projects_potential.md

### Responsible Party
  * Organization Name: Geographic Information Network of Alaska (GINA)
  * Email: support+aaem@gina.alaska.edu

### Data Lineage
  * Data File: water-wastewater_projects_potential.csv
  * Description: Description of water and wastewater systems for Alaska communities.  Not every community's information is available.
    * First line: Header
    * Column Name [units] (Column Name)
      * City [unitless] ()
      * System Type [unitless] (in the preprocessor.py data file, there is a sys_map that maps one of the 15 possible systems to one of the 5 systems described in the ww_assumptions file)
      * SQFT [square feet] (square footage of building)
      * HF Used [gallons/year]
      * HF w/Retro [gallons/year] (with retrofit for improving efficiency)
      * kWh/yr [kWh/year]
      * kWh/yr w/ retro [kWh/year] (with retrofit for improving efficiency)
      * Implementation Cost [$]
      * HR gallons [gallons/year] (heat recovery system)
      * Steam District [?] ()
      * HR Installed [TRUE/FALSE] (heat recovery system installed or not)
      * Biomass [TRUE/FALSE] (is biomass used)
  * Processing Steps
    1. rename file

### Source Files
  * Description: Contains wasterwater and water data for several communities not included in earlier lists.
  * Filename: ww_data 09162016.xlsx
  * Date: 2016/09/16
  * Contact Name: Neil McMahon
  * Organization Name: Alaska Energy Authority/Alaska Industrial Development and Export Authority
  * Contact Email: NMcMahon@aidea.org
  * Delivery Method: Basecamp (Alaska Affordable Energy Model Project)
