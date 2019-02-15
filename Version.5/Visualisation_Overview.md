


<center><h1>Visualization Overview</h1></center>

This section describes a basic overview on visualization and its functionality.

> **Note :**  A more detailed explanation is mentioned clearly in **Visualization Types and Settings** document

Visualization in AcuBi creates impressive graphs and charts based on query result obtained and displays an eye-caching pictorial representation of data obtained. Based on your requirement, you can visualize the data in different chart formats.

**Basic overview on how visualization works ;**

In Reports section you can configure data and visualization together, So once you share a query user will get a visualization picture and data as well.

**For Instance** : In this example we will consider a pie chart, For which create a report to fetch Order details.  In this example we will query  **Stationcode, Whenmade_Month and order_value_sum.** Apply filter to Whenmade_month to a limit the data  to January, February and March. ( Pie chart supports maximum 20 division)

![
](https://raw.githubusercontent.com/sv18042016/fp1/588793b3bdaa6683973fbe70ceaf6b591ff25fb2/images/New_version5/UD_Visualisation_Overview_Image1.png)


After selecting dimensions and measures, run the report to display the fetched data for Order details.



## Visualization- Adds Life to Data

Click on **Charts** tab, to configure different type of visualization images for your query. 
Under **General** tab, click on the type of chart you want to view.

**For instance:** Consider **Pie Chart,** for better understanding.

![
](https://raw.githubusercontent.com/sv18042016/fp1/588793b3bdaa6683973fbe70ceaf6b591ff25fb2/images/New_version5/UD_Visualisation_Overview_Image2.png)

As shown in above image there multiple editing options provided to **Pie chart**, Similarly you can also view types of visualization options available in AcuBi.

## Hide Pivot

To hide the first or last column field data  in visualization, Select hide first or hide last check box in Data section. Pivot Whenmade_Month.
To carry out this function you need to derive a expression in calculated column.

**For Example :** Apply subtraction for Order Value_Sum and derive the expression in calculated column as follow ;
>**Note :** Use $ to select the fields and later Replace it with # to Fetch the accurate values.	
```
pivot_offset( ${ROOT.BI_ORDERS.sum_QUANTITY} ,0,-1)
```
![
](https://raw.githubusercontent.com/sv18042016/fp1/ba6e2d3a06a7fd83e84e6344095e5c673abbea8d/images/New_version5/UD_Visualisation_Overview_Image3.png)

The resultant for this expression would be seen in green colour;

![
](https://raw.githubusercontent.com/sv18042016/fp1/e9c507879e500b4be6a758a27d99c4ddb4806335/images/New_version5/UD_Visualisation_Overview_Image4.png)

In the above image you can see, hide_pivot 1st column is seen empty, so in order to hide this you need to select checkbox **pivot hide first** in **Data Section** to hide it in visualization charts. Similarly you can hide last column by selecting the check box pivot hide last. (Applicable only for table chart). 

Goto Charts-->Select-->Table Chart-->Click Data Section-->Expand Hide_Pivot Section.

Select the Hide_Pivot_First Checkbox.

![
](https://raw.githubusercontent.com/sv18042016/fp1/18aaf7e8bc6bd4b6048871846de1fb606759f055/images/New_version5/UD_Visualisation_Overview_Image5.png)

  - Similarly to hide the last column select the **check box** for **Pivot Hide Last.**

## Refine Visualization

To refine and enhance the data obtained in AcuBi, there are good number of customizing options available in Acubi Visualization section.

For Instance : Consider a Pie chart, and select **Percentage** checkbox, which displays the quantity sum percentage of each month. 

![
](https://raw.githubusercontent.com/sv18042016/fp1/caef96a364da60995f83c18399b0f6c4b340ea46/images/New_version5/UD_Visualisation_Overview_Image6.png)

## Deeper insights in visualization

You can drill deeper into visualization, to get more specific information about the data. In order to carry out this function, click on the data in table chart, so it will further drill down displaying more deeper insight about the data.

**For Instance**: In below chart, when you click on country it will display the states that fall under that country, for more deeper insight on clicking on State_Name it will display the list of cities that fall under that states as shown clearly in below image.
 Country_Name-->
 > **Note:**  To carryout this function you need derive it in model first.

A more detailed explanation on visualization is given in visualization types and settings documents.

![
](https://raw.githubusercontent.com/sv18042016/fp1/bd51433e92663a090ee5049d77c52fdbb36a2fa3/images/drill_visu.png)


<!--stackedit_data:
eyJoaXN0b3J5IjpbMTQzNDc3OTk2MywxNjI5MDQ4MDkxLDE1Mz
IxNDk3NDksLTE0ODE2MDEwNTgsMzEyOTQwMjUxLC05MzQ5NzEx
MjAsMTU3OTgzMTU5NCwxMjkzOTc2NjI3LDE4MDI0NzM0NDUsMj
Y2ODg4Njc2LDU5NzMxOTE0MCwyMTMxOTkwOTgwLDExMTExODEx
MzZdfQ==
-->