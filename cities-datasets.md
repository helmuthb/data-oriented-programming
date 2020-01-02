| description | from  | to   | format  | link |
|---|---|---|---|---|
| Crime Index  |  2012 |  2019 | html  | https://www.numbeo.com/crime/rankings.jsp  |
| Cost of Living Index  | na  | current  | html |  https://www.expatistan.com/cost-of-living/index |
| The 48 best cities in the world (Time Out Index survey) | na  |  2019 | html  | https://www.timeout.com/things-to-do/best-cities-in-the-world  |
| World City Populations 2019  | na | 2019  | csv/json  | http://worldpopulationreview.com/world-cities/  |
| **World Urbanization Prospects (Population Dynamics)** | 1950 | 2018 (2030) | xls | https://population.un.org/wup/Download/|
| List of cities or metropolitan areas by GDP | mixed | mixed | html | https://en.wikipedia.org/wiki/List_of_cities_or_metropolitan_areas_by_GDP |
| Cities GDP | mixed  | mixed | html | http://www.worldcitiescultureforum.com/data/gdp-pppmillion |
| **City Regions (population, gdp,...)** | 2001 | 2016 | excel, csv, api | https://stats.oecd.org/Index.aspx?DataSetCode=CITIES |
| Geo Coordinates of World Heritages | current  | current | excel, xml | https://whc.unesco.org/en/syndication |
| Creative Cities | current  | current | pdf | https://en.unesco.org/creative-cities/sites/creative-cities/files/16_pages_villes_creatives_uk_bd.pdf |
| City Prosperity Index | mixed  | 2016  | excel | http://urbandata.unhabitat.org/download-raw-data |
| Mercer Index (Quality of Living Survey) | 2010, 2012, 2014, 2015, 2016 | 2018, 2019 | html | https://en.wikipedia.org/wiki/Mercer_Quality_of_Living_Survey |
| Tripindex | | 2013| jpg(!) | https://www.tripadvisor.com/InfoCenter-a_ctr.TripIndex__5F__Cities__5F__2013__5F__US |
| Innovation Cities™ Index 2019 : Global| | current | html | https://www.innovation-cities.com/index-2019-global-city-rankings/18842/ |
| Global Cities' AI Readiness Index |  | current | html | https://www.oliverwymanforum.com/city-readiness/global-cities-ai-readiness-index-2019.html |
| **Global Power City Index (GPCI)** | 2008-2017 | 2018, 2019 | pdf | http://www.mori-m-foundation.or.jp/english/ius2/gpci2/index.shtml |
| **Cost of living in cities around the world** | | 2018 | html, xlsx | https://www.ubs.com/microsites/prices-earnings/en/explore/?split=false |
| Green area per capita (square meters per capita) |2000 | 2014 | xls | https://data.humdata.org/dataset/green-area-per-capita-square-meters-per-capita |
| % of public green space (parks and gardens) | mixed | mixed | html, csv | http://www.worldcitiescultureforum.com/data/of-public-green-space-parks-and-gardens |
| **Sustainable Cities Mobility Index** | | 2017| pdf | https://www.arcadis.com/en/global/our-perspectives/sustainable-cities-mobility-index-2017/?utm_source=PR&utm_medium=10302017&utm_campaign=SCMI2017&utm_content=global |
| Google Trends Explore | | current | csv | https://trends.google.com/trends/explore?q=beatles |
| openaq: Fighting air inequality through open data and community (no vienna, no up-to-date daily csv) | ? | 2019 | csv (e.g. `curl -o openaq-2019-01-01.csv https://openaq-data.s3.amazonaws.com/2019-01-01.csv`), api | https://openaq.org |
| and many more ... | | | | https://toolbox.google.com/datasetsearch/search?query=Global%20city%20index |

ideas:
- gdp datasets contain mixed years! suggestion: "normalize" by adding percentage of change over years of country or region gdp
- similar to earthquakes, new feature: number of cultural heritages (https://whc.unesco.org/en/list/) within the vicinity (e.g. 50 km radius) of the city
- calculate % of green space by taking `Green area per capita (square meters per capita)` and `City Regions (population, gdp,...)`->Metropolitan areas->Geographic->Variables:Metropolitan Area area core land area
- geodata is also contained in `World Urbanization Prospects (Population Dynamics)`
- `Google Trends Explore`->Interest by Region->City->Check Include Low Search Volume Regions



Tabellarische Mercer daten
https://en.wikipedia.org/wiki/Mercer_Quality_of_Living_Survey