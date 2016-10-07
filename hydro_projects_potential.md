## hydro_projects_potential.md

### Responsible Party
  * Organization Name: Geographic Information Network of Alaska (GINA)
  * Email: support+aaem@gina.alaska.edu

### Data Lineage
  * Data File: hydro_projects_potential.csv
  * Description: data for various hydropower projects
    * First line: Header
    * Column Name [units] (Column Description)
      * Community/Power Line [Unitless] ()
      * Region [Unitless] ()
      * Project [Unitless] ()
      * Stream [Unitless] ()
      * Distance [miles] ()
      * Location [Unitless] ()
      * Transmission Cost (current) [$] ()
      * Transmission Cost Source [Unitless] ()
      * Construction Cost (2014$) [$] ()
      * Construction Cost Source [Unitless] ()
      * Total Construction Cost [$] ()
      * AAEM Capacity (kW) [kW] ()
      * AAEM Capacity Source [Unitless] ()
      * AAEM Generation (kWh) [kWh] ()
      * Generation Source [Unitless] ()
      * Capacity Factor [] ()
      * Phase Completed [Unitless] ()
      * LAT [Decimal Degrees] ()
      * LON [Decimal Degrees] ()
      * USACE siteGroup [Unitless] ()
  * Processing Steps
    1. rename source to hydro_projects_potential.csv
    2. remove _intertie from communty names

### Source File
  * Description: data for various hydropower projects
  * Filename: hydro_projects 09192016s.csv
  * Date: 2016-09-19
  * Contact Name: Neil McMahon
  * Organization Name: Alaska Energy Authority/Alaska Industrial Development and Export Authority
  * Contact Email: NMcMahon@aidea.org
  * Delivery Method: FILL_IN
  * origin: Data was compiled from 
    1. United State Army Corps of Engineers spreadsheet compiled for the Alaska Energy Authority in 2013. The spreadsheet "Alaska_hydropower_Master_Table_20Dec13" was sorted for those projects that had been determined by the USACE to be most likely to be feasible.  Data fields collected from the spreadsheet were maintained, although scrubbing of the data was required to remove inconsistent and/or illogical values.  
    For missing values, regional values were estimated using the USACE data.  The values reported in this file are either from a report or modeled based on the estimates within the USACE spreadsheet and accompanying report.
    2. AEA personnel collected the applicable data from Renewable Energy Fund pre-construction projects.   
    
