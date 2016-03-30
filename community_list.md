## community_list.md

### Responsible Party
  * Organization Name: Geographic Information Network of Alaska (GINA)
  * Email: support+aaem@gina.alaska.edu

### Data Lineage
  * Data File: community_list.csv
  * Description: Complete list of communities to be processed by model.  Each community is assigned a model ID, FIPS ID, and an energy region. Railbelt communities and communities too small (as determined by Neil McMahon) have been removed.
    * First line: Header
    * Column Name [units] (Column Name)
      * Model ID [unitless] (In order 1 to 243)
      * Community [unitless] ()
      * Energy Region [unitless] (standard definitions for Alaska)
      * FIPS [unitless] (Federal Information Processing Code)
  * Processing Steps
    1. Export the AkAES tab into community_list.csv
    2. Add a primary column containing "Model ID".  These IDs are just assigned 1..N(Communities) and do not need to stay consistent as communities may be added or subtracted from this list.
    3. Patch in the FIPS IDs.
    4. Patch in the GNIS IDs.

### Source File
  * Description: Community lists in 3 tabs (non-railbelt communities, communities too small to model, railbelt communities removed)
  * Filename: AkAES community list.xlsx
  * Date: 01/21/2016
  * Contact Name: Neil McMahon
  * Organization Name: Alaska Energy Authority/Alaska Industrial Development and Export Authority
  * Contact Email: NMcMahon@aidea.org
  * Delivery Method: Basecamp (Alaska Affordable Energy Model Project)
