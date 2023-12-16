# 225Project

### Remaining Analysis Tasks
 **However, it's possible we don't have the rest of the december data yet if we analyze the trends per month, we can adjust the 2022 to 2023 rate with predicted amount of EVs to register for december, then make a more accurate prediction of the trend. We can evaluate MAPE and use the MAPE to evaluate** We'll do "years since 2017" for our predictor value
* [ ] plot months in all years, using the average assume that to be the change we expect in december (we must first subtract the december count from 2023)
    * For each month, calculate confidence interval. This is sample with t, we don't have population (in this case, it's every year). (on average with confidence p, month tends to be between this)
    * Then for december, extract mean just the mean. If confidence too low, we can instead look at trend and use its prediction.
* [ ] Create Logarithmic regression on the years and perform MAPE and k=1-cross-validation.
* [ ] Geometric Heatmap using the coords in one of the datasets
* [ ] Map out top brand in all of Washington
* [ ] Map out top brand in each county
* [ ] Cluster prediction using the coords and the brand.
    * Evaluate on the number of k's and use best.

### Datasets
**Main Datasets**
* https://catalog.data.gov/dataset/electric-vehicle-population-size-history-by-county
* https://catalog.data.gov/dataset/electric-vehicle-population-data

**Supplementary Datasets**
* https://eric.clst.org/tech/usgeojson/ (500Ks)

### Supportive Sites
**Programming**
* https://towardsdatascience.com/creating-choropleth-maps-with-pythons-folium-library-cfacfb40f56a
* https://medium.com/analytics-vidhya/create-and-visualize-choropleth-map-with-folium-269d3fd12fa0
* https://towardsdatascience.com/how-to-step-up-your-folium-choropleth-map-skills-17cf6de7c6fe

**Data Analysis**
* https://www.irs.gov/credits-deductions/credits-for-new-clean-vehicles-purchased-in-2023-or-after
* https://www.indeed.com/career-advice/career-development/what-is-mape#:~:text=Calculate%20the%20MAPE&text=Add%20all%20the%20absolute%20percent,final%20result%20is%20the%20MAPE.