## res_fuel_source.md

### Responsible Party
  * Organization Name: Geographic Information Network of Alaska (GINA)
  * Email: support+aaem@gina.alaska.edu

### Data Lineage
  * Data File: res_fuel_source.csv
  * Description: Estimated residential fuels by community
    * First line: Header
    * Column Name [units] (Column Name)
      * Community Name [unitless] ()
      * Borough/Census Area [unitless] ()
      * Total [unitless] (Estimated)
      * Error Total [unitless] (Margin of Error)
      * Utility Gas [unitless] (Estimated)
      * Error Utility gas  [unitless] (Margin of Error)
      * LP [unitless] (Estimated bottled, take, or LP gas)
      * Error LP  [unitless] (Margin of Error)
      * Electricity [unitless] (Estimated)
      * Error Electricity  [unitless] (Margin of Error)
      * Fuel Oil [unitless] (Estimated fuel oil, kerosene, etc.)
      * Error Fuel Oil [unitless] (Margin of Error)
      * Coal [unitless] (Estimated coal or coke)
      * Error Coal [unitless] (Margin of Error)
      * Wood [unitless] (Estimated)
      * Error Wood [unitless] (Margin of Error)
      * Solar [unitless] (Estimated ESolar)
      * Error Solar [unitless] (Margin of Error)
      * Other [unitless] (Estimated other fuels)
      * Error Other [unitless] (Margin of Error)
      * No fuel used
  * Processing Steps
    1. Export Res Fuel Use Data to model to res_fuel_source.csv file. Remember to export enough digits. Export as FRACTIONS, not percents (100% -> 1.0)
    2. Remove header line 2013 ACS data (B25040) so that the only header is the column definition

### Source File
  * Description: 2013 Five-year American Community Survey (B24050). The data is gathered at the Census Tract for each Borough, Municipality, or Census Area. Notes from Neil McMahon, "I've updated the assumption for heating fuel used in the North Slope Borough--attached.  The model had used an average over the entire borough, which was dominated by Barrow's and Nuiqsut's natural gas supplies.  I've modified it to assume Barrow and Nuiqsut as the nearly 100% utility gas and used Northwest Arctic Borough's numbers as a proxy for the rest of the North Slope borough. There's now an anomalous amount of firewood, but it's probably as good as it can be without making up numbers to fit..."
  * Filename: ACS Fuel Census Tract.xlsx
  * Date: 02/11/2016
  * Contact Name: Neil McMahon
  * Organization Name: Alaska Energy Authority/Alaska Industrial Development and Export Authority
  * Contact Email: NMcMahon@aidea.org
  * Delivery Method: Basecamp (Alaska Affordable Energy Model Project)
