## wind_projects_potential.md

### Responsible Party
  * Organization Name: Geographic Information Network of Alaska (GINA)
  * Email: support+aaem@gina.alaska.edu

### Data Lineage
  * Data File: wind_projects_potential.csv
  * Description: data for existing wind projects
    * First line: Header
    * Column Name [units] (Column Description)
      * Community [unitless] ()
      * Wind class to Model (within 1 mile) [unitless] ()
      * High Turbulence (Y/N) [unitless] ()
      * Phase* Proposed Capacity (kW) [kW] ()
      * Proposed Generation (kWh) [kWh] ()
      * Distance to Resource (ft) [ft] ()
      * Generation Capital Cost [$] ()
      * Transmission CAPEX [$] ()
      * Operational Costs / year [$/yr] ()
      * Expected years to operation [years] ()
      * Identified Reason for not pursuing project [unitless] ()
      * Data Source (report reference) [unitless] 
      * Project Name [unitless] ()
      * Lat/Long (decimal degrees) [] ()
  * Processing Steps
    1. exported first tab of Wind Model 06152016.xlsx to wind_projects_potential.csv
    2. fixed spelling of operational
    3. remove leading/trailing whitespace in column names
    4. remove number formatting
    5. replace bad values (-$, -) with 0

### Source File
  * Description: wind project data
  * Filename: wind_projects_potential - revised.csv
  * Date: 2016/06/16
  * Contact Name: Neil McMahon
  * Organization Name: Alaska Energy Authority/Alaska Industrial Development and Export Authority
  * Contact Email: NMcMahon@aidea.org
  * Delivery Method: 
