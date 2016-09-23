## wind_class_cf_assumptions.md

### Responsible Party
  * Organization Name: Geographic Information Network of Alaska (GINA)
  * Email: support+aaem@gina.alaska.edu

### Data Lineage
  * Data File: wind_class_cf_assumptions.csv
  * Description: assumptions for wind class
    * First line: Header
    * Column Name [units] (Column Description)
      * Wind Class [unitless] ()
      * 30 m Wind Speed [mph] (wind speed at 30 meters)
      * 50 m Wind Speed [mph] (wind speed at 50 meters)
      * REF V-VI Net CF [percent] (percent of theroretical capacity usable)
  * Processing Steps
    1. copy wind assumptions table from source file
    2. remove % signs from data
    3. add 0 to class 1

### Source File
  * Description: Manley Hot Springs Model Draft.  The Diesel Fuel Prices tabs contain the relevant information.
  * Filename: DRAFT Project Evaluation Tool--Manley Hot Springs 01262016.xlsm
  * Date: 01/26/2016
  * Contact Name: Contact Name: Neil McMahon
  * Organization Name: Alaska Energy Authority/Alaska Industrial Development and Export Authority
  * Contact Email: NMcMahon@aidea.org
  * Delivery Method: Basecamp (Alaska Affordable Energy Model Project)

