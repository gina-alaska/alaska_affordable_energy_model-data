## interties.md

### Responsible Party
  * Organization Name: Geographic Information Network of Alaska (GINA)
  * Email: support+aaem@gina.alaska.edu

### Data Lineage
  * Data File: interties.csv
  * Description: List of intertied communities, identifying the community with the power generation and the other communities on the intertie.
    * First line: Header
    * Column Name [units] (Column Name)
      * Community Name with power generation [unitless] (parent community)
      * Plant Intertied [unitless] (yes/no)
      * Other Community on Intertie [unitless] (child community)
      * Other Community on Intertie [unitless] (child community)
      * Other Community on Intertie [unitless] (child community)
      * Other Community on Intertie [unitless] (child community)
      * Other Community on Intertie [unitless] (child community)
      * Other Community on Intertie [unitless] (child community)
      * Other Community on Intertie [unitless] (child community)
  * Processing Steps
    1. Export Interties tab in source file to interties.csv.
    2. Remove Napaskiak from Bethel intertie.
    3. Remove communities that do not work with current model.
      - Ketchikan,Yes,Petersburg,Wrangell,Saxman,Kupreanof,,,#Loring
      - Saint Mary's,Yes,Pitkas Point,,,,,,#Andreafsky
      - +#Skagway,Yes,Haines,,,,,,

### Source File
  * Description: List of intertied communities, identifying the community with the power generation and the other communities on the intertie. Neil McMahon suggests this data can be cross-checked  against the power house data in the energy statistics
  * Filename: Intertie Communities.xlsx
  * Date: 11/06/2015
  * Contact Name: Neil McMahon
  * Organization Name: Alaska Energy Authority/Alaska Industrial Development and Export Authority
  * Contact Email: NMcMahon@aidea.org
  * Delivery Method: Basecamp (Alaska Affordable Energy Model Project)