## solar_resource_data.md

### Responsible Party
  * Organization Name: Geographic Information Network of Alaska (GINA)
  * Email: support+aaem@gina.alaska.edu

### Data Lineage
  * Data File:
  * Description:  data for solar component
    * First line: Header
    * Column Name [units] (Column Description)
      * Community Name [unitless] ()
      * Nearest Reference Community [unitless] (Name of community data is referenced from)
      * Output per 10kW Solar PV [kWh] (solar output potential)
  * Processing Steps
    1. Export Diesel Data tab from source file. 

### Source File
  * Description: Manley Hot Springs Model Draft.  The Diesel Fuel Prices tabs contain the relevant information.
  * Filename: DRAFT Project Evaluation Tool--Manley Hot Springs 05192016.xlsm
  * Date: 01/26/2016
  * Contact Name: Contact Name: Neil McMahon
  * Organization Name: Alaska Energy Authority/Alaska Industrial Development and Export Authority
  * Contact Email: NMcMahon@aidea.org
  * Delivery Method: Basecamp (Alaska Affordable Energy Model Project)
  * Origin: 
    1. Data was collected by AEA personnel from the National Renewable Energy Laboratory's PVWatts Calculator, available from http://pvwatts.nrel.gov/index.php. If multiple data sources were available for a community, the TMY3 data was chosen. For each of the reference cities available for Alaska, a 10-kW system was modeled on the calculator's base level assumptions. The yearly AC Energy output in kWh was recorded.
    2. To determine the nearest reference community, a distance function was used between every community in Alaska and the reference communities. The reference community with the shortest distance to the community was chosen as the proxy.
