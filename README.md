# Surfs_Up Project Analysis 

## Analysis Overview 

This is an analysis of a Waves and Ice Cream startup company. This company is about to open a surf shop in Oau Island in Hawaii. The company is concerned regarding the surf shop's financial sustainability during the whole year. The financial sustainability would be dependent on what the weather is like year-round. To determine the weather statistics year-round, we are analyzing the June and December weather. 

## Resources 

- [x] Jupyter Notebook
- [x] Python (including numpy, pandas, sqlalcemy, etc. dependencies)
- [x] sqlite 

## Analysis Results 

### Findings regarding June and December temperature

By filtering the date column of the Measurements table in the hawaii.sqlite database we retreived all the temperature data for the months of June and December. Then we converted that data into lists and databased for June and December. After that we have generated summary statistics for the June and December datasets. The screenshot for the temperature for the month of June is below:

![june_temp](https://github.com/TamaraGR/surfs_up/blob/main/june_temp.jpg)

And here is the screenshot for the temperature for the month of December:

![dec_temp](https://github.com/TamaraGR/surfs_up/blob/main/dec_temp.jpg)

The descriptive statistics for both of the months are below as well: 

![june_temp_desc](https://github.com/TamaraGR/surfs_up/blob/main/june_temp_desc.jpg)

![dec_temp_desc](https://github.com/TamaraGR/surfs_up/blob/main/dec_temp_desc.jpg)

The comparative analysis of the two months' temperature data is the following:

- [x] We have 12 % more temperature data points for the month June in comparison to the month of December. 
- [x] Maximum month of June temperature is only 2 degress warmer than for the month of December (85 versus 83). 
- [x] Average month of June temperature only about 4 degrees warmer than the one for the month of December (74.9 versus 71). 

### Additional findings regarding June and December temperature 


