# Sea Level Rise and New York City
*Original proposal: https://github.com/jjbasinger/up206a_groupproject/blob/main/Group%20Assignments/Project%20Proposal.md?plain=1*

## Roles
- Jacob: data cleaning and mapping
- Lucia: data charting

## Status Update
Our mood is good because we were able to incorporate both temporal census data and sea level rise data into our project up to this point.  While we have not found much correlation between projected flooding due to climate change and population changes, we are optimistic about our project because we have accomplished much of what we set out to do.

## Data Update
We have finalized our data for the census and sea level rise information.

**Sea Level Rise Data**
  - Description: We obtained sea level rise data from the NYC OpenData portal. Instead of utilizing mean high tide data, which only shows a few inches of rise and would not be very informative in a map of the entire city, we decided to use flood projections for various levels of storms (which also incorporate the rises in mean high tide). We chose to use 100 year flood and 500 year flood data because Hurricane Sandy was a 260 year storm (https://www.businessinsider.com/another-hurricane-sandy-flood-risk-hit-new-york-2016-10), therefore these visualizations will show flood events that are similar. We chose to use the 2020 projections instead of 2050s or 2100s because it is temporally sooner, and we believe people may be more likely to respond to situations that they feel are more imminent.
  - Source: NYC OpenData, https://data.cityofnewyork.us/browse?q=sea+level+rise

**Census Data**
  - Description: The NYC OpenData portal has an excel file available that contains the 2010 and 2020 census population data, as well as columns with the population change information already calculated. I combined this data with census tract geographies, also obtained from the NYC OpenData portal, then joined them into a workable geojson.
  - Source: NYC OpenData, https://www1.nyc.gov/site/planning/data-maps/open-data.page#waterfront

## Concerns
- Locating usable housing market/financial data. I am worried that it will be in too large of a file to utilize.
- Working concurrently in the group repository is causing merge issues, it makes it difficult to work collaboratively.
