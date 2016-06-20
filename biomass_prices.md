## biomass_prices.md

### Responsible Party
  * Organization Name: Geographic Information Network of Alaska (GINA)
  * Email: support+aaem@gina.alaska.edu

### Data Lineage
  * Data File: biomass_prices.csv
  * Description: Current (2016) cost of biomass (cords/pellet) in Alaska communities.
    * First line: Header
    * Column Name [units] (Column Name)
      * Community [unitless] ()
      * Region [unitless] ()
      * Biomass ($/Cord) [$/Cord] (cordwood price)
      * Pellets ($/ton) [$/Ton] (pellet price)
      * Source [unitless] (Source of biomass price data)
  * Processing Steps
    1. Export the 4 columns from the source file into biomass_price_estimates.csv
    2. Note: Kodiak and Aleutian region do not have data.  Listed as 'N/A' in column.

### Source File
  * Description: biomass prices for pellet and cordwood
  * Filename: Biomass Price Data for model 06162016.xlsx
  * Date: 06/16/2016
  * Contact Name: Neil McMahon
  * Organization Name: Alaska Energy Authority/Alaska Industrial Development and Export Authority
  * Contact Email: NMcMahon@aidea.org
  * Delivery Method: Basecamp (Alaska Affordable Energy Model Project)
