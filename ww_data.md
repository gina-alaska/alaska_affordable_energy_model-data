## ww_data.md

### Responsible Party
  * Organization Name: Geographic Information Network of Alaska (GINA)
  * Email: support+aaem@gina.alaska.edu

### Data Lineage
  * Data File: ww_data.csv
  * Description: Description of water and wastewater systems for Alaska communities.  Not every community's information is available.
    * First line: Header
    * Column Name [units] (Column Name)
      * City [unitless] ()
      * System Type [unitless] (in the preprocessor.py data file, there is a sys_map that maps one of the 15 possible systems to one of the 5 systems described in the ww_assumptions file)
      * SQFT [square feet] (square footage of building)
      * HF Used [gallons/year]
      * HF w/Retro [gallons/year] (with retrofit for improving efficiency)
      * kWh/yr [kWh/year]
      * kWh/yr w/ retro [kWh/year] (with retrofit for improving efficiency)
      * Implementation Cost [$]
      * HR gallons [gallons/year] (heat recovery system)
      * Steam District [?] ()
      * HR Installed [TRUE/FALSE] (heat recovery system installed or not)
  * Processing Steps
    1. Export columns A:K from the Water & Sewer Data tab into ww_data.csv. Do not include the W&WW types in columns O:P.
    2. Change HR Installed (Yes,No) to TRUE (when YES) and FALSE (when 0). Modify header to be HR Installed.

### Source File
  * Description: Manley Hot Springs Model Draft.  The Water & Sewer tab contains needed information. Neil McMahon notes "I've included data for heat recovery as a column on w&ww the data page.  There are also more communities with identified system types.  For now, unless we get better info at a later date, I have categorized the 15 or so different w&ww types into the five categories already defined, with an additional category of "N/A"."
  * Filename: DRAFT Project Evaluation Tool--Manley Hot Springs 11172015.xlsm
  * Date: 11/17/2015
  * Contact Name: Neil McMahon
  * Organization Name: Alaska Energy Authority/Alaska Industrial Development and Export Authority
  * Contact Email: NMcMahon@aidea.org
  * Delivery Method: Basecamp (Alaska Affordable Energy Model Project)