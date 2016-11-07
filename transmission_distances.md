## transmission_distances.md

### Responsible Party
  * Organization Name: Geographic Information Network of Alaska (GINA)
  * Email: support+aaem@gina.alaska.edu

### Data Lineage
  * Data File: transmission_distances.md
  * Description: Information on nearest viable community for adding an intertie
    * First line: Header
    * Column Name [units] (Column Description)
      * community [unitless] ()
      * Maximum savings ($/kWh) [$/kWh] (savvings possible with intertie)
      * Nearest Community with Lower Price Power [unitless] (community name)
      * Distance to Community [miles] ()
  * Processing Steps
    1. export 'intertie distace data' tab from source file as csv.
    2. add 'community' as column 1 header

### Source File
  * Description: Infromation on each communities nearest neighbor for intertie purposes
  * Filename: transmission_distances 09212016.csv
  * Date: 07/25/2016
  * Contact Name: Neil McMahon
  * Organization Name: Alaska Energy Authority/Alaska Industrial Development and Export Authority
  * Contact Email: NMcMahon@aidea.org
  * Delivery Method: FILL_IN
  * Origin: Distances between every two communities in Alaska was calculated using a distance formula based on the latitude and longitude of each community. The communities that were within thirty miles were compared for the difference in retail electricity costs. The community that had the lowest relative cost, or was the regional hub, was chosen. 
