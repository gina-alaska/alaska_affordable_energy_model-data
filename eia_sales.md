## eia_sales.md

### Responsible Party
  * Organization Name: Geographic Information Network of Alaska (GINA)
  * Email: support+aaem@gina.alaska.edu

### Data Lineage
  * Data File: eia_sales.csv
  * Description: Provides electric sales information for Alaska communities. This file is used if data is not available from the PCE data files.  
    * First line: Header
    * Column Name [units] (Column Name)
      * Data Year [unitless] ()
      * Utility Number [unitless] ()
      * Community [unitless] ()
      * Utility Name [unitless] ()
      * Ownership [unitless] ()
      * Residential Thousand Dollars [$] (revenue)
      * Residential Megawatthours [MWh] (sales)
      * Residential Count [# Customers] (customers)
      * Commercial Thousand Dollars [$] (revenue)
      * Commercial Megawatthours [MWh] (sales)
      * Commercial Count [# Customers] (customers)
      * Industrial Thousand Dollars [$] (revenue)
      * Industrial Megawatthours [MWh] (sales)
      * Industrial Count [# Customers] (customers)
      * Total Thousand Dollars [$] (revenue)
      * Total Megawatthours [MWh] (sales)
      * Total CustomerCount [# Customers] (customers)
  * Processing Steps
    1. Export the Sales (861 2003-2014) tab to eia_sales.csv.
    2. Remove all headers except the column labels.

### Source File
  * Description: Energy Information Administration (EIA) data for 2003 - 2014. This file contains final 2003 data.  During the year, the EIA-906 and EIA-920 surveys collect monthly data from a sample of approximately 1800 generating plants.   After the end of the calendar year, data are collected from the approximately 3300 out-of-sample plants.  The annual responses are proportionately distributed over the months using the ratio of collected monthly data to the sum of that monthly data.  These data are shown below with plant-specific names and plant numbers.  Estimates for nonresponses are rolled-into state/fuel aggregates with a “99999” plant code.  For additional information, see the documentation file on page 3 of this workbook.
  * Filename: EIA consolidated 923 861.xlsx
  * Date: 10/28/2015
  * Contact Name: Neil McMahon
  * Organization Name: Alaska Energy Authority/Alaska Industrial Development and Export Authority
  * Contact Email: NMcMahon@aidea.org
  * Delivery Method: Basecamp (Alaska Affordable Energy Model Project)
