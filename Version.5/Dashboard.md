<center><h1>Dashboard</h1></center>

Dashboard provides access to view multiple reports in single dashboard layout, in this way it provides a quick view on related data. In order to make it more feasible to users, it is provided with set of global filters by making dashboard more interactive and can re-arrange the titles. After configuring a dashboard to your interest, you can share it with your team. You can create as many dashboards as you want, so you can alter each dashboard to the specific needs of the people who use it.

## View Dashboard

After logging into AcuBi Home Page, Click on **Dashboard**.

![
](https://raw.githubusercontent.com/sv18042016/fp1/master/images/New_version5/UD_Dashboard_image1.png)

  - It will navigate to Dashboard section. It consist of list of Tags, Dashboards and Reports Saved under **My Space** structure.

   - To View a specific dashboard, enter the dashboard name in given **Search Option**. 
  - To View the dashboards and reports in List, Click on **List View**.
  - To view the dashboards and reports in folder view, Click on **Folder View.**
  
![
](https://raw.githubusercontent.com/sv18042016/fp1/master/images/New_version5/UD_Dashboard_image2.png)

 - To view the existing dashboard report click on dashboard report from the list. 
 -  It will navigate to dashboard report as shown in below image. 
 
![
](https://raw.githubusercontent.com/sv18042016/fp1/a139aa668a28e43d5ac7a91829062729877b0e09/images/New_version5/UD_Dashboard_image3.png)


 - Left side of the dashboard displays global filters used, Use **Apply** Button to re-apply any new filters to the dashboard report.
  - Click **Save,** to save the filters applied.
  - To revert back to previously applied filter, click on **Default** Button. 
  - Right side of the Dashboard displays different dashboard reports layout.
  
***Now, Let us See how to create a New dashboard.***
 
 ## Create Dashboard
Under Dashboard Section,  Choose **New->Dashboard** from the given drop down list. 

![
](https://raw.githubusercontent.com/sv18042016/fp1/99b04bcdbb9f776bd4ac2f0a851841fe9dcbbc34/images/New_version5/UD_Dashboard_image4.png)

## Select Layout

   **Layout formats are categorized in 2 ways,**
   
- **Flow Layout** This layout is provided with a scroll bar option to define your layout appropriately.

- **Grid (Fixed) Layout** All the reports in this layout will fit into single screen.

![
](https://raw.githubusercontent.com/sv18042016/fp1/3b8137ddf669d251a2e9ea3f26fa8b6bde3a8984/images/New_version5/UD_Dashboard_image5.png)


**2.**   Select the Layout using drop-down list and add reports to the layout.

**3.** To add Reports to layout selected, Select the grid and click on report you wish to add or Click on **Add** link available under work space. 

**4.** To Add Global Filters to the dashboard, Click on **Add Global Filters** Button.

**Dashboard global Filters** allows user to view limited data by applying filters on dashboard reports and it supports following filter types string, number, date and lookup.
 
| **Type** | **Description** |
|  ------ | ------ |
|  **String** | For fields that contain letters or special characters. |
|  **Number** | For fields that contain numbers. |
|  **Date** | For fields that contain dates. |
|  **Lookup** | To view the lookup in dashboard filters it should be defined in lookup section first. |

![
](https://raw.githubusercontent.com/sv18042016/fp1/1dd11662359a18e0f370aa3058e7fd6281328220/images/New_version5/UD_Dashboard_image6.png)

**Fill up the dashboard global filter section;**

 -   **Filter Name :**  identifier name to the filter applicable.

  -   **Filter Type :**  type of filter used ( Eg: string, date, number).

  -   **Operator :**  filter option to be applied on the fields.


> **Note 1:** Timeline filters, accepts only text. A detailed information on timeline filters are available in Technical Documents.
> **Note  2:** You need to add Loookups before creating Global filters.

## Lookups

 Adding lookup to dashboard will refer set of query or list of items in filters.

**5.** To Add Lookups to Dashboard reports, Click on Lookups Tab.

> **Note ** Lookup works only for string field.

![
](https://raw.githubusercontent.com/sv18042016/fp1/bd243725834336dcd901b72f730e584eb164d89c/images/New_version5/UD_Dashboard_image7.png)

**Fill up the lookup section ;**

   -   **Lookup name :**  Name Identifier for lookup field.
   
    -   **Lookup Type :**  Refers to item or query type.
   
   -  **Connection**  Connection are referred only for Queries and it is disabled for Items.
     
   **6.** Click on **Test Lookup.**
   
   -   **Multiple Selections :**  Enables the selection of list, for multiple data.

## Dependency Filters

You can refer the existing lookup, based on which a new lookup is created to retrieve the data based on referred lookup. In this way  you can extract the data depending on referred lookup field.

   -   **Referred** on selecting the referred checkbox the following lookup will extract the data based on the previously created lookup for which the referred checkbox is enabled.
 
## Report Listeners 

The Listeners option allows to register callbacks to be notified when an event is detected on a specific label.
**For instance** if a filter is defined for dashboard containing 2 reports and listener is added on particular field for report_1, it results in filter applied on report_1 it self and report_2 will remain unaffected.

![
](https://raw.githubusercontent.com/sv18042016/fp1/fdf32389df2e4c179a67ce4349c25c445af98cef/images/New_version5/UD_Dashboard_image8.png)

***Fill up the Report Listener Section ;***

   - **Reports** :  Displays the dashboard reports.
   
   -  **Add Listener :**  Adds multiple filters to reports.
   
   -   **Listen Filter :**  refers to filter option available.
    
   -   **Apply to field :**  applies filter options to field column in a report.
    
**8.** Click **Save** button It will navigate to **Save Dashboard** section.

***Fill up save dashboard section :***

   -   **Name :**  name identifier for dashboard created.
                              
   -   **Title :**  title to refer the dashboard.
    
   -   **Info :**  summary information for dashboard created.
    
   **Share Status**   Enable any of the following privacy option to save the dashboard.
    
   -  **Private()** It enable access for user itself.
   
   -  **Public()**   It enable access for all the users. 
   
    -  **Share()** It enable access for specific set of users.
  
**9.** Select the tag in which you want to save **Dashboard Reports** and click **Save.**

![
](https://raw.githubusercontent.com/sv18042016/fp1/90511a882ffd694c16d44cb8f74b6f97e9db823e/images/create_dash_ur_4.png) 

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE0MjI5ODMzMzgsLTc3NDMwMzQ0NiwtMj
gyNDY0NzQ0LC02OTgxMzczMjYsNDI2MTM1NjM0LDUwMjQ3MjE5
NywtOTY0OTAxMDM5LDE5ODcyNzE0MTcsLTEyNTE3MzAyMzYsMj
AyOTU1Nzc3OCwtOTM0NTMzODMwLC0xODczNzE3NTQ1LC01MjUw
MTc1ODIsLTE3MTAyODk3ODksMTk4MDY1MDY2NSw2OTU3ODkzOT
YsMTM5MDQ1ODI4MywxNTk5Mzg2MjM5LDI1ODgwODIxOSwtMzI4
NzM1NDVdfQ==
-->