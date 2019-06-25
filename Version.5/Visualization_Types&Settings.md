

<center><h2>VISUALIZATION TYPES & SETTINGS</h2></center>

 Visualization provides an opportunity to view the data obtained in analysis report into different pictorial representation along with some standard editing options. Based on the priority, to view specific information about the data retrieved. Each type of visualization charts have different setting which can be customized for its appearance. 
 
 ***Types of visualization charts in Acubi;***
 - Line
 - Horizontal Bar
 - Pie
 - Radar
 - Widget
 - World
 - Bar
 - Bubble
 - Table 
 - Funnel
 - Gauge

> **Note :** Some of the options in editing list might be hidden or grayed in situations where they would conflict with other settings you have chosen.

## Line 

 Emphasize the overall shape of an entire series of values, usually over time.
 
 **1.** Choose Chart Type **Line** from the drop down list.

![
](https://github.com/sv18042016/fp1/blob/caf436cec9dfaf0afd3065d99bee59072050e1d8/images/New_version5/UD_Visualization_Types&Settings_Image1.png?raw=true)
**Image 1**

 ***Editing Options for Line Chart***
 
 - **Line type** displays the information as a series of data points called markers. Below are the list of markers used in line chart (spline acts as  default line type), 
   - Line
   - Spline 
   - Step
   - Area
   - Area-Spline
   - Area-Step
   - Scatter
    
- **Points**  will display the data by specifying the points on the chart.

- **Point style** will specify how the data points will appear on chart. 
Below are the following options available. 
  - Circle
  - Triangle
  - Rectangle
  - RectRot
  - Cross
  - CrossRot
  - Star
  - Line
  - Dash

## Horizontal Bar 

Horizontal Bar charts are used to compare data across different categories. You can build a bar chart by placing a dimension on the Column area and a measure on row.

 **2.** Choose Chart type **Horizontal Bar** from the drop down list to compare the data in Horizontal Bar chart.
 
![
](https://raw.githubusercontent.com/sv18042016/fp1/1a322f67a5166b6fe77c00678ff264b7ac59252d/images/New_version5/UD_Visualization_Types&Settings_Image2.png)
**Image 2**
## Pie Chart 

PIE chart are divided into slices to provide the numerical proportion of the data.
 
 **3.**  Choose Chart Type **Pie** from the drop down list.
 
 ![
](https://raw.githubusercontent.com/sv18042016/fp1/e1868ae74d5d6d0289d45b6fa2bc71a9302ad97f/images/New_version5/UD_Visualization_Types&Settings_Image3.png)
**Image 3**
### Editing Options in Pie Chart
 
- **Show percentage**  displays percentage for each measure value in pie chart. To enable it select the **Check Box** show percentage as shown below;

![
](https://raw.githubusercontent.com/sv18042016/fp1/9efd7408868fc3755257f26138885e2ca684e1d0/images/New_version5/UD_Visualization_Types&Settings_Image4.png)
**Image 4**

- **Polar Area** On selecting the checkbox polar area, it enables the polar view for each dimensions in pie chart.

-  **Donut** chart are equal to pie chart. They show relationships of parts to a whole. 
- Select checkbox to enable Donut view.

![
](https://raw.githubusercontent.com/sv18042016/fp1/3ba1953c960af32db0af345fbb40776d222ee54e/images/New_version5/UD_Visualization_Types&Settings_Image5.png)
**Image 5**

## Radar chart 

 Radar charts are a great way to compare members of a dimension in a function of several metrics.  
 
**Example:** when you want to buy a Laptop, you can use a radar chart to compare several devices across several metrics like battery life, memory, hard drive etc.  

 **4.** Choose chart type **Radar** from drop down list.

![
](https://raw.githubusercontent.com/sv18042016/fp1/751eed2fc28d82c24e883a2d567d5f389919b172/images/New_version5/UD_Visualization_Types&Settings_Image6.png)
**Image 6**

- **Points** on selecting the checkbox it enables pointers for the data range in line chart.

- **Point style** will specify how the data points will appear on chart. below are the following options are available. 
  - Circle
  - Triangle
  - Rectangle
  - RectRot
  - Cross
  - CrossRot
  - Star
  - Line
  - Dash
  
- **Reverse scale** on selecting the checkbox, it display the reversal side of data displayed in radar chart i.e. if the 10 highest values are shown in radar chart ,on selecting the checkbox, then it will display 10 lowest values.

- **Show ticklabels** on selecting this checkbox, it enables measure values on y-axis.

- **Show arc lines** on selecting this checkbox, it points the dimension fields in radar chart.

- **Arc field** select the dimension field to apply arc lines.

- **Curve** it maximize and minimize the surface area in radar chart.

## Widget chart 

It displays one or more data series as a data graph. Widget chart is used to display the number of records created today and Number of Incidents by status or department.

 **5.** Choose **Widget** from drop-down list, it displays total number of data record in widget chart.
 
![
](https://raw.githubusercontent.com/sv18042016/fp1/ac06f66008071fe929798b3d8ee36e5bd5cd89bf/images/New_version5/UD_Visualization_Types&Settings_Image7.png)
**Image 7**

 **Value** select the field value (measure field) to display in the widget. This specify the measure field if you have multiple measure value defined in the underlying step.

- **Format** select the number format for the measure field.

- **Previous value** select the alternative measure field, to calculate the difference of growth in widget.

- **Change** specify the conditions for selected measures such as difference, growth, none.

- **Show growth** displays the growth rate of selected measures.

- **Title** specify widget title.

- **Label** specify the widget label.

- **Style** specify a status indicator for measure value such as default, primary, success, warning, info, danger.

- **Theme** Data alignment in widget chart.

- **Widget Icon** Choose a icon to symbolize widget value. 

- **Background Colour** Select appropriate background colour for widget chart.

##  World chart 

 It displays the data grouped by specific country and at the same time highlights the grouped data regions in the map.
 
**6.** Choose chart type **World** from drop down list. 

 > **Note :** The values you want to define in world chart should be defined in model section initially to display them here. 

![
](https://raw.githubusercontent.com/sv18042016/fp1/b4d06a116e6f5919fd87b2e6d003a889f0f2f0fd/images/New_version5/UD_Visualization_Types&Settings_Image8.png)
 **Image 8**

- **Title** specify a title for world map.

- **Flat Map** displays a flat view or "2D" vision of the map.

- **Default** set default colour to display specific countries.

- **Over Border** colour the border of a map region.

- **Data Field** choose the data field to display it on map.	

- **Tip Fields** select numbers of data fields to be displayed on map.

- **Colour Field** specifies which field to be coloured.

- **Colour From & To** specify the colour specific range of values in map region.

- **Negative Cutoff** enabled when negatives values are applicable.

- **Negative colour-from & to** Specify colour for specific range of negative values.

## Bar Chart

Bar charts are used to compare data across different categories. Bar chart is built by placing a dimension on a row and measure on a column area.

**7.** Choose chart type **Bar** from drop down list, under general section.

![
](https://raw.githubusercontent.com/sv18042016/fp1/06087da8a8df002e219ac38e88404ea9603f4d7c/images/New_version5/UD_Visualization_Types&Settings_Image9.png)
**Image 9**

## Bubble chart 

Bubble Chart displays the data in circles. We can define each bubble using any of our Dimension value and its size by Measure value.
 
 **8.** Choose Chart Type **Bubble** under **General** section  to compare the data in Bubble chart.
 ![
](https://raw.githubusercontent.com/sv18042016/fp1/427b27184df7c745300ef1169318ae6427ae1e56/images/New_version5/UD_Visualization_Types&Settings_Image10.png)
**Image 10**

## Table chart 
 
Table chart displays the data in series making it more feasible for comparing dimensions and measure values.
 
 **9.** Choose chart type **Table** under **General** section to compare data in table chart.
 
![
](https://raw.githubusercontent.com/sv18042016/fp1/7e9db7322511f370a3f088a614821da70ec05e0f/images/New_version5/UD_Visualization_Types&Settings_Image11.png)
**Image 11**

### Hide Pivot (Calculated Column)

To hide the first or last column field values in Table Chart, Select hide first or hide last check box in Data section of visualization.
To carry out this function you need to derive an expression in calculated column first.  
Select Stationcode, Quantity_sum and Whenmade_month, Apply pivot to Stationcode.

**For Instance** :  derive the following expression in calculated column first;

```
pivot_offset(#{ROOT.BI_ORDERS.sum_QUANTITY} ,0,-1)
```
![
](https://raw.githubusercontent.com/sv18042016/fp1/488ee6156d0f40eb8566b427b08347106977e416/images/New_version5/UD_Visualization_Types&Settings_Image12.png)
**Image 12**

The resultant for this expression would be seen in green colour;

![
](https://raw.githubusercontent.com/sv18042016/fp1/4bd9045b7b3b1dceac68eb20c87579d484fd0c4e/images/New_version5/UD_Visualization_Types&Settings_Image13.png)
**Image 13**

In the above image you can see, for pivot_hide 1st column is seen empty, to hide this select checkbox **pivot hide first** in **Data Section** of visualisation. Similarly to hide the last column, select checkbox for Hide_last in data section of table chart.

> **Note :**  Applicable only for table chart. 

![
](https://raw.githubusercontent.com/sv18042016/fp1/e749e7c96af56390cc3fb80fd0d1a7d17fd0bf2c/images/New_version5/UD_Visualization_Types&Settings_Image14.png)
**Image 14**
## Funnel chart 

Funnels helps to visualize a process that has stages and items flow sequentially from stage one to next. Use a funnel when there is a sequential flow between stages, For Instance a sales process, that starts with inquiry and ends with billing.

**The following section describes the editing option for Funnel chart in Charts;**
 
 **9.** Choose chart type **Funnel** under **General** section  to compare the data in Funnel chart.
 
![
](https://raw.githubusercontent.com/sv18042016/fp1/84af193f1ebf383092d92fc256ec7041495cca5a/images/New_version5/UD_Visualization_Types&Settings_Image15.png)
**Image 15**

***Funnel charts can be viewed in following ways;***

 - **Sort** on selecting this check box, it enables data in the sorted order in funnel chart.
  
 - **Curved** on selecting this check box it will display, funnel chart in curved view.
 
 - **Pinched** on selecting this check box it will display, compressed view of the funnel chart.
  
 - **Inverted** on selecting this check box it will display, funnel chart in reversed or bottom up position.
 
 - **Highlight on Hover**  on selecting this check box it will highlight each section by placing a cursor on it.
 
 - **Dynamic Height** on selecting this check box it will display the height depending on the numeric range of the data retrieved in funnel chart. 
 
 - **Dynamic Slope** on selecting this checkbox it will display the potential covered based on the value range.

**For instance:** higher value is referred with bigger slope and lower value is referred with smaller slope.

 - **Load Animation** on selecting this check box the column values in funnel chart will appear as moving image.


##  Gauge Chart 

Gauge chart displays current status in the context of goal.

 
 **10.** Choose chart type **Gauge** from drop down list under **General** section  to compare the data in Gauge chart.

- **Green** colour in gauge chart indicates the value attained is closer to target.

![
](https://raw.githubusercontent.com/sv18042016/fp1/63e6ce82315ae4e72a287d4437b7d7a4bcea940b/images/New_version5/UD_Visualization_Types&Settings_Image16.png)
**Image 16**

- **Orange** colour indicates, maximum value attained is half the way to target.
-  **Red** colour indicates, maximum value attained is at initial state or lower side to the target. 

![
](https://github.com/sv18042016/fp1/blob/3ff08da67be44bb345a23a3e47e19f4ab62a4553/images/New_version5/UD_Visualization_Types&Settings_Image17.png?raw=true)
**Image 17**

- **Value** select one of the available measure values from the drop down.

- **Min** specifies the minimum value of the gauge this corresponds to bottom position of the gauge.

- **Max**  specifies the maximum value of the gauge this corresponds to top position of the gauge.

- **Title** specify a title.

- **Label** specify a identifier name to display in the chart.

- **Donut** displays total measure value.

- **Counter** displays minimum and maximum values of the measure.

- **Reverse** displays the measure values in reversal direction maximum to minimum.

- **Hide Minmax**  hides min and maximum values in gauge target.


## Standard Settings

### General Section 

- **Title** specify title for the chart selected.

- **Position** align title to top,bottom,left,right position.

- **Label** Specify label text.

- **Padding** specifies spacing at the top, bottom, left and right side of the charts.

- **Tooltips** points the first measure value of the column field.

- **Grouped Tooltips** points all the measure values of the column field.

- **Show legend** on selecting this checkbox, it displays the measures fields used at the bottom of the chart, you can display or hide specific measure field values on chart by clicking on the measure field.

- **Position** Align the legend at top,bottom,left and right side of the chart.

### X-Axis Menu Options

- **Axis type** specifies how x-axis scale for Line, Bar, Bubble is calculated and displayed.

  - **Indexed** specifies the data to be plotted in numeric values starting from zero on x-axis.
   
  - **Category** specifies the data to be plotted as category group on x-axis.
  
  - **Timeseries** specify the data to be plotted as time values. The x-axis is labeled with appropriate time increments.
 
- **Label field**  specify a dimension field to be displayed on X-axis.

- **Show Grid** enables the grid display for dimension fields on x-axis.

- **Axis label** Text label for x-axis.

**Reference Lines** enables the creation of reference lines in a chart.

 - **Reference** specify a indicator name. 
  
 - **Type** specify reference type as line or  area.
  
 -  **From & to** specify the reference line for specific range of dimensions.

 - **Theme** enables colour for reference line.
 
 > **Note:**  X-Axis is enabled only for Line, Bar and Bubble chart only.

### Y-Axis

- **Axis** select the measures values on y-axis  to enable
editing options for y-axis in Line, for Bar and bubble chart.

- **Axis label** Text label for x-axis.

- **Format** it enables number format for numeric values.

- **Currency** Using this field, you can specify the formatting for currency as of now Acubi supports $,   ₹  ,   €  ,  £.

- **Y-Axis** display measure values on Y-axis. 

- **Show Grid** enables the grid display for measures on y-axis.

- **Include Zero** displays measure values starting from zero.

- **Position** you can align the y-axis to left or right side of the chart.

**Reference Lines** enables the creation of reference lines in a chart.

- **Name** specify a reference name for specific information on y-axis.
  
 - **Type** specify  Linear, Polynomial, Exponential, Logarithmic, Average, Median, Minimum, Maximum, Deviation, Variance, Custom Line, Custom Area on Y-axis.
  
 -  **From & to** specify the reference line for specific range of measure values.

 - **Theme** enables colour for reference line.
 
 > **Note:**  Y-Axis is enabled only for Line, Bar and Bubble chart only.
 
## Format   
      
- **Condition** Specify any of the following condition types Greater than, Less than, Between, Not Between, equal to, duplicates values, Top 10 Items, Bottom 10 Items, Above Average, Below Average for the fields.

- **Format on** Specify a measure field on which you want to apply format.

- **Value** Specify a value to measure the condition.

- **BG (background colour)** Select the background colour for the data which is retrieved using condition.

- **Font** Select the font colour for the data retrieved based on condition.

- **Icon** Select a icon for the data retrieved based on condition.

- **Before number** Align the icon before the data value.


**For Example :** Consider below image, which displays the format section for table chart.

![
](https://raw.githubusercontent.com/sv18042016/fp1/5d83f06c9740cedd36829d2db56c97b5aac224f5/images/New_version5/UD_Visualization_Types&Settings_Image18.png)
**Image 18**
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTQ1OTA4MzA4NSw1NzIyNTkyMjQsLTIxND
E4MTM0LDczODE3Mzc5OCwxNDMyNDg1MjY4LDEyOTA4ODU4NTMs
LTE3ODEwNjYzNTIsMTI4OTk4MjcwMCwxMTc0MzAwOTYwLDkzOT
I2Mjk5OCw0MDAzNzkwNTIsLTQzNzE0MzU4LC0xMTU1NzYzODEw
LDE5ODIyMjU4NDAsLTExMzM0NzUzMzIsMTQ1OTkwODQyMiwtNT
k3OTU2NTk5LC0xNTc5NjMwMDU1LDEyNTA3ODcyNzEsLTE2NjU0
OTg1NjJdfQ==
-->