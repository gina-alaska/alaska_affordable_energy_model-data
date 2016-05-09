## res_model_data.md

### Responsible Party
  * Organization Name: Geographic Information Network of Alaska (GINA)
  * Email: support+aaem@gina.alaska.edu

### Data Lineage
  * Data File: res_model_data.csv
  * Description: Data for residential buildings in the communites
    * First line: Header
    * Column Name [units] (Column Name)
      * community [None] ()
      * energy_region [None] ()
      * year [None] ()
      * total_occupied [None] (total # of houses occupied)
      * BEES_number [None] (# houses that meet BEES (Alaska Building Energy Efficiency Standard))
      * BEES_avg_area [Square Feet] (average square feet of BEES houses)
      * BEES_avg_EUI [MMBTU/Sqft/yr] (average EUI (energy use intensity) of bees houses)
      * BEES_total_consumption [MMBTU/yr] (total BEES consumption per year)
      * pre_number [None] (# of houses not retofitted)
      * pre_avg_area [Square Feet] (average sqare feet of not retofitted houses)
      * pre_avg_EUI [MMBTU/Sqft/yr] (average EUI (energy use intensity) of not retrofitted houses)
      * post_number [None] (number of refitted houses)
      * post_avg_area [Square Feet] (average square footage of retrofitted houses)
      * post_avg_EUI_reduction [MMBTU/Sqft/yr] (average EUI reduction)
      * post_avg_EUI [MMBTU/Sqft/yr] (Average EUI)
      * post_total_consumption [MMBTU/yr] (retrofitted consumption)
      * Notes [None] ()
  * Processing Steps
    1. changed the header lines
      * commented out the original header lines
      * added header row with new column names
    2. added the year column

### Source File
  * Description: Residential Model Output
  * Filename: Residential Model Output 05032016.xlsx
  * Date: 2016-05-03
  * Contact Name: Neil McMahon
  * Organization Name: Alaska Energy Authority/Alaska Industrial Development and Export Authority
  * Contact Email: NMcMahon@aidea.org
  * Delivery Method: Basecamp (Alaska Affordable Energy Model Project)
