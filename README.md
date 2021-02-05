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
- [x] Minimum temperature for the month of JUne is 8 degrees higher than for the month of December (64 versus 56)

### Additional findings regarding June and December temperature 

The percipitation summaries for the months of June and December are below: 

![june_prcp](https://github.com/TamaraGR/surfs_up/blob/main/june_prcp.jpg)

![dec_prcp](https://github.com/TamaraGR/surfs_up/blob/main/dec_prcp.jpg)

The descriptive statistics for the precipiation for the months of June and December are below: 

![june_prcp_desc](https://github.com/TamaraGR/surfs_up/blob/main/june_prcp_desc.jpg)

![dec_prcp_desc](https://github.com/TamaraGR/surfs_up/blob/main/dec_prcp_desc.jpg)

The comparative analysis of the two months' precipitation data is the following:

- [x] Just like with the temperature points, there are 12% more precipitation points for the month of JUne than the month of December. 
- [x] Average precipitation for the month of June is 0.14, while for the month of December it is 022 (0.08 difference)
- [x] MAximum precipitation for the month of June is 4.43, and for the month of December 6.42 (2 difference). 
- [x] Minimum precipitation is the same, at 0.



