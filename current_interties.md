## current_interties.md

### Responsible Party
  * Organization Name: Geographic Information Network of Alaska (GINA)
  * Email: support+aaem@gina.alaska.edu

### Data Lineage
  * Data File: current_interties.csv
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
      * Other Community on Intertie [unitless] (child community)
      * Other Community on Intertie [unitless] (child community)
      * Other Community on Intertie [unitless] (child community)
      * Other Community on Intertie [unitless] (child community)
      * Other Community on Intertie [unitless] (child community)
      * Other Community on Intertie [unitless] (child community)
      * Other Community on Intertie [unitless] (child community)
      * Other Community on Intertie [unitless] (child community)
      * Other Community on Intertie [unitless] (child community)
  * Processing Steps
    1. Export Interties tab in source file to current_interties.csv.
    2. Remove Napaskiak from Bethel intertie.
    3. Remove double entry for Unalaska.
    4. Add New Allakaket to intertie with Allakaket and Alatna.
    5. Remove communities that do not work with current model.
      - Ketchikan,Yes,Petersburg,Wrangell,Saxman,Kupreanof,,,#Loring
      - Saint Mary's,Yes,Pitkas Point,,,,,,#Andreafsky
      - +#Skagway,Yes,Haines,,,,,,
      - Glennallen,Yes,Gakona,Gulkana,Copper Center,Kenny Lake,Mendeltna,Tazlina,#Sheep Mountain
    6. update Glennallen (copper valley) intertie (2015-04-21)
      - added Nelchina, Silver Springs, Tolsona, Tonsina, Copperville, Nabesna, Nelchina, Willow Creek
      - added header columns to support theses in prerpocessor
    7. update Glennallen (copper valley) intertie (2015-04-24)
      - commented out Copperville, Nabesna, Willow Creek
      - Added Valdez, Commented out all of the seperate entry for Valdez
    8. updated Hains intertie (2015-04-28)
      - added Skagway
    9. changed Alakanuk 'Community Name with power generation' to yes
    10. added Whale Pass and Naukati Bay to craig, commented out their individual lines
    
### Source File
  * Description: List of intertied communities, identifying the community with the power generation and the other communities on the intertie. Neil McMahon suggests this data can be cross-checked  against the power house data in the energy statistics
  * Filename: Intertie Communities.xlsx
  * Date: 11/06/2015
  * Contact Name: Neil McMahon
  * Organization Name: Alaska Energy Authority/Alaska Industrial Development and Export Authority
  * Contact Email: NMcMahon@aidea.org
  * Delivery Method: Basecamp (Alaska Affordable Energy Model Project)
  * Origin: Data from AEDG, personal communication with AEA personnel, and utility websites.
