## heating_fuel_premium.md

### Responsible Party
  * Organization Name: Geographic Information Network of Alaska (GINA)
  * Email: support+aaem@gina.alaska.edu

### Data Lineage
  * Data File: heating_fuel_premium.csv
  * Description: The heating fuel premium is added to the price of diesel fuel in a community to compute the final fuel cost.
    * First line: Header
    * Column Name [units] (Column Name)
      * region [unitless] (Alaska energy regions)
      * premium [$] (heating fuel price premium for region)
  * Processing Steps
    1. Copy from source file Assumptions tab into a two-column file (region,premium) called heating_fuel_premium.csv

### Source File
  * Description: Manley Hot Springs Model Draft.  The Assumptions tab contains needed information. Heating Fuel Price Adder for Alaska regions: Based on average of 2011-2013 PCE Diesel and AHFC/DCRA Heating Oil (Neil McMahon)
  * Filename: DRAFT Project Evaluation Tool--Manley Hot Springs 11022015.xlsm
  * Date: 11/02/2015
  * Contact Name: Neil McMahon
  * Organization Name: Alaska Energy Authority/Alaska Industrial Development and Export Authority
  * Contact Email: NMcMahon@aidea.org
  * Delivery Method: Basecamp (Alaska Affordable Energy Model Project)
  * Origin: Raw data for the price per gallon for utility diesel and retail heating oil was accessed from the Alaska Energy Data Gateway in June 2015.  Reported price for utility diesel and retail heating oil was compiled per community per year.  The difference between these values was averaged per year per AEA energy region.  These yearly differences were averaged to calculate the regional heating fuel price adder.  

