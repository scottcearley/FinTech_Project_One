# Impacts of the Pandemic on Phoenix Housing

<img align="middle" width="900" height="500" src="https://api.time.com/wp-content/uploads/2022/04/GettyImages-1292752655.jpg?quality=85&w=1200&h=628&crop=1">

## Running the Main Analysis Notebook 
You must download the following packages in order to run the Main Analysis Notebook: 

<span style="color:white;font-weight:100;font-size:15px">
    <b>Altair Data Visualization Package:</b>
</span>

    pip install altair 
    conda install -c conda-forge altair
    import altair as alt 

<span style="color:white;font-weight:100;font-size:15px">
    <b>Holo Views (hvPlot) Visualization Package:</b>
</span>

    pip install hvplot
    conda install -c pyviz hvplot
    import hvplot.pandas 

<span style="color:white;font-weight:100;font-size:15px">
    <b>RISE Jupyter Slideshow Extension:</b>
</span>

    (To view the main analysis notebook in slideshow format, download the following)
    pip install RISE
    conda install -c conda-forge rise

## Summary
Being interested in the housing market from a personal perspective, our team decided to seek out answers to a few questions about the Phoenix housing market:
​
1.  Did the Pandemic have an effect on the availability of housing (in the owner and rental markets)?
2.  Did the Pandemic affect housing prices?
3.  Did the Pandemic usher in institutional investors thereby displacing homes for rent by individual homeowners?
​
## Visual 1:  Phoenix market
​
Visual:  most recent 600 properties sold in the Phoenix and Glendale areas:
https://github.com/Mun-Min/Project_One/blob/main/Visuals%20PNG/phoenix_housing_property__type_listings_map..png
​
- Observations:  As is to be expected, single family homes are the predominant residential properties being listed and sold.
- The average price of single residential homes is $440,000 based on the most recent sampling.
- Data extraction & cleaning:  The data underlying this graphic was the one of the more difficult data sets that we acquired and cleaned.  It required creating a dataframe via iteration from a data-intensive JSON file.
​
## Visual 2 and 3:  Heat map of Phoenix housing and rental market 
​
https://github.com/Mun-Min/Project_One/blob/main/Visuals%20PNG/phoenix_housing_property_listings_heat_map..png
https://github.com/Mun-Min/Project_One/blob/main/Visuals%20PNG/phoenix_rental_property_listings_heat_map..png

- Heatmaps convey the state of the current housing & rental market. 
- Legend for the heat maps - the larger the circle, the more square footage for the property. The darker the circle, the more expensive the property.
​
​
## Visual 3 and 4: All homes for sale on the market
​<https://github.com/Mun-Min/Project_One/blob/main/Visuals%20PNG/all_home_sales_2019_2022..png>

- Note, the peak of inventory was in Sept 2019, falling shortly to a low in June 2020, which was 3 months after the pandemic was declared by WHO.  The inventory of houses on the market currently is approximately half of all houses available in 2019.


- This graphic brings up a few questions:

    - Is this due to slower housing starts?

    - More people working from home?

    - The home inventory is shrinking, but yet 200 people a day are still moving to Phoenix area.

## Visual 5: Price per square foot for solds in the market 
https://github.com/Mun-Min/Project_One/blob/main/Visuals%20PNG/price_per_square_foot_by_year..png

- March 2020 $178/sf

- Dec 2020 $200/sf

- April 2021 $225/sf

- Jan 2022 $263/sf

- May 2022 $293/sf
​
## Visual 6:  Investor purchases of rentals vs. total rentals
​<https://github.com/Mun-Min/Project_One/blob/main/Visuals%20PNG/total_sales_and_investor_purchases.png>

- During the times of the pandemic and afterwards, the ratio of investor purchases seemed to be in line and parellel with owner-occupant purchases month in and month out.

## Conclusion
- Immediately following the pandemic declaration, housing prices rose sharply while looking at price per sq ft, the population continues to increase, yet housing inventory keeps declining, and finally, data indicates that investors are not coming in and buying all the inventory despite what we hear in the news, owner occupant and investor purchases are at the same ratio, before and after the pandemic.