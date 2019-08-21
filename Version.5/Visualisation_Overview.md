

<center><h2>VISUALIZATION OVERVIEW</h2></center>

This section provides basic overview on visualization and its functionality.

> <b>Note :</b>  A more detailed explanation is mentioned clearly in <b>Visualization Types and Settings</b> document

Visualization in AcuBi creates impressive graphs and charts based on query result obtained and displays an eye-caching pictorial representation of data obtained. Based on your requirement, you can visualize the data in different type of charts.

<b>Basic overview on how visualization works ;</b>

Under reports section data and visualization are configured together, So once you share a query user will get a visualization picture and data as well.

<b>For Instance</b> :  Create a report to fetch Order details and query Stationcode, Whenmade_Month and order_value_sum. Apply <b>filter</b>  to whenmade_month to limit the data  to January, February and March. 

![
](https://raw.githubusercontent.com/sv18042016/fp1/588793b3bdaa6683973fbe70ceaf6b591ff25fb2/images/New_version5/UD_Visualisation_Overview_Image1.png)

 <b><font color = "Black"> Image 1</b>

After selecting dimensions and measures, run the report to display the fetched data for Order details.

> <b>Note:</b> Consider a pie Chart in visualization section. ( Pie chart supports maximum 20 division)

Click on <b>Charts</b> tab, to view different type of visualization images available for your query.
 
Under <b>General</b> tab, Select the chart type <b>PIE</b> from available drop-down list. ( Refer image 2)

![
](https://raw.githubusercontent.com/sv18042016/fp1/588793b3bdaa6683973fbe70ceaf6b591ff25fb2/images/New_version5/UD_Visualisation_Overview_Image2.png)
 <b><font color = "Black"> Image 2</b>

As shown in the image there multiple editing options provided to <b> Pie chart</b>, Similarly you can also view types of visualization options available in AcuBi.

## Hide Pivot

To hide the first or last column field data  in visualization, Select hide first or hide last check box in Data section. 
To carry out this function, derive a expression in calculated column.

<b>For Example :</b>  Apply Pivot to <b>Whenmade_Month </b> under data section. 
Derive following expression  in calculated column as follow ;

><b>Note :</b> Use $ to select the fields and later Replace it with # to Fetch the accurate values.	
```
pivot_offset( ${ROOT.BI_ORDERS.sum_QUANTITY} ,0,-1)
```
![
](https://raw.githubusercontent.com/sv18042016/fp1/ba6e2d3a06a7fd83e84e6344095e5c673abbea8d/images/New_version5/UD_Visualisation_Overview_Image3.png)

 <b><font color = "Black"> Image 3</b>

The resultant for this expression would be seen in green colour;

![
](https://raw.githubusercontent.com/sv18042016/fp1/e9c507879e500b4be6a758a27d99c4ddb4806335/images/New_version5/UD_Visualisation_Overview_Image4.png)

 <b><font color = "Black"> Image 4</b>

In the above image you can see, hide_pivot 1st column is seen empty, so in order to hide this you need to select checkbox <b>pivot hide first</B> in <b>Data Section</b> to hide it in visualization charts. Similarly you can hide last column by selecting the check box pivot hide last. (Applicable only for table chart). 

<b>Navigation :</b>  Goto <b>&rarr;</B> Charts <b>&rarr;</b> Select <b>&rarr;</b> Table Chart <b>&rarr;</b> Click Data Section <b>&rarr;</b> Expand Hide_Pivot Section.

   - Select checkbox <b>Pivot Hide First.</B>

![
](https://raw.githubusercontent.com/sv18042016/fp1/18aaf7e8bc6bd4b6048871846de1fb606759f055/images/New_version5/UD_Visualisation_Overview_Image5.png)

 <b><font color = "Black"> Image 5</b>

  - Similarly to hide the last column select the <b> Check box</b> for <b>Pivot Hide Last.</B>

## Refine Visualization

To refine and enhance the data obtained in AcuBi, It is provided with good number of customizing options.

<B>For Instance:</b>
 Select checkbox <b>Percentage</b> in Pie chart which displays the quantity sum of each month in percentage. 

![
](https://raw.githubusercontent.com/sv18042016/fp1/caef96a364da60995f83c18399b0f6c4b340ea46/images/New_version5/UD_Visualisation_Overview_Image6.png)
 <b><font color = "Black"> Image 6</b>

## Deeper insights in visualization

You can drill deeper into visualization, to get more specific information about the data obtained. In order to carry out this function, single click on the data field in table chart, it will further drill down displaying more deeper insight about the data field.

<b>For Instance:</b> In below chart, when you click on country it will display the states that fall under that country, for more deeper insight on clicking on State_Name it will display the list of cities that fall under that states as shown clearly in below image.
<b><i>Country_Name &rarr; State_Name &rarr; City_Name</i></b>

 > <b>Note:</b>  To carryout this function you need derive it in model first.

![
](https://raw.githubusercontent.com/sv18042016/fp1/7c0acf39f26482bbef006df3ae981d22e8067f00/images/New_version5/UD_Visualisation_Overview_Image7.png)
 <b><font color = "Black"> Image 7</b>

> <b>Note :</b> A more detailed explanation on visualization is given in visualization types and settings documents.

<!--stackedit_data:
eyJoaXN0b3J5IjpbNjQyODAzMjIzLDEyNzgzMjY4MDcsLTE0MT
E3NzMyMjUsMTA1MjgxMjI5MywtOTkzNDQ0ODksODY0NjY0OTY1
LC05OTM0NDQ4OSwtOTkzNDQ0ODksLTE2Mjk4MDI1ODMsNTYyOD
MyNjgxLC0xMTM0OTMzMjg5LDUxNzYxNzMsLTQzODgzOTYxMiwt
MTk3Nzc5NzIzNSwtMTY3MzQzMzgxMiwxMjMwNDcwMjM0LC0xMz
U1MTY0ODg0LC0xMTcxNzgyMDAyLC0xMTkwNDUyOTkzLC02MDk3
NTUxMF19
-->