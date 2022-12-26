CIAN - Real Estate price prediction

https://www.cian.ru/ - a largest Russian real estate portal with rich functionality. Cian group with is offering a new approach to the process of purchasing real estate with the aim to provide a one-stop services platform. Company offer a vast variety of services and cooperate with real estate agencies, insurance companies, banks and the real estate developers. 

In 2020 Cian Group in partnership with 1Cbit Russia has launched a project to develop an online real estate evaluation service in order to enrich cian.ru functionality and became a #1 Russian real estate portal.
The evaluation is based on weightened importance factors for data taken from different sources:
1. Data based on online ads
2. Building information (municipal data)
3. Geospatial data (lon,lat of real estate object)
4. Infrastructure information (municipal data)
5. Real estate sold price data (aggregated from real estate agencies)

The most valuable and accurate data is #5, which I used for my Machine Learning project. The other data sources were also used to adjust the estimation model and for other services which are not described here.
The dataset is original real estate sales data in Russia for the period from 2018-2021 gathered from CIAN partner's real estate agencies across the country. The dataset is already cleaned and contain 5_477_006 records and 13 features.

date - date of publication of the announcement;
time - the time when the ad was published;
geo_lat - Latitude
geo_lon - Longitude
region - Region of Russia. There are 85 subjects in the country in total.
building_type - Facade type. 0 - Other. 1 - Panel. 2 - Monolithic. 3 - Brick. 4 - Blocky. 5 - Wooden
object_type - Apartment type. 1 - Secondary real estate market; 2 - New building;
level - Apartment floor
levels - Number of storeys
rooms - the number of living rooms. If the value is "-1", then it means "studio apartment"
area - the total area of the apartment
kitchen_area - Kitchen area
price - Price. in rubles
