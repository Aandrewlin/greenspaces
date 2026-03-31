# greenspaces
Data Analysis and Visualisation project. March 2026.

Hello and welcome to my first data analysis project! I used data from the City of Toronto's Open Data Portal and the QGIS software to create two choropleth maps. The first map shows the amount of green spaces in each Toronto census subdivision. The second map shows the percent of green space coverage, also in each Toronto census subdivision. According to Open Data Toronto (2026), green spaces include, but are not limited to: public parks, beaches, parts of ravines, golf courses and cemeteries.

I began this project at the March 26 datathon jointly hosted by the Yorku Data Science Club, Yorku Library Data Services and Toronto Open Data. During the event, I tried a few tools like Tableau and Geopandas, but it didn't go smoothly. Afterwards, a librarian suggested that I use a Geographic Information System (GIS) tool, which made sense since we were working with map data after all. The following is the result. 

![Toronto Subdivisions Green Spaces Count.png](https://github.com/Aandrewlin/greenspaces/blob/eb212a33ffa30d7a5d3513cb4d1149e0e1de4e1f/Toronto%20Subdivisions%20Green%20Spaces%20Count.png)

![Toronto Subdivisions Green Spaces Coverage Percentage.png](https://github.com/Aandrewlin/greenspaces/blob/54271dee22f87f3320677e13eae0fb85c10ec00d/Toronto%20Subdivisions%20Green%20Spaces%20Coverage%20Percentage.png)

## Summary Statistics
We consider summary statistics, keeping in mind there are 140 subdivisions in total.

Top 5 subdivisions with the **highest number** of green spaces:
1. Rouge, at 254
2. Waterfront Communities - The Island, at 101
3. West Humber-Clairville, at 84
4. Birchcliffe-Cliffside, at 78
5. Islington-City Centre West, at 74

Top 6 (due to tie) subdivisions with the **lowest number** of green spaces:
1. Danforth, at 3
1. Runnymede-Bloor West Village, at 3
1. Maple Leaf, at 3
2. Corso Italia-Davenport, at 4
2. North St.James Town, at 4
2. Blake-Jones, at 4

Top 5 subdivisions with the **highest square meterage** of green space:
1. Rogue, at about 23,861,826 square meters
2. West Hill, at about 4,980,551 square meters
3. Woburn, at about 4,432,331 square meters
4. Banbury-Don Mills, at about 4,070,451 square meters
5. West Humber-Clairville, at about 3,910,539 square meters

Top 5 subdivisions with the **lowest square meterage** of green space:
1. Runnymede-Bloor West Village, at about 11,014 square meters
2. Danforth, at about 11,394 square meters
3. North St.James Town, at about 14,915 square meters
4. University, at about 17,759 square meters
5. Little Portugal, at about 23,498 square meters

Top 5 subdivisions with the **highest coverage** of green space:
1. Flemingdon Park, at about 100% 
2. Playter Estates-Danforth, at about 91%
3. Old East York, at about 88%
4. Elms-Old Rexdale, at about 78%
5. Woodbine-Lumsden, at about 77%

Top 5 subdivisions with the **lowest coverage** of green space:
1. Runnymede-Bloor West Village, at about 0.7%
2. Danforth, at about 1%
3. University, at about 1.3%
4. Little Portugal, at about 1.9%
5. (Ironically) Oakwood Village, at about 2.5%

### 5-number summary for coverage
Min.: about 0.7% 
1st quartile: about 8% 
Median: about 16% 
3rd quartile: about 35% 
Max.: about 100% 

Standard deviation: about 21%

IQR: about 26.743% 
Upper bound: about 74.675% 
Amount of outliers: 6. These are the top 5 subdivisions with the highest coverage mentioned above, plus the Taylor-Massey subdivision which has about 76% green space coverage.

