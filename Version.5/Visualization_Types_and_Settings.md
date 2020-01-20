

<center><h2>VISUALIZATION TYPES </h2></center>

 Visualization provides an opportunity to view the data obtained in analysis report into different pictorial representation along with some standard editing options. Based on the priority, to view specific information about the data retrieved. Each type of visualization charts have different setting which can be customized for its appearance. 
 
 <b><i>Types of visualization charts in Acubi; </i></b>
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

> <b>Note :</b> Some of the options in editing list might be hidden or grayed in situations where they would conflict with other settings you have chosen.

## Line 

 Emphasize the overall shape of an entire series of values, usually over time.
 
 <b>1.</b> Choose Chart Type <b>Line</b> from the drop down list.

![
](https://github.com/sv18042016/fp1/blob/caf436cec9dfaf0afd3065d99bee59072050e1d8/images/New_version5/UD_Visualization_Types&Settings_Image1.png?raw=true)
  <b><font color = "Black"> Image 1</b>

 <b><i>Editing Options for Line Chart</i></b>
 
 - <b>Line type :</b> Displays the information as a series of data points called markers. Below are the list of markers used in line chart (spline acts as  default line type), 
   - Line
   - Spline 
   - Step
   - Area
   - Area-Spline
   - Area-Step
   - Scatter
    
- <b>Points :</b>  This display the data by specifying the points on the chart.

- <b>Point style :</b> This specify how the data points will appear on chart. 
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

 <b>2.</b>  Choose Chart type <b>Horizontal Bar</b> from the drop down list to compare the data in Horizontal Bar chart.
 
![
](https://raw.githubusercontent.com/sv18042016/fp1/1a322f67a5166b6fe77c00678ff264b7ac59252d/images/New_version5/UD_Visualization_Types&Settings_Image2.png)
  <b><font color = "Black"> Image 2</b>

## Pie Chart 

PIE chart are divided into slices to provide the numerical proportion of the data.
 
 <b>3.</b>  Choose Chart Type <b>Pie</b> from the drop down list.
 
 ![
](https://raw.githubusercontent.com/sv18042016/fp1/e1868ae74d5d6d0289d45b6fa2bc71a9302ad97f/images/New_version5/UD_Visualization_Types&Settings_Image3.png)
  <b><font color = "Black"> Image 3</b>
  
### Editing Options in Pie Chart
 
- <b>Show percentage :</b>  Displays percentage for each measure value in pie chart. To enable it select the <b>Check Box</b> show percentage as shown below;

![
](https://raw.githubusercontent.com/sv18042016/fp1/9efd7408868fc3755257f26138885e2ca684e1d0/images/New_version5/UD_Visualization_Types&Settings_Image4.png)
  <b><font color = "Black"> Image 4</b>

- <b>Polar Area :</b> On selecting the checkbox polar area, it enables the polar view for each dimensions in pie chart.

-  <b>Donut :</b> Chart are equal to pie chart. They show relationships of parts to a whole. 
- Select checkbox to enable Donut view.

![
](https://raw.githubusercontent.com/sv18042016/fp1/3ba1953c960af32db0af345fbb40776d222ee54e/images/New_version5/UD_Visualization_Types&Settings_Image5.png)
  <b><font color = "Black"> Image 5</b>

## Radar chart 

 Radar charts are a great way to compare members of a dimension in a function of several metrics.  
 
<b>Example:</b> While purchasing Laptop, you can make use of radar chart to compare several devices across several metrics like battery life, memory, hard drive etc.  

 <b>4.</b> Choose chart type <b>Radar</b> from drop down list.

![
](https://raw.githubusercontent.com/sv18042016/fp1/751eed2fc28d82c24e883a2d567d5f389919b172/images/New_version5/UD_Visualization_Types&Settings_Image6.png)
  <b><font color = "Black"> Image 6</b>

- <b>Points :</b> On selecting the checkbox it enables pointers for the data range in line chart.

- <b>Point style :</b>This will specify how the data points to appear on chart.
 below are the list of options available. 
  - Circle
  - Triangle
  - Rectangle
  - RectRot
  - Cross
  - CrossRot
  - Star
  - Line
  - Dash
  
- <b>Reverse Scale</b> On selecting the checkbox, it display the reversal side of data displayed in radar chart i.e. if the 10 highest values are shown in radar chart ,on selecting the checkbox, then it will display 10 lowest values.

- <b>Show Tick Labels :</b> On selecting this checkbox, it enables measure values on y-axis.

- <b>Show Arc Lines :</b> On selecting this checkbox, it points the dimension fields in radar chart.

- <b>Arc Field :</b> Select the dimension field to apply arc lines.

- <b>Curve :</b> It maximize and minimize the surface area in radar chart.

## Widget chart 

It displays one or more data series as a data graph. Widget chart is used to display the number of records created today and Number of Incidents by status or department.

 <b>5.</b> Choose <b>Widget</b> from drop-down list, it displays total number of data record in widget chart.
 
![
](https://raw.githubusercontent.com/sv18042016/fp1/ac06f66008071fe929798b3d8ee36e5bd5cd89bf/images/New_version5/UD_Visualization_Types&Settings_Image7.png)
  <b><font color = "Black"> Image 7</b>

 <b>Value :</b> Select the field value (measure field) to display in the widget. This specify the measure field if you have multiple measure value defined in the underlying step.

- <b>Format:</b> Select the number format for the measure field.

- <b>Previous Value:</b> Select the alternative measure field, to calculate the difference of growth in widget.

- <b>Change:</b> Specify the conditions for selected measures such as difference, growth, none.

- <b>Show Growth:</b> Displays the growth rate of selected measures.

- <b>Title:</b> Specify widget title.

- <b>Label:</b> Specify the widget label.

- <b>Style:</b> Specify a status indicator for measure value such as default, primary, success, warning, info, danger.

- <b>Theme:</b> Data alignment in widget chart. Select using drop down list.

- <b>Widget Icon:</b> Choose a icon to symbolize widget value. 

- <b>Background Color:</b> Select appropriate background color for widget chart.

##  World chart 

 It displays the data grouped by specific country and at the same time highlights the grouped data regions in the map.
 
<b>6.</b> Choose chart type <b>World</b> from drop down list. 

 > <b>Note :</b> The field in world chart should be defined in model section initially to display them here. 

![
](https://raw.githubusercontent.com/sv18042016/fp1/b4d06a116e6f5919fd87b2e6d003a889f0f2f0fd/images/New_version5/UD_Visualization_Types&Settings_Image8.png)
  <b><font color = "Black"> Image 8</b>

- <b>Title:</b> Specify a title for world map.

- <b>Flat Map:</b> Displays a flat view or "2D" vision of the map.

- <b>Default</b> Set default color to display specific countries.

- <b>Over Border:</b> Color the border of a map region.

- <b>Data Field:</b> Choose the data field to display it on map.	

- <b>Tip Fields:</b> Select numbers of data fields to be displayed on map.

- <b>Color Field:</b> Specifies which field to be colored.

- <b>Color From & To:</b> Specify the color specific range of values in map region.

- <b>Negative Cutoff:</b> Enabled when negatives values are applicable.

- <b>Negative color from & to:</b> Specify color for specific range of negative values.

## Bar Chart

Bar charts are used to compare data across different categories. Bar chart is built by placing a dimension on a row and measure on a column area.

<b>7.</b> Choose chart type <b>Bar</b> from drop down list, under general section.

![
](https://raw.githubusercontent.com/sv18042016/fp1/06087da8a8df002e219ac38e88404ea9603f4d7c/images/New_version5/UD_Visualization_Types&Settings_Image9.png)
  <b><font color = "Black"> Image 9</b>

## Bubble chart 

Bubble Chart displays the data in circles. We can define each bubble using any of our Dimension value and its size by Measure value.
 
 <b>8.</b> Choose Chart Type <b>Bubble</b> under <b>General</b> section  to compare the data in Bubble chart.
 ![
](https://raw.githubusercontent.com/sv18042016/fp1/427b27184df7c745300ef1169318ae6427ae1e56/images/New_version5/UD_Visualization_Types&Settings_Image10.png)
  <b><font color = "Black"> Image 10</b>


## Table chart 
 
Table chart displays the data in series making it more feasible for comparing dimensions and measure values.
 
  <b>9. </b> Choose chart type  <b>Table </b> under  <b>General </b> section to compare data in table chart.
 
![
](https://raw.githubusercontent.com/sv18042016/fp1/7e9db7322511f370a3f088a614821da70ec05e0f/images/New_version5/UD_Visualization_Types&Settings_Image11.png)
<b><font color = "Black"> Image 11</b>

### Hide Pivot (Calculated Column)

To hide the first or last column field values in Table Chart, Select hide first or hide last check box in Data section of visualization.
To carry out this function you need to derive an expression in calculated column first.  
Select Stationcode, Quantity_sum and Whenmade_month, Apply pivot to Stationcode.

 <b>For Instance </b> :  derive the following expression in calculated column first;

```
pivot_offset(#{ROOT.BI_ORDERS.sum_QUANTITY} ,0,-1)
```
![
](https://raw.githubusercontent.com/sv18042016/fp1/488ee6156d0f40eb8566b427b08347106977e416/images/New_version5/UD_Visualization_Types&Settings_Image12.png)
<b><font color = "Black"> Image 12</b>

The resultant for this expression would be seen in green color;

![
](https://raw.githubusercontent.com/sv18042016/fp1/4bd9045b7b3b1dceac68eb20c87579d484fd0c4e/images/New_version5/UD_Visualization_Types&Settings_Image13.png)
<b><font color = "Black"> Image 13</b>

In the above image you can see, for pivot_hide 1st column is seen empty, to hide this select checkbox <b>pivot hide first</b> in data Section of visualization. Similarly to hide the last column, select checkbox for <b>Hide_Last</b> in data section of table chart.

> <b>Note :</b>  Applicable only for table chart. 

![
](https://raw.githubusercontent.com/sv18042016/fp1/e749e7c96af56390cc3fb80fd0d1a7d17fd0bf2c/images/New_version5/UD_Visualization_Types&Settings_Image14.png)
<b><font color = "Black"> Image 14</b>

## Funnel chart 

Funnels helps to visualize a process that has stages and items flow sequentially from stage one to next. Use a funnel when there is a sequential flow between stages, For Instance a sales process, that starts with inquiry and ends with billing.

<b>The following section describes the editing option for Funnel chart in Charts;</b>
 
 <b>9.</b>  Choose chart type <b>Funnel</b> under <b>General</b> section  to compare the data in Funnel chart.
 
![
](https://raw.githubusercontent.com/sv18042016/fp1/84af193f1ebf383092d92fc256ec7041495cca5a/images/New_version5/UD_Visualization_Types&Settings_Image15.png)
<b><font color = "Black"> Image 15</b>

<b><i>Funnel charts can be viewed in following ways;</i></b>

 - <b>Sort:</b> This enables data in the sorted order in funnel chart.
  
 - <b>Curved:</b> Displays funnel chart in curved view.
 
 - <b>Pinched:</b> Displays compressed view of the funnel chart.
  
 - <b>Inverted:</b> Displays funnel chart in reversed or bottom up position.
 
 - <b>Highlight on Hover:</b> Highlight based on hover over direction. 
 
 - <b>Dynamic Height:</b> On selecting this check box it will display the height depending on the numeric range of the data retrieved in funnel chart. 
 
 - <b>Dynamic Slope:</b> On selecting this checkbox it will display the potential covered based on the value range.

<b>For instance:</b> Higher value is referred with bigger slope and lower value is referred with smaller slope.

 - <b>Load Animation:</b> On selecting this check box the column values in funnel chart will appear as moving image.


##  Gauge Chart 

Gauge chart displays current status in the context of goal.

 
 <b>10.</b> Choose chart type <b>Gauge</b> from drop down list under <b>General</b> section  to compare the data in Gauge chart.

- <b>Green</b> color</b> in gauge chart indicates the value attained is closer to target.

![
](https://raw.githubusercontent.com/sv18042016/fp1/63e6ce82315ae4e72a287d4437b7d7a4bcea940b/images/New_version5/UD_Visualization_Types&Settings_Image16.png)
<b><font color = "Black"> Image 16</b>

- <b>Orange:</b>_ndicates, maximum value attained is half the way to target.

-  <b>Red:</b> Indicates, maximum value attained is at initial state or lower side to the target.  

![
](https://github.com/sv18042016/fp1/blob/3ff08da67be44bb345a23a3e47e19f4ab62a4553/images/New_version5/UD_Visualization_Types&Settings_Image17.png?raw=true)
<b><font color = "Black"> Image 17</b>

- <b>Value:</b> select one of the available measure values from the drop down.

- <b>Minimum:</b> specifies the minimum value of the gauge this corresponds to bottom position of the gauge.

- <b>Maximum:</b>  specifies the maximum value of the gauge this corresponds to top position of the gauge.

- <b>Title:</b> specify a title.

- <b>Label:</b> specify a identifier name to display in the chart.

- <b>Donut:</b> displays total measure value.

- <b>Counter:</b> displays minimum and maximum values of the measure.

- <b>Reverse:</b> displays the measure values in reversal direction maximum to minimum.

- <b>Hide Minmax:</b>  hides min and maximum values in gauge target.


# Standard Settings

### General Section 

- <b>Title:</b> specify title for the chart selected.

- <b>Position:</b> align title to top,bottom,left,right position.

- <b>Label:</b> Specify label text.

- <b>Padding:</b> specifies spacing at the top, bottom, left and right side of the charts.

- <b>Tooltips:</b> points the first measure value of the column field.

- <b>Grouped Tooltips:</b> points all the measure values of the column field.

- <b>Show legend:</b> on selecting this checkbox, it displays the measures fields used at the bottom of the chart, you can display or hide specific measure field values on chart by clicking on the measure field.

- <b>Display Labels:</b> enables labels on charts.

- <b>Position:</b> Align the legend at top,bottom,left and right side of the chart.

### X-Axis Menu Options

- <b>Axis type:</b> specifies how x-axis scale for Line, Bar, Bubble is calculated and displayed.

  - <b>Indexed:</b> specifies the data to be plotted in numeric values starting from zero on x-axis.
   
  - <b>Category:</b> specifies the data to be plotted as category group on x-axis.
  
  - <b>Timeseries:</b> specify the data to be plotted as time values. The x-axis is labeled with appropriate time increments.
 
- <b>Label field:</b>  specify a dimension field to be displayed on X-axis.

- <b>Show Grid:</b> enables the grid display for dimension fields on x-axis.

- <b>Axis label:</b> Text label for x-axis.

<b>Reference Lines:</b> enables the creation of reference lines in a chart.

 - <b>Grid Color</b>  Enable color for grid.

 - <b>Font Color</b> Enable color for labels on X-axis.

 - <b>Font Size:</b> enable font size for labels on X-axis.
 
 - <b>Reference:</b> specify a indicator name. 
  
 - <b>Type:</b> specify reference type as line or  area.
  
 -  <b>From & to:</b> specify the reference line for specific range of dimensions.

 - <b>Theme:</b> enables color for reference line.
 
 > <b>Note:</b>  X-Axis is enabled only for Line, Bar and Bubble chart only.

### Y-Axis

- <b>Axis:</b> select the measures values on y-axis  to enable
editing options for y-axis in Line, for Bar and bubble chart.

- <b>Axis label:</b> Text label for Y-axis.

- <b>Format:</b> it enables number format for numeric values.

- <b>Currency:</b> Using this field, you can specify the formatting for currency as of now Acubi supports $,   ₹  ,   €  ,  £.

- <b>Grid Color:</b>  Enable color for grid.
 
- <b>Font Color:</b> Enable color for labels on Y-axis.

 - <b>Font Size:</b> enable font size for labels on Y-axis.

- <b>Y-Axis:</b> display measure values on Y-axis. 

- <b>Show Grid:</b> enables the grid display for measures on y-axis.

- <b>Include Zero:</b> displays measure values starting from zero.

- <b>Position: </b>you can align the y-axis to left or right side of the chart.

- <b> Min Value</b>  Displays Y-axis data starting from value specified in field <b>Min Value</b>

### Reference Lines

<b>Reference Lines:</b> Enables the creation of reference lines in a chart.

- <b>Name:</b> Specify a reference name for specific information on y-axis.
  
- <b>Type:</b> Specify  Linear, Polynomial, Exponential, Logarithmic, Average, Median, Minimum, Maximum, Deviation, Variance, Custom Line, Custom Area on Y-axis.
  
-  <b>From & to: </b> Specify the reference line for specific range of measure values.

- <b>Theme:</b> Enables color for reference line.
 
 > <b>Note:</b>  Y-Axis is enabled only for Line, Bar and Bubble chart only.
 
### Format   
      
- <b>Condition: </b> Specify any of the following condition types Greater than, Less than, Between, Not Between, equal to, duplicates values, Top 10 Items, Bottom 10 Items, Above Average, Below Average for the fields.

- <b>Format on:</b> Specify a measure field on which you want to apply format.

- <b>Value:</B>  Specify a value to measure the condition.

- <b>BG (background color):</b> Select the background color for the data which is retrieved using condition.

- <b>Font:</b> Select the font color for the data retrieved based on condition.

- <b>Icon:</b> Select a icon for the data retrieved based on condition.

- <b>Before number:</b> Align the icon before the data value.


<b>For Example :</b> Consider below image, which displays the format section for table chart.

![
](https://raw.githubusercontent.com/sv18042016/fp1/5d83f06c9740cedd36829d2db56c97b5aac224f5/images/New_version5/UD_Visualization_Types&Settings_Image18.png)

<b><font color = "Black"> Image 18</b>
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE5ODk0MzEyMzgsLTEyOTA0NTYxMTIsMT
MwMDc0NzM4MywtMTA4MTIxNzYyMSw1NjM1Nzg2NzUsLTE0ODIz
MzA0MjksMTM0MzA5OTc2MiwxNjU4MDExMzQ4LDEyNzU2NjM4MT
EsNTkyNTIwNTA2LDEyOTQ3MTA1NzEsMjEwNzE5MTAyOSwxNDQ0
OTIxNzY3LC0xNDExNzIxMDI1LC0xMDU4ODcyMDU5LC05MDQxNT
EyMDQsLTk0OTk2Njk5OCwtMTYzMDg5MzEzNCwtMTAwMzU4NTUy
OCwtMTgwMjkzMTQxNl19
-->