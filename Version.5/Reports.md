

> <center><h1> Reports </h1></center>

This section discuss how Acubi Builds they query and data retrieved is represented in different type of visualization images based on the requirement. 

Analysis reports. Reports are the starting point for a query. retrieves the data in the desired combinations as per your business needs and how to explore particular subject area it self. It has an ability on how to pull the data and modify the report as per the needs and drill down deeper into the report for more better insights across the report.

 To create a report, Click on **Reports Section**.
 
 ![
](https://raw.githubusercontent.com/sv18042016/fp1/11d8e2454a911ad96e6238049e8d1575e6dcd084/images/New_version5/UD_Reports_Image1.png)


**1.**  All the connection established, databases and tables used for the Reports are defined under **Project.** Depending on your business requirement you can choose appropriate project.

**For Example :** If you want to create a project based on oracle connection select project **Oracle_new** from drop down list.

**2.** **Model** Section has different set of models developed  for Orders, Customers, Delivery, Employees, Kitchen Process and Products.

**For Example:** to create a report on order based details, Select **Bi_Orders** from given drop down list. 
 
 **3.** To refresh a report click on, **Reset** ( refresh icon). 

## Getting Started

The data in analyse sections is determined by dimensions and measures.

![
](https://raw.githubusercontent.com/sv18042016/fp1/f5a7faedfbdd7f0d9e7175835750a8f0c79a9e54/images/New_version5/UD_Reports_Image2.png)

**4.**  Using **Field Picker**, select Dimensions and Measures to retrieve the data based on the selection made. In AcuBi a dimension is derived as group of data and Measure is derived as information about group of data.

 > **Note :** All the dimensions appear blue in  colour and all the measures appear in Orange colour in your data table.

Let us generate a query to display Stationcode (Dimension) and Order Attendant ID (Dimension) with Quantity Sum. 

**5.** After Selecting dimensions and measures, hit the **Run** button to extract and display the data.
In the following example we have selected **Two Dimensions and One Measure Field.**

> **Note :**  Data retrieved on running a report, is visible in  **Data Section**

**6.** To hide the Explore /visualize section that displays dimensions and measure click on  **angle double left** icon. to display the explore/visualize section click  **angle double right** icon available near dimensions and measure field list.

## Report Filters

Report filters will narrow the reports results while allowing you to view the specific range of data. 

**The following are the various types of filter expressions used.**

| Type | Description |
|--|--|
| **String** | For fields that contain letters or special characters |
|**Numbers**|For fields that contain numeric
|
|**Date**|For fields that contain dates|
|**Lookup**| To view the lookup in Report filters it should be derived under lookup field in model section|


**Following are the different types of filters characteristics applicable :**

## String 
|			**Example**            |						**Description**                        |                                                                                 
|------------------------------|-----------------------------------------------------------|
|**is not null**                   | should not be equal to null                               |
|**is null**                       | equal to null                                             |
|**is not empty**                  | should not be empty                                       |
|**is empty**                      | should be empty                                           |
|**equal**                         | should be equals to specific value                        |
|**not equal**                     | shouldn't be equal to specific value                      |
|**in**                            | selection based on combination of filter values           |
|**not in**                        | excluding set of values                                   |
|**begins with**                   | finds any value that starts with mentioned sub string      |
|**doesn’t begins with**           | finds a value that doesn't begin with mentioned sub-string|
|**contains**                      | contains mentioned sub-string                             |
|**doesn’t contain**               | finds a value which does not contain mentioned sub-string |
|**ends with**                     | should end with mentioned sub-string                      |
|**doesn’t end with**              | should not end with mentioned sub-string                  |

## Integer

|			**Example**            |						**Description**                         |                                                                                 
|------------------------------|------------------------------------------------------------|
|**is not null**                   | should not be equal to null value                          |                
|**is null**                       | should be equal to null value                              |                                           
|**not empty**                     | data is not empty                                          |
|**is empty**                      | data is empty                                              |
|**equal**                         | data equal to specified value                              |
|**not equal**                     | data not equal to specified value                          |
|**in**                            | data equal to specified values                             |
|**not in**                        | data not equal to specified values                         |
|**less**                          | data less than specified value                             |
|**less or equal**                 | data less than or equal to specified value                 |
|**greater**                       | data greater than specified value                          |
|**greater or equal**              | data greater than or equal to specified value              |
|**between**                       | data in between the specified range                        |
|**not between**                   | data not in between the specified range                    |

## Date 

|			Example            |						Description                         |                                                                                 
|------------------------------|------------------------------------------------------------|
|**timeline**                      |data from specific time scale                               |
|**equal**                         |data from specific date                                     |
|**not equal**                     |data excluding from specific date
|**between**                       |data in between the specified dates
|**not between**                   |excluding the data between the specified range
|**less or equal**                 |data up to specified date 
|**greater or equal**              |data from the specified date 
|**is not null**                   |data which is not equal to null
|**is null**                       |data which is equal to null

> **Note :** To view the **Timeline Filters** in details please go to Timeline filters document.

**7.** To Add Filter to a report, Click on **Add Filter.** The report data is retrieved based on **Filter** applied if any. All the fields selected are visible in filter expression list using which you can apply filters.

> **For Example :** Apply filter expression to measure field **Quantity sum is greater than or equal to 1000** in filter section and data is retrieved on based on the filters applied.

![
](https://raw.githubusercontent.com/sv18042016/fp1/f8001dca815cc6c014f37403d67e23f6e4ef916b/images/New_version5/UD_Reports_Image3.png)
 
  -  Hit the **Run** button, data is displayed based on the filters applied.

**8.** Similarly, we can apply **Hidden Filters** to the report data, By Clicking on Filter Icon available in field list of a report. The data can also be retrieved based on the applied hidden filters, this hidden filters are visible in the list of filter expression but are hidden in data section.

**9.** To Delete the filter applied Click **Cross Icon** as shown in the image below.


## Order (Ascending / Descending)

**10.** To view the report data in ascending or descending orders, Apply Order to the Column fields, To carry out this function Click on **Add Orders** button.

 > To Delete the Order applied Click on **Cross Icon.**
 
 ![
](https://raw.githubusercontent.com/sv18042016/fp1/ee732d48c976b66c2738b922a177c466513a35f4/images/New_version5/UD_Reports_Image4.png)

**11.** To hide the **Filter** or **Order** sections, click on angle-double-up icon on to far right of the order section. To un-hide the same click on angle-double-down icon.

## Local Sorting

**12.** Sorting can also be applied after data is retrieved in data section, you can simply click on **Arrow Up and Down Icon** available at desired field header to enable sorting.

For  **Dimensions**

-   Click on upper arrow to enable ascending order.
-   Click on down arrow to enable descending order.

For  **Measures** use opposite direction.

-   Click on upper arrow to enable descending order.
-   Click on down arrow to enable ascending order.

**13.** The **Total time taken** to build a query for a report is displayed at top of the report screen and **Total number of rows** fetched displayed just below that.
  
**14.**  Select the  **Check Box** for totals, to display total sum values of the measure fields.

**15.**  You can **limit** the rows to 100, 500, 1000, 5000, etc using given drop down list.

## Pivot

Multiple dimensions in a report data are often easier to look at, when you pivot one of the dimensions horizontally and display group based data for the field to which pivot is applied. 
**Pivot can be applied in 2 ways :**
 
**a.** To apply pivot **Before Retrieving** the data, Click on pivot icon at field selection.

**b.** To Apply pivot **After Retrieving** the data, select List icon, then choose Pivot option from field drop down list. 

![
](https://raw.githubusercontent.com/sv18042016/fp1/853361b4c4a583c5fb273a41c7e497f2dc1564e1/images/New_version5/UD_Reports_Image5.png)

> **Note :** incase if you are using multiple pivot, make sure you have at least one un-pivoted dimension and a measure value.

**Pivot Example** : if you want to view quantity sum based on station code then apply pivot for station code (Dimension) as shown in below image.

![
](https://raw.githubusercontent.com/sv18042016/fp1/f28d480f0255107fbc0b02a9636003fa49ef7d0d/images/New_version5/UD_Reports_Image6.png)

## Hide data in pivot 

To hide pivoted data in report output, choose pivot hide first ( hides 1st column data in list) or choose pivot hide last (hides last column data in a list) in data section under datasets.


## Pin or Remove Pin

**16.** To freeze the column field values while scrolling the data to right or left, select **Pin** option in field drop down and to release the same select **Remove Pin.**


![
](https://raw.githubusercontent.com/sv18042016/fp1/ab443ab38f10897e313c0d3e30800e0828c5d811/images/New_version5/UD_Reports_Image7.png)

## Group / Un-Group

By selecting group option for a field you can display the consolidated value of the field. 

**17.** To carry out this function select  **Group** in field drop down and to release the same select **Un-Group**. 

## Multi-Level grouping

To carry out Multi-level grouping on the data extracted. Select group option for two dimension fields in drop down list. 

> **For Example** : To get it clear on multi grouping, i am adding one more dimension fields **Payment_mode** to the report. Select group option for **Stationcode** and **Order_attendant_ID.** Now on expanding Stationcode_2, it displays corresponding **Order_attendant_ID** on further expanding, it displays the **payment mode** for the records as shown in the image below.

![
](https://raw.githubusercontent.com/sv18042016/fp1/8be46795cac2baf245b3ec91e0e17a3cbcae034e/images/New_version5/UD_Reports_Image8.png)


**18.**  To find the specific field value, from the data extracted select **Find** from the field drop down.


**19.**  To hide the specific field in the visualization charts select **Hide Visualization** in the drop down list  and to display the same select **Show visualization.**

**20.**  To remove a specific field column from the extracted list, select **Remove** from drop down list.


## Calculated column

Calculated column functionality allows you to manipulate the retrieved data, using arithmetical, logical, text-based and date-based functions and then displays it in the required format. 

> **Note :** To understand the total functionality of Calculated column, **"Refer Calculated Column Document".**

Click on  **Calculated column**  button to enable table calculations as shown in below image,


![enter image description here](https://raw.githubusercontent.com/sv18042016/fp1/26d0a3487833ab177c6be9fe97046d96212be2fa/images/New_version5/UD_Reports_Image9.png)

After navigating to calculated column, enter below fields;

> **Note :** To Add sum amount 100 to the quantity sum as bonus declare a calculated column as below.

![
](https://raw.githubusercontent.com/sv18042016/fp1/master/images/New_version5/UD_Reports_Image10.png)

-   **Field name**  unique identifier name to refer calculated column.
    
-   **Label**  labeling the calculated column.
    
-   **Data type**  data type used (string,number).
    
-   **Field type**  derives dimension or measure.
    
-   **Calculation**  derive arithmetical & logical expressions.
Use $ symbol to select apply operational function to the Fields.
    
-   **Calculate on raw data**  By enabling the field **Calculate on Raw** the calculation is applied on all the rows irrespective of grouping and pivot settings, if disabled calculation applied on abstract values only.


 Click **ok** after deriving the expression, all the values based on calculation is shown up in green colour as shown in below image,

![
](https://raw.githubusercontent.com/sv18042016/fp1/9cb9f650b41942a8082bc296ee5426416bd20772/images/New_version5/UD_Reports_Image11.png)

## Data Sets

Click on Charts, to view the different type of visualization image for data obtained.

> **Note** : Goto Visualization Document for more details description on charts.

**Data** section under visualization is enabled based on the data retrieved on running a report.
![
](https://raw.githubusercontent.com/sv18042016/fp1/3e22fdc921e2f9e483420be1116042428e7f566a/images/New_version5/UD_Reports_Image12.png)


 **Parameters applicable on the data retrieved are explained as below;**

- **Row Grouping** enables row grouping for field values based on the field selected as shown in the below image.

- **Explore Enabled** to explore the data which are grouped select the check box **Explore Enabled.**

- **Stacked** Series values are added on the y-axis, so each consecutive series appears above the last. Be sure that the units of all series match.

- **Datasets** this section enables you to perform alignment, set currency formats, group aggregates ( Sum, Avg, Max, Min, Count ) on the consolidated values of the field.

- **Legend** it will enable you to change the label for measure value in visualization charts as shown below.

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



## SQL Query 

To view the SQL query built on retrieving data in report, click on **SQL** section.

![
](https://raw.githubusercontent.com/sv18042016/fp1/master/images/New_version5/UD_Reports_Image13.png)

## Save Report

**21.** Click Save Button to Save the Report.

  -  You will be navigated to Save Report Page. Fill the following fields to save the report.
  
![
](https://raw.githubusercontent.com/sv18042016/fp1/4d53ac9064e170dbaa096a06ba3517219d691b1c/images/New_version5/UD_Reports_Image14.png)

-   **Report Name**  Name identifier for a report. ( Acubi allows special character but does not support any spaces )
    
-   **Title**  label for the report the way you want it to appear.
    
-   **Info**  displays any specific information about the report.
    
-   **Privacy**  you can save the report in any one of the following privacy option.
   
    -   **Private ()**  report saved in private section and accessed by the user itself.
    -   **Public ()**  the report is saved in public section and accessed by all the users.
    -   **Share ()**  the report saved under share section and accessed by specific set of users.
    
## Saving under specific tag

Reports build, are saved under  **Work space**  tag.

## Defining Filter fields

Filter are used to extract only specific data you want to view. this function is carried out by applying filters to reports.

-   **Filter**  filters added in this section is automatically reflected in the filter section of dashboard reports.

Click Save to **Save** the Report in Data Base.

![
](https://raw.githubusercontent.com/sv18042016/fp1/925f7e57b04172a1a11b2ad7d839b4b8163633a9/images/New_version5/UD_Reports_Image15.png)
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEzMzg0MjMxMjQsMTMyODgxMTAwNCwtMT
k1MTUwNDc5NywxNjIzMjEyNzE2LC0xMDU0MTcyNDg0LC03NTU4
MDQ1MTYsMTI1NDc1MTgxNCwtODQ2NjExOTYxLC0yNTI2Mzc1MD
csMTE0NjM1NTk4MiwtMTc3OTA1NjYxNywtMTY5NzY1MjU3MSw1
MDY2MjIzNzMsLTE1Nzc1MzM0NTksMTI1NjYzMTA1LDIwODA3Nj
EwMjQsMTU0OTg5Mjc4LDE3NDQ1MjIyMDgsLTk4NDc2MTgzNSwt
MTQxMzUwODQ3OF19
-->