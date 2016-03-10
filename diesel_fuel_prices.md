## diesel_fuel_prices.md

### Responsible Party
  * Organization Name: Geographic Information Network of Alaska (GINA)
  * Email: support+aaem@gina.alaska.edu

### Data Lineage
  * Data File: diesel_fuel_prices.csv
  * Description: FILL_IN
    * First line: Header
    * Column Name [units] (Column Name)
      * ID [unitless] (ID, not certain of origin)
      * "Rural (0) Urban (1)" [unitless] (flag for rural or urban community)
      * Utility [unitless] (community utility)
      * Community Name [unitless] ()
      * Years (year) [2015 - 2076]
  * Processing Steps
    1. Export Diesel Fuel Prices tab from source file. Make sure to have enough digits & dollar signs removed.
    2. Remove all headers but the one that begins with ID. Make sure the ID column is all on one line (not split between Rural (0) and Urban(1)).

### Source File
  * Description: Manley Hot Springs Model Draft.  The Diesel Fuel Prices tabs contain the relevant information.
  * Filename: DRAFT Project Evaluation Tool--Manley Hot Springs 10282015.xlsm
  * Date: 10/28/2015
  * Contact Name: Contact Name: Neil McMahon
  * Organization Name: Alaska Energy Authority/Alaska Industrial Development and Export Authority
  * Contact Email: NMcMahon@aidea.org
  * Delivery Method: Basecamp (Alaska Affordable Energy Model Project)
