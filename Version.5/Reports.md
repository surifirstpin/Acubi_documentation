

> <center><h2> REPORTS </h2></center>

This section introduces how to explore the data in AcuBi and how the query built, data retrieved and represented in desired combinations based on your business requirement and how efficiently explores particular subject area itself. AcuBi reports have an ability to pull the data and modify the report as per the needs and drill down deeper for more better insights across the report.

## Where to get started ?

 <b>Reports</B> are the starting point for building a query. To create a report, Click on <b>Reports Section.</B>

 ![
](https://raw.githubusercontent.com/sv18042016/fp1/11d8e2454a911ad96e6238049e8d1575e6dcd084/images/New_version5/UD_Reports_Image1.png)
<b><font color = "Black"> Image 1</b>

<b>1.</b>  All the connection established, databases and tables used for the Reports are defined under <b>Project.</b> Depending on your business requirement you can choose appropriate project from drop down list.

<b>For Instance :</b> To create a project based on oracle connection select project <b>Oracle_new</b> from drop down list.

<b>2. Model</b> Section has different set of models developed  for Orders, Customers, Delivery, Employees, Kitchen Process and Products.

<b>For Instance:</b> to create a report on order based details, Select <b>Bi_Orders</b> from given drop down list. 
 
 <b>3.</b> To refresh a report click on, <b>Reset</b> ( refresh icon). 

## Adding Dimension and Measure fields

The data in analyse sections is determined by  <b> Dimensions</b> and <b>Measures.</b>

 In AcuBi a dimension is derived as group of data and Measure is derived as information about group of data.

 > <b>Note :</b> All the dimensions appear blue in  color and all the measures appear in Orange color in your data table.
 
 **For Instance :**
Let us generate a query to display <b>Stationcode</b> (Dimension) and <b>Order Attendant ID</b> (Dimension) with <b>Quantity Sum.</b>

![
](https://raw.githubusercontent.com/sv18042016/fp1/f5a7faedfbdd7f0d9e7175835750a8f0c79a9e54/images/New_version5/UD_Reports_Image2.png)
<b><font color = "Black"> Image 2</b>

## SQL Query 

<b>4.</b>  Using <b>Field Picker (Search)</b>, select Dimensions and Measures.
the query is built in SQL Section based on the selection made and the joins derived in model section.

To view the SQL query built click on <b>SQL</b> section.

![enter image description here](https://raw.githubusercontent.com/sv18042016/fp1/master/images/New_version5/UD_Reports_Image13.png)
<b><font color = "Black"> Image 3</b>

## Data Extract

<b>5.</b> Hit the <b>Run< /b>button to extract data.

> <b>Note :</b>  Data retrieved on running a report, is visible in  <b>Data Section</b>.

<b>6.</b> To <b>hide</b> the Explore/Visualize section that displays dimensions and measure click on  <b>Angle Double Left</b> icon. To display the same click  <b>Angle Double Right</b> icon available near dimensions and measure field list. ( Refer Image 2)

## Add Filters

Report filters will narrow the reports results while allowing you to view the specific range of data. 

<b>7.</b> To Add Filter to a report, Click on <b>Add Filter</b> The report data is retrieved based on <b>Filter</b> applied if any. All the fields selected are visible in filter expression list using which you can apply filters.

> <b>For Example :</b> Apply filter expression to measure field <b>Quantity sum is greater than or equal to 1000</B> in filter section and data is retrieved on based on the filters applied.

  -  Hit <b>Run</b> button, data is displayed based on the filters applied.

![
](https://raw.githubusercontent.com/sv18042016/fp1/f8001dca815cc6c014f37403d67e23f6e4ef916b/images/New_version5/UD_Reports_Image3.png)
 
 <b><font color = "Black"> Image 4</b>
 
<b><i>The following are the various types of filter expressions used.</i></b>

| Type | Description |
|--|--|
| <b>String</b>| For fields that contain letters or special characters |
|<b>Numbers</b>|For fields that contain numeric|
|<b>Date</b>|For fields that contain dates|
|<b>Lookup</b>| To view the lookup in Report filters it should be derived under lookup field in model section|


<b><i>Following are the different types of filters characteristics applicable :</i><b>

## String 
|			<b>Example</b>            |						<b>Description</b>                |                                                                                 
|------------------------------|-----------------------------------------------------------|
|<b>is not null</b>                 | should not be equal to null                               |
|<b>is null</b>                     | equal to null                                             |
|<b>is not empty</b>                  | should not be empty                                       |
|<b>is empty</b>                      | should be empty                                           |
|<b>equal</b>                         | should be equals to specific value                        |
|<b>not equal</b>                     | shouldn't be equal to specific value                      |
|<b>in</b>                            | selection based on combination of filter values           |
|<b>not in</b>                       | excluding set of values                                   |
|<b>begins with</b>                   | finds any value that starts with mentioned sub string      |
|<b>doesn’t begins with</b>           | finds a value that doesn't begin with mentioned sub-string|
|<b>contains</b>                      | contains mentioned sub-string                             |
|<b>doesn’t contain</b>               | finds a value which does not contain mentioned sub-string |
|<b>ends with</b>                     | should end with mentioned sub-string                      |
|<b>doesn’t end with</b>              | should not end with mentioned sub-string                  |

## Integer

|			Example            |						Description                     |                                                                                 
|------------------------------|------------------------------------------------------------|
|<b>is not null</b>                   | should not be equal to null value                          |                
|<b>is null</b>                       | should be equal to null value                              |                                           
|<b>not empty</b>                    | data is not empty                                          |
|<b>is empty</b>                      | data is empty                                              |
|<b>equal</b>                         | data equal to specified value                              |
|<b>not equal</b>                     | data not equal to specified value                          |
|<b>in</b>                            | data equal to specified values                             |
|<b>not in</b>                        | data not equal to specified values                         |
|<b>less</b>                          | data less than specified value                             |
|<b>less or equal</b>                 | data less than or equal to specified value                 |
|<b>greater</b>                       | data greater than specified value                          |
|<b>greater or equal</b>              | data greater than or equal to specified value              |
|<b>between</b>                       | data in between the specified range                        |
|<b>not between</b>                   | data not in between the specified range                    |

## Date 

|			Example            |						Description                         |                                                                                 
|------------------------------|------------------------------------------------------------|
|<b>timeline</b>                      |data from specific time scale                               |
|<b>equal</b>                         |data from specific date                                     |
|<b>not equal</b>                     |data excluding from specific date
|<b>between</b>                       |data in between the specified dates
|<b>not between</b>                   |excluding the data between the specified range
|<b>less or equal</b>                 |data up to specified date 
|<b>greater or equal</b>              |data from the specified date 
|<b>is not null</b>                   |data which is not equal to null
|<b>is null</b>                       |data which is equal to null

> <b>Note :</b> To view the <b>Timeline Filters</b> in details please go to Timeline filters document in Technical Documents.

<b>8.</b> Similarly, we can apply <b>Hidden Filters</b> to the report data, by clicking on Filter Icon available in field list of a report. The data can also be retrieved based on the applied hidden filters, this hidden filters are visible in the list of filter expression but are hidden in data section.

<b>9.</b> To <b>Delete</b> the filter applied Click <b>Cross Icon.</B> ( Refer image 4) 


## Sorting Order (Ascending / Descending)

<b>10.</b> To view the report data in ascending or descending orders, Apply Order to the Column fields, To carry out this function Click on <b>Add Orders</b> button.

  - To Delete the Order applied Click on <b>Cross Icon.</b>
 
 ![
](https://raw.githubusercontent.com/sv18042016/fp1/ee732d48c976b66c2738b922a177c466513a35f4/images/New_version5/UD_Reports_Image4.png)
 <b><font color = "Black"> Image 5</b>

<b>11.</b> To hide the <b>Filter</b> or <b>Order</b> sections, click on angle-double-up icon on to far right of the order section. To un-hide the same click on angle-double-down icon.

## Local Sorting

<b>12.</b> Sorting can also be applied after data is retrieved in data section, you can simply click on <b>Arrow Up and Down Icon</b> available at desired field header to enable sorting.

For  <b>Dimensions</b>

-   Click on upper arrow to enable ascending order.
-   Click on down arrow to enable descending order.

For  <b>Measures</b> use opposite direction.

-   Click on upper arrow to enable descending order.
-   Click on down arrow to enable ascending order.

<b>13.</b> The <b>Total time taken</b> to build a query for a report is displayed at top of the report screen and <b>Total number of rows</b> fetched displayed just below it. (Refer image 5)
  
<b>14.</b>  Select the  <b>Check Box</b> for totals, to display total sum values of the measure fields.

<b>15.</b>  You can <b>limit</b> the rows to 100, 500, 1000, 5000, etc using given drop down list.

## Pivot

Multiple dimensions in a report data are often easier to look at, when you pivot one of the dimensions horizontally and display group based data for the field to which pivot is applied. 
<b>Pivot can be applied in 2 ways :</b>
 
<b>a.</b> To apply pivot <b>before retrieving</b> the data, Click on pivot icon at field selection. (Refer image 6)

<b>b.</b> To Apply pivot <b>after retrieving</b> the data, select List icon, then choose Pivot option from field drop down list. (Refer image 6)

![
](https://raw.githubusercontent.com/sv18042016/fp1/853361b4c4a583c5fb273a41c7e497f2dc1564e1/images/New_version5/UD_Reports_Image5.png)
**Image 6:**

> **Note :** in case if you are using multiple pivot, make sure you have at least one un-pivoted dimension and a measure value.

**Pivot Example** : if you want to view quantity sum based on station code then apply pivot for station code (Dimension) as shown in below image.

![
](https://raw.githubusercontent.com/sv18042016/fp1/f28d480f0255107fbc0b02a9636003fa49ef7d0d/images/New_version5/UD_Reports_Image6.png)
**Image 7**

## Hide data in pivot 

To hide pivoted data in report output, choose pivot hide first ( hides 1st column data in list) or choose pivot hide last (hides last column data in a list) in data section under **data-sets.**


## Pin or Remove Pin

**16.** To freeze the column field values while scrolling the data to right or left, select **Pin** option in field drop down and to release the same select **Remove Pin.**


![
](https://raw.githubusercontent.com/sv18042016/fp1/ab443ab38f10897e313c0d3e30800e0828c5d811/images/New_version5/UD_Reports_Image7.png)
**Image 8**

## Group / Un-Group

By selecting group option for a field you can display the consolidated value of the field. 

**17.** To carry out this function select  **Group** in field drop down and to release the same select **Un-Group**. 

## Multi-Level grouping

To carry out Multi-level grouping on the data extracted. Select group option for two dimension fields in drop down list. 

 **For Instance** : To get it clear on multi grouping, Add one more dimension fields **Payment_mode** to the report. Select group option for **Stationcode** and **Order_attendant_ID.** Now on expanding Stationcode_2, it displays corresponding **Order_attendant_ID** on further expanding, it displays the **payment mode** for the records as shown in the image below.

![
](https://raw.githubusercontent.com/sv18042016/fp1/8be46795cac2baf245b3ec91e0e17a3cbcae034e/images/New_version5/UD_Reports_Image8.png)
**Image 9**

**18.**  To find the specific field value, from the data extracted select **Find** from the field drop down.

**19.**  To hide the specific field in the visualization charts select **Hide Visualization** in the drop down list  and to display the same select **Show visualization.** (Refer Image 8)

**20.**  To remove a specific field column from the extracted list, select **Remove** from drop down list.


## Calculated column

Calculated column functionality allows you to manipulate the retrieved data, using arithmetical, logical, text-based and date-based functions and then displays it in the required format. 

> **Note :** To understand the total functionality of Calculated column, **"Refer Calculated Column Document".**

Click on  **Calculated column**  button to enable table calculations as shown in below image,


![enter image description here](https://raw.githubusercontent.com/sv18042016/fp1/26d0a3487833ab177c6be9fe97046d96212be2fa/images/New_version5/UD_Reports_Image9.png)
**Image 10**

 Enter Below Information in Calculated Column section.
 
-   **Field name**  unique identifier name to refer calculated column.
    
-   **Label**  labeling the calculated column.
    
-   **Data type**  data type used (string,number).
    
-   **Field type**  derives dimension or measure.
    
-   **Calculation**  derive arithmetical & logical expressions.
Use $ symbol to select apply operational function to the Fields.
    
-   **Calculate on raw data**  By enabling the field **Calculate on Raw** the calculation is applied on all the rows irrespective of grouping and pivot settings, if disabled calculation applied on abstract values only.
- 
> **Note :** To Add sum amount 100 to the quantity sum as bonus declare a calculated column as below.

![
](https://raw.githubusercontent.com/sv18042016/fp1/master/images/New_version5/UD_Reports_Image10.png)
**Image 11**

 Click **ok** after deriving the expression, all the values based on calculation is shown up in green color as shown in image below,

![
](https://raw.githubusercontent.com/sv18042016/fp1/9cb9f650b41942a8082bc296ee5426416bd20772/images/New_version5/UD_Reports_Image11.png)
**Image 12**

## Data Sets

Click on Charts, to view the different type of pictorial representation for the data obtained.

> **Note** : Go to **Visualization Document** for more details description on charts.

**Data** section under visualization is enabled based on the data retrieved on running a report.

![
](https://raw.githubusercontent.com/sv18042016/fp1/3e22fdc921e2f9e483420be1116042428e7f566a/images/New_version5/UD_Reports_Image12.png)
**Image 13**

 **Parameters applicable on the data retrieved are explained as below;**

- **Row Grouping** enables row grouping for field values based on the field selected.(Refer Image 13)

- **Explore Enabled** to explore the data which are grouped select the check box **Explore Enabled.**

- **Stacked** Series values are added on the y-axis, so each consecutive series appears above the last. Be sure that the units of all series match.

- **Datasets** this section enables you to perform alignment, set currency formats, group aggregates ( Sum, Avg, Max, Min, Count ) on the consolidated values of the field.

- **Legend** it will enable you to change the label for measure value in visualization charts. (Refer Image 13)

##  Format

 **Format** enables different type of number format to measure a field value. Following are the list of number formats supported by AcuBi:

|  Example | Description |
|  ------ | :------ |
|  #  | Number(1234) |
|  #.0  | Number with exactly one decimal(1234.0) |
|  #.00  | Number with exactly two decimal(1234.00) |
|  #.000 | Number with exactly three decimal(1234.000) |
|  #,##0 | Number with comma between thousands(1,234) |
|  #,##0.0 | Number with comma between thousands with and one decimal(1,234.0) |
|  #,##0.00 | Number with comma between thousands and two decimal(1,234.00) |
|  #,##0.000 | Number with comma between thousands and three decimal(1,234.000) |
|  ###,###.0 | Number with comma between hundreds and one decimal(123,456.0) |
|  ###,###.00 | Number with comma between hundreds and two decimal(123,456.00) |
|  ###,###.000 | Number with comma between hundreds and three decimal(123,456.000) |
|  ###.###,0 | Number with dot between hundreds and comma one decimal(123.456,0) |
|  ###.###,00 | Number with dot between hundreds and comma two decimal(123.456,00) |
|  ###.###,000 | Number with dot between hundreds and comma three decimal(123.456,0) |
|  ### ###   | Number with space between hundreds(123 456) |
|  #% | Percent with 0 decimals (1%). Please note multiplication by 100 happens automatically |
|  #.0% | Percent with one decimals (1.0%). Please note multiplication by 100 happens automatically |
|  #.00% | Percent with two decimals (1.00%). Please note multiplication by 100 happens automatically |
|  #.000% | Percent with three decimals (1.000%). Please note multiplication by 100 happens automatically |
|  # k | Number in thousand (1.234 k). Please note division by 1 thousand happens automatically |
|  # M | Number in Millions (0.001234 M).please note division by 1 million happens automatically |
|  *00#  | Number zero padded to 3 places (001) |
|  *00#.00 | Number zero padded to 3 places and exactly 2 decimals |
|  $# | Dollar with 0 decimal |
|  $#.00  | Dollar with 2 decimal |
|  $#,##0.00 | Dollars with comma between thousands and 2 decimals ($1,234.00) |


- **Currency** AcuBi supports following currency formats $,   ₹  ,   €  ,  £.






## Save Report

**21.** Click **Save** Button to Save the Report.

  -  It will navigate to Save Report Page. Fill the following fields to save the report.
  
![
](https://raw.githubusercontent.com/sv18042016/fp1/4d53ac9064e170dbaa096a06ba3517219d691b1c/images/New_version5/UD_Reports_Image14.png)
**Image 15**

-   **Report Name**  Name identifier for a report. ( AcuBi allows special character but does not support any spaces )
    
-   **Title**  label for the report the way you want it to appear.
    
-   **Info**  displays any specific information about the report.
    
-   **Privacy**  you can save the report in any one of the following privacy option.
   
    -   **Private ()**  report saved in private section and accessed by the user itself.
    -   **Public ()**  the report is saved in public section and accessed by all the users.
    -   **Share ()**  the report saved under share section and accessed by specific set of users.
    
## Saving under specific tag


All the Reports generated can be saved under any **Parent or Child Tag** available under **Workspace.**


## Defining Filter fields

Filter are used to extract only specific data you want to view. this function is carried out by applying filters to reports.

-   **Filter**  filters added in this section is automatically reflected in the filter section of dashboard reports.

Click **Save** to save a report in Database.

![
](https://raw.githubusercontent.com/sv18042016/fp1/925f7e57b04172a1a11b2ad7d839b4b8163633a9/images/New_version5/UD_Reports_Image15.png)
**Image 16**

## Download Data

**22.**  To download a report, click on **Download (icon)** button as shown in the image below.

![
](https://raw.githubusercontent.com/sv18042016/fp1/92f63f8ea46e1c695d8df74cd3dd9967e3de2a40/images/New_version5/UD_Reports_Image14_11.png)
**Image 17**
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTA4NTQwMzQwOSw3Njg3MjExOTEsMTAzMz
YyMzk1NCwtMTEzODU4MTM4OSwtMTcwOTQ1NjkwOSwtNTAxMzkz
NzM3LC01MDM0OTA2NTAsLTY5NjEzNDM3NSw1Mzg3OTMwMCwxMT
IxNjU4MjcwLC01MzExMTE0NTgsLTIwMjUxNzAzNzAsLTEwMzMx
MDg4MDAsOTA2MTc5ODIsLTE5OTk3MDAzODIsLTEwNTQ0ODk4NC
wxNDMyODk1MTI1LDQ4MjQ3ODY4NiwtMzQ2ODc3NTY4LDg5ODY4
MzMxOV19
-->