## purchased_power_lib.md

### Responsible Party
  * Organization Name: Geographic Information Network of Alaska (GINA)
  * Email: support+aaem@gina.alaska.edu

### Data Lineage
  * Data File: purchased_power_lib.csv
  * Description: Energy source as a function of community and utility company.
    * First line: Header
    * Column Name [units] (Column Name)
      * community_names [unitless] (Name of community (ies) as recorded in the U.S. Census that reported that year to the Alaska Energy Authority to receive Power Cost Equalization payment. Variable name in AEA's PCE NAVISION system: Posting Description.)
      * purchased_from [unitless] (Utility or independent power producer (IPP) name from which kilowatt-hours were purchased. Variable name in AEA's PCE NAVISION system: Purchased From.)
      * Energy Source [unitless] (Identifies type of fuel used to generate purchased power)
  * Processing Steps
    1. The first thing to do is to just run the model with the new PCE data in the power-cost-equalization-pce-data.csv and see what is missing from the purchased_power_lib.csv file (warnings are obtained from preprocessor diagnostics file that say "Utility XYZ not found in utility-power source lib not using as provider" )
    2. Update the purchased_power_lib.csv file as needed.
    3. To create the purchased_power_lib.csv file from the beginning
      * Copy source file to temporary spreadsheet, probably easiest to manipulate a spreadsheet.
      * Add a new column at the end, "Energy Source"
      * Remove blank entries, duplicate entries.
        * The challenge here - each utility has many many spellings of its name.
      * Add the energy source using seed data from the previous "purchased_power_lib_12-30-2015.csv"; not all new energy source data will be available in this file so some investigating may be required (ask Neil McMahon for assistance)
      * Export from source file to purchased_power_lib.csv.
    4. NOTE: These manual steps could be built into a python script; request made to AEDG to provide this type of file directly.

### Source File(s)
  * Description: Data downloaded from the Alaska Energy Data Gateway on 03/11/2016. From the AEDG PCE data, export the community name and purchased from fields into own spreadsheet.  
  * Filename: power-cost-equalization-pce-community_names-purchased_from-2016-03-11.xlsx
  * Date: 03/11/2016
  * Contact Name: N/A
  * Organization Name: Alaska Energy Data Gateway (https://akenergygateway.alaska.edu/)
  * Contact Email: N/A
  * Delivery Method: Download from AEDG Data Search Tools on 03/11/2016 @ 2:37 PM
