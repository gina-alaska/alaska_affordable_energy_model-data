## non_res_buildings.md

### Responsible Party
  * Organization Name: Geographic Information Network of Alaska (GINA)
  * Email: support+aaem@gina.alaska.edu

### Data Lineage
  * Data File: non_res_buildings.md
  * Description: Inventory of buildings by community.  Significant classification is building type (the AAEM model has set classifications).
    * First line: Header
    * Column Name [units] (Column Name)
      * City [unitless] ()
      * GNIS [unitless] (Geographic Names Information System ID)
      * Physical Address [unitless] ()
      * Data Source [unitless] ()
      * Building [unitless] ()
      * Building Type [unitless] ()
      * Square Feet [square feet] ()
      * Audited [unitless] ()
      * Audit Notes [unitless] ()
      * Retrofits Done [unitless] ()
      * Retrofit Notes [unitless] ()
      * Fuel Oil [gallons/year] (fuel oil 1 and 2)
      * HW District [gallons/year] (district heating in heating oil equivalent)
      * Electric [kWh/year] [ccf/year] ()
      * Natural Gas [gallons/year] ()
      * Propane [gallons/year] ()
      * Biomass [cords/year] ()
      * Fuel Oil Post [gallons/year] (fuel oil 1 and 2, post retrofit)
      * HW District Post [gallons/year] (district heating in heating oil equivalent)
      * Electric Post [kWh/year] [ccf/year] ()
      * Natural Gas Post [gallons/year] ()
      * Propane Post [gallons/year] ()
      * Biomass Post [cords/year] ()
      * implementation cost [$] ()
  * Processing Steps
    1. Export to non_res_buildings.csv.
    2. Rename Columns 
      * Be sure to use the columns as identified in this file, replacing the original columns where needed.  Naming is important in running the AAEM model.
    3. Remove last two cloumns
    4. Relpace '#Ref?' and '#name!' with ''
    5. Relpace remaining '#' characters with '--'
    

### Source File
  * Description: Building inventory as determined by AEA (via many methods)
  * Filename: Compiled nonresidential buildings 07212016.xlsx
  * Date: 07/27/2016
  * Contact Name: Neil McMahon
  * Organization Name: Alaska Energy Authority/Alaska Industrial Development and Export Authority
  * Contact Email: NMcMahon@aidea.org
  * Delivery Method: Basecamp (Alaska Affordable Energy Model Project)
