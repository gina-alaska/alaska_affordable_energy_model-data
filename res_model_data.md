## res_model_data.md

### Responsible Party
  * Organization Name: Geographic Information Network of Alaska (GINA)
  * Email: support+aaem@gina.alaska.edu

### Data Lineage
  * Data File: res_model_data.csv
  * Description: Data for residential buildings in the communites
    * First line: Header
    * Column Name [units] (Column Name)
      * Community [None] ()
      * Energy Region [None] ()
      * Year [None] ()
      * Total Occupied [None] (total # of houses occupied)
      * BEES Number [None] (# houses that meet BEES (Alaska Building Energy Efficiency Standard))
      * BEES Avg Area (SF) [Square Feet] (average square feet of BEES houses)
      * BEES Avg EUI (MMBtu/sf) [MMBTU/Sqft/yr] (average EUI (energy use intensity) of bees houses)
      * BEES Total Consumption (MMBtu) [MMBTU/yr] (total BEES consumption per year)
      * Pre-Retrofit Number [None] (# of houses not retofitted)
      * Pre-Retrofit Avg Area (SF) [Square Feet] (average sqare feet of not retofitted houses)
      * Pre-Retrofit Avg EUI (MMBtu/sf) [MMBTU/Sqft/yr] (average EUI (energy use intensity) of not retrofitted houses)
      * Post-Retrofit Number [None] (number of refitted houses)
      * Post-Retrofit Avg Area (SF) [Square Feet] (average square footage of retrofitted houses)
      * Post-Retrofit Avg. EUI Reduction [MMBTU/Sqft/yr] (average EUI reduction)
      * Post-Retrofit Avg EUI (MMBtu/sf) [MMBTU/Sqft/yr] (Average EUI)
      * Total Consumption (MMBtu) [MMBTU/yr] (retrofitted consumption)
      * Notes [None] ()
  * Processing Steps
    1. changed the header lines
      * upadted columns to match list above

### Source File
  * Description: Residential Model Output
  * Filename: res model 09192016.xlsx
  * Date: 2016-09-16
  * Contact Name: Neil McMahon
  * Organization Name: Alaska Energy Authority/Alaska Industrial Development and Export Authority
  * Contact Email: NMcMahon@aidea.org
  * Delivery Method: Basecamp (Alaska Affordable Energy Model Project)
  * Origin:
    1. Total occupied is from the 2010 US Census.
    2. Data was extracted and cleaned from the Alaska Retrofit Information System. The data was separated into two categories: BEES and Weatherization/Home Energy Rebate. 
    3. For the BEES entries, the total number of BEES compliant residences per community, the average square footage and the average Energy Use Index (EUI) were determined. The BEES total consumption was found for each community using these values.
    4. The Weatherization/Home Energy Rebate entries were divided into pre- and post-retrofit categories. With no other data to cross-check against, the pre-retrofit category was assumed to mirror the average characteristics of the housing stock in a community or region. The pre-retrofit average square footage and average EUI was computed for each community and region. 
    5. The post-retrofit average area and average EUI was calculated by community. The total post-retrofit consumption was calculated by community. 
    6. For each entry that had a pre- and post-retrofit entry, the EUI reduction was determined. The EUI reductions were averaged at the community and regional levels. 
    7. Statistical analysis was performed to determine if the data available for each community was statistically significant. Specifically, the pre-retrofit average square footage, average EUI, and post-retrofit average EUI reduction were checked for statistical significance.  If the values were not statistically signficant, the regional average was used. The data was then cleaned to fix any logically inconsistent results.
