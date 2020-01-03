<center><h2>DASHBOARD</h2></center>

Dashboard provides access to view multiple reports in single dashboard layout, this way it provides a quick view on related data. In order to make it more feasible to users, it is provided with set of global filters by making dashboard more interactive and can re-arrange the titles. After configuring a dashboard to your interest, you can share it with your team. You can create as many dashboards as you want, so you can alter each dashboard to the specific needs of the people who use it.

## View Dashboard

After logging into AcuBi Home Page, Navigate to <b>Dashboard</b> Section.

![enter image description here](https://raw.githubusercontent.com/sv18042016/fp1/e633a63e9f980e7bcc0cfcd76e32592477ab197f/images/New_version5/UD_Dashboard_image1_1.png)
<b><font color = "Black"> Image 1</b>

  - Dashboard section consist of list of Tags, Dashboards and Reports Saved under <b>My Space</b> structure.

  - To View a specific dashboard, enter the dashboard name in given <b>Search Option.</B>
  - To View the dashboards and reports in List view, Click on <b>List View</b>.
  
  - To view the dashboards and reports in folder view, Click on <b>Folder View.</b>
  
![
](https://raw.githubusercontent.com/sv18042016/fp1/master/images/New_version5/UD_Dashboard_image2.png)
<b><font color = "Black"> Image 2</b>

 - To view the existing dashboard report click on dashboard report name in the list. 
 
 -  It will navigate to dashboard report. ( Refer image 3)
 
![
](https://raw.githubusercontent.com/sv18042016/fp1/a139aa668a28e43d5ac7a91829062729877b0e09/images/New_version5/UD_Dashboard_image3.png)
<b><font color = "Black"> Image 3</b>

 - Left side of the dashboard displays global filters used.

-  To change the existing filter options, Select <b>Apply</b> button to re-apply any newly added filters to the dashboard report.

 -  Click <b>Save,</b> to save the filters applied.

- To revert back to previously applied filter, click on <b>Default</b> Button. 

- Right side of the Dashboard displays different dashboard reports layout.
  
 ## Creating Dashboard
 
<b>1.</b> Under Dashboard Section,  Choose <b>New->Dashboard</b> from the given drop down list. 

![
](https://raw.githubusercontent.com/sv18042016/fp1/99b04bcdbb9f776bd4ac2f0a851841fe9dcbbc34/images/New_version5/UD_Dashboard_image4.png)

<b><font color = "Black"> Image 4</b>

## Select Layout

   <b><i>Layout formats are categorized in 2 ways,</i></b>
   
- <b>Flow Layout</b> This layout is provided with a scroll bar option to define your layout appropriately.

- <b>Grid (Fixed) Layout</b> All the reports in this layout will fit into single screen.

![
](https://raw.githubusercontent.com/sv18042016/fp1/3b8137ddf669d251a2e9ea3f26fa8b6bde3a8984/images/New_version5/UD_Dashboard_image5.png)
<b><font color = "Black"> Image 5</b>

<b>2.</b>   Select the Layout using drop-down list.

  <b>3.</b> To add reports in flow layout, select the grid and click on report available under <b>Work space</b>. Select  <b>Add</b>  to add new report grid to existing layout.

<b>4.</b> To Add Global Filters to the dashboard, Click on <b>Add Global Filters</b> Button.

<b>Dashboard global Filters</B> allows user to view limited data by applying filters on dashboard reports and it supports following filter types string, number, date and lookup.
 
| **Type** | **Description** |
|  ------ | ------ |
|  **String** | For fields that contain letters or special characters. |
|  **Number** | For fields that contain numbers. |
|  **Date** | For fields that contain dates. |
|  **Lookup** | To view the lookup in dashboard filters it should be defined in lookup section first. |


![
](https://raw.githubusercontent.com/sv18042016/fp1/1dd11662359a18e0f370aa3058e7fd6281328220/images/New_version5/UD_Dashboard_image6.png)
<b><font color = "Black"> Image 6</b>

<b><i><u>Fill up the dashboard global filter section;</i></u></B>

 -   <b>Filter Name :</B>  identifier name to the filter applicable.

 -   <b>Filter Type :</B>  type of filter used ( Eg: string, date, number).

 -   <b>Operator :</b>  filter option to be applied on the fields.


> <b>Note 1:</b> Timeline filters, accepts only text. A detailed information on timeline filters are available in Technical Documents.
> <b>Note  2:</B> You need to add Loookups before creating Global filters.

## Lookups

 Adding lookup to dashboard will refer set of query or list of items in filters.

<b>5.</b> To Add Lookups to Dashboard reports, Click on Lookups Tab.

> <b>Note:</B> Lookup works only for string field.

![
](https://raw.githubusercontent.com/sv18042016/fp1/bd243725834336dcd901b72f730e584eb164d89c/images/New_version5/UD_Dashboard_image7.png)
<b><font color = "Black"> Image 7</b>

<b><u><i>Fill up the lookup section ;</u></i></b>

 -   <b>Lookup name :</B> Name Identifier for lookup field.
 -   <b>Lookup Type :</b>  Refers to item or query type.
   
 -  <b>Connection</b>  Connection are referred only for Queries and it is disabled for Items.
     
   <b>6.</B> Click on <b>Test Lookup.</b>
   
 -   <b>Multiple Selections : </b> Enables the selection of list, for multiple data.

## Dependency Filters

You can refer the existing lookup, based on which a new lookup is created to retrieve the data based on referred lookup. In this way  you can extract the data depending on referred lookup field.

   -   <b>Referred</b> on selecting the referred checkbox the next following lookup will extract the data based on the previously created lookup for which the referred checkbox is enabled.
 
## Report Listeners 

The Listeners option allows to register callbacks to be notified when an event is detected on a specific label.

<b>For instance</b> if a filter is defined for dashboard containing 2 reports and listener is added on particular field for report_1, it results in filter applied on report_1 it self and report_2 will remain unaffected.

![
](https://raw.githubusercontent.com/sv18042016/fp1/fdf32389df2e4c179a67ce4349c25c445af98cef/images/New_version5/UD_Dashboard_image8.png)
<b><font color = "Black"> Image 8</b>

<b><i><u>Fill up the Report Listener Section ;</u></i></b>

   - <b>Reports</b> :  Displays the dashboard reports.
   
   -  <b>Add Listener :</b> Adds multiple filters to reports.
   
   -   <b>Listen Filter :</B>  refers to filter option available.
    
   -   <b>Apply to field :</b>  applies filter options to field column in a report.
    
<b>8.</b> Click <b>Save</b> button It will navigate to <b>Save Dashboard</b> section.

<b><i><u>Fill up save dashboard section :</u></i></b>

   -   <b>Name : </b> name identifier for dashboard created.
                              
   -   <b>Title :</B>  title to refer the dashboard.
    
   -   <b>Info :</B>  summary information for dashboard created.

## Share Status    

<b>Share Status</b>   Enable any of the following privacy option to save the dashboard.
   -  <b>Public()</B>   It enable access for all the users. 
     
   -  <b>Private()</B> It enable access for user itself.
   
   -  <B>Share()</B> It enable access for specific set of users.
  
<b>9.</B> Choose the tag where you would like to save <b>Dashboard Reports</b> and click <b>Save.</b>

![
](https://raw.githubusercontent.com/sv18042016/fp1/b59aa3d638caeab80a9fa1c15b898fb0d403988f/images/New_version5/UD_Dashboard_image9.png)
<b><font color = "Black"> Image 9</b>
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE3MDMwNjQ0MzMsLTE4NTA4MTksMTM2MT
Y1MDg1MCw1NDgyOTYzNjUsLTM5Mjc0OTM0LC03NjY0MzA5NDIs
MTAwOTI4NzMyOCwyNjE2Nzg2NzgsNTM0NjMwMTU4LC0xNDMzOD
IyMTAwLC0yMTM5NzI1NjQ3LC0yMDgwODY5NDY2LDg4OTkwNzgx
MiwtNDU0NjA5NjEsMjA3MTQyMzgzMSwxMTUwNjYyNTYwLC0xND
g1MTgyMjQxLC02ODgwMTU4NjQsNzU3NDYyNDkzLC04NDAwNjAz
NzBdfQ==
-->