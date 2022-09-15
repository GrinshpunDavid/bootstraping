## Project description:
OilyGiant mining company need a model that will find the best place for a new well.

### Goal:
Suggest a region for development of oil wells and justify the choice.

### Data description:
- Geological exploration data for the three regions (GEO-1, GEO-2, GEO-3)
- oil well id
- f0, f1, f2 - three features of points
- volume of reserves in the oil well (thousand barrels)

### Steps performed:
- Collect the oil well parameters in the selected region: oil quality and volume of reserves.
- Build a model for predicting the volume of reserves in the new wells.
- Pick the oil wells with the highest estimated values.
- Pick the region with the highest total profit for the selected oil wells.
- Build a model that will help to pick the region with the highest profit margin using Bootstrapping.

### Results:
- GEO-1 have the highest average oil reserves chosen by our models.
- GEO-1 is the only region that have positive revenue in its lower bootstrapping 2.5% quantile hence the lowest loss risk.
