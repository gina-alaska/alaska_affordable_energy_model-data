## heatin_degree_days.md

### Responsible Party
  * Organization Name: Geographic Information Network of Alaska (GINA)
  * Email: support+aaem@gina.alaska.edu

### Data Lineage
  * Data File: heatin_degree_days.csv
  * Description: Contains heating degree days per year for Alaskan communities.
    * First line: Header
    * Column Name [units] (column description)
      * Community [unitless] (Alaska communities)
      * HDD in ARIS equations [Degree Fahrenheit/year] (heating degree days per year)
  * Processing Steps
    1. Convert AkWarm_dd_changes.xlsx to heatin_degree_days.csv
      * Description: Export columns b and f as community, and HDD in ARIS equation. Remove # formating
    2. ensure correct spelling of community: Nunam Iqua(was Numum Iqua)

### Source File
  * Description: Excel spreadsheet containing heating degree days per year for Alaskan communities.
  * Filename: AkWarm_dd_changes.xlsx
  * Date: 02/23/2016
  * Contact Name: Neil McMahon
  * Organization Name: Alaska Energy Authority/Alaska Industrial Development and Export Authority
  * Contact Email: NMcMahon@aidea.org
  * Delivery Method: Basecamp (Alaska Affordable Energy Model Project)
  * Origin: Alaska Retrofit Information System
