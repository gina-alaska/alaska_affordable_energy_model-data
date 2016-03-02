## cpi.md

### Responsible Party
  * Organization Name: Geographic Information Network of Alaska (GINA)
  * Email: support+aaem@gina.alaska.edu

### Data Lineage
  * Data File: cpi.csv
  * Description: Consumer Price Index multiplier to convert dollars in one time period to the real value (adjusted for inflation) in another time period.
    * First line: Header
    * Column Name [units] (Column Description)
      * year [year] (2015 - 2075)
      * CPI multiplier [unitless] ()
  * Processing Steps
    1. Open the Fuel Price Worksheet tab in the source file.
    2. Export or save contents tab to cpi.csv in data directory.
    3. Remove all data EXCEPT year (row 6) and CPI multiplier in unlabeled row 23 (G23:BO23).  
    4. Using copy/paste/transpose, create two columns in cpi.csv containing year and CPI multiplier. Add headers for each column, "year" and "CPI multiplier".  Keep only years 2015 - 2075. Final file is a two-column spreadsheet containing year and CPI multiplier from 2015 - 2075.
    5. Save cpi.csv in spreadsheet app again.

### Source File
  * Description: Excel spreadsheet (containing many tabs) to model energy use in Manley Hot Springs. Relevant information in Fuel Price Worksheet tab. Updated July 2014 (Alejandra Villalobos Meléndez, ISER Research Associate) Crude Oil Forecast, Energy Information Administration, Annual Energy Outlook 2
  014
  * Filename: DRAFT Project Evaluation Tool--Manley Hot Springs 10282015.xlsm
  * Date: 10/29/2015
  * Contact Name: Neil McMahon
  * Organization Name: Alaska Energy Authority/Alaska Industrial Development and Export Authority
  * Contact Email: NMcMahon@aidea.org
  * Delivery Method: Basecamp (Alaska Affordable Energy Model Project)
