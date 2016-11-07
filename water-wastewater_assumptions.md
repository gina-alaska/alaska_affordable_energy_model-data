## water-wastewater_assumptions.md

### Responsible Party
  * Organization Name: Geographic Information Network of Alaska (GINA)
  * Email: support+aaem@gina.alaska.edu

### Data Lineage
  * Data File: Relates the energy/heating consumption of water and waste water systems to both the population and the heating degree days.
  * Description: water-wastewater_assumptions.csv
    * First line: Header
    * Column Name [units] (Column Name)
      * system type [unitless] (choices are: Circulating/Gravity, Circulating/Vacuum, Haul, Pressure/Gravity,Washeteria/Honey Bucket)
      * HDD kWh [kWh/heating degree day (F)] (required kiloWatt-hours per heating degree day)
      * HDD HF [kWh/heating degree day (F)] (required gallons of fuel per heating degree day)
      * pop kWh [kWh/person] (required kiloWatt-hours per person)
      * pop HF [gallons/person] (required gallons of fuel per person)
  * Processing Steps
    1. Create a new file water-wastewater_assumptions.csv.
    2. Using method of choice, rearrange the data to reflect the column definition above (1st line is a header containing column titles, 2nd line to the end contains the data). Make sure to export 10 decimals places.
      * header: "system type,HDD kWh,HDD HF,pop kWh,pop HF"
      * example (2nd line): "Circulating/Gravity,8.21176678517469,0.629599405815875,32.1503755648685,1.33444201080967"

### Source File
  * Description: Relates the energy/heating consumption of water and waste water systems to both the population and the heating degree days.  The source file contains multiple tabs with data that comprises the estimates in the Model Output tab.
  * Filename: W&WW Model Estimates.xlsx
  * Date: 11/28/2015
  * Contact Name: Neil McMahon
  * Organization Name: Alaska Energy Authority/Alaska Industrial Development and Export Authority
  * Contact Email: NMcMahon@aidea.org
  * Delivery Method: Basecamp (Alaska Affordable Energy Model Project)
  * Origin: Assumptions are derived from data for specific water and wastewater systems in Alaska by system type. The data, available through the water_wastewater_projects_potential, was analyzed using Excel's Regression data analytics tool to develop regression for the kWh and heating oil consumption based on the community's population and climate (using heating degree days as the quantitative measure).
