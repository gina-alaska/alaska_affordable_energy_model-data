## biomass_resource_data.md

### Responsible Party
  * Organization Name: Geographic Information Network of Alaska (GINA)
  * Email: support+aaem@gina.alaska.edu

### Data Lineage
  * Data File: biomass_resource_data.csv
  * Description: biomass data
    * First line: Header
    * Column Name [units] (Column Description)
      * Community Name [Unitless] ()
      * Sufficient Biomass for 30% of Non-residential buildings [Unitless] (yes or no)
      * Existing project (Y,N) [Unitless] ()
      * Productive Forest (H,M,L) [Unitless] ()
      * Phase [Unitless] ()
      * Certainty [Unitless] ()
      * On Road/SE [Unitless] ()
      * Proposed Capacity (MMBtu/hr) [mmbtu/hr] ()
      * Proposed Heating Oil Displaced [gal] ()
      * Estimated Capital Cost [$]
      * Estimated Operation Cost [$]
      * Source of Data [Unitless] ()
      * Heating Reference Community [Unitless] (community used as reference)
      * Distance to Heating Reference Community [miles] ()
      * Peak Month % of total [Unitless] ()
      * Capacity Factor [Unitless] ()

  * Processing Steps
    1. rename source file to biomass_resource_data.csv

### Source File
  * Description:  Biomass resoure data.
  * Filename: biomass resource data new.csv
  * Date: 2017/03/09
  * Contact Name: Contact Name: Neil McMahon
  * Organization Name: Alaska Energy Authority/Alaska Industrial Development and Export Authority
  * Contact Email: NMcMahon@aidea.org
  * Delivery Method: Basecamp (Alaska Affordable Energy Model Project)
  * Origin: 
    1. Sufficient Biomass for 30% of Non-residential buildings [Unitless] (yes or no)--AEA analysis of AEDI woody biomass GIS data.  A five mile circumference was made around each community.  The sum of the tons of woody biomass was found using the values of the pixels in the five-mile radius.  The tons of woody biomass was converted to MMBtu and an equivalent amount of gallons of diesel.  It was assumed that 1% of the wood could be harvested per year.  The harvestable value was then compared against an estimate of 30% of the non-residential heat load for the community.  If the harvestable value was equal or greater than the applicable community load, it was labed as having sufficient biomass.  
    2. On road/SE--used Google Earth/Wikipedia
    3. Heating reference community--AEA used a distance function to find nearest community with applicable weather data
    4. Peak mont % of total: based on analysis from ashp_climate_data
    5. Capacity factor: [not used, I think]
