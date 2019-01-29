<center><h1>Dashboard</h1></center>

Dashboard provides access to view multiple reports in single dashboard layout, in this way it provides a quick view on related data. In order to make it more feasible to users, it is provided with set of global filters by making dashboard more interactive and can re-arrange the titles. After configuring a dashboard to your interest, you can share it with your team. You can create as many dashboards as you want, so you can alter each dashboard to the specific needs of the people who use it.

## View Dashboard

After logging into AcuBi Home Page, Click on **Dashboard Section**.
 it consist of list of Tags, Dashboards and Reports Saved under **My Space** structure.
   - To View a specific dashboard, enter the dashboard name in given **Search Option**. 
  - To View the dashboards and reports in List, Click on **List View**.
  - To view the dashboards and reports in folder view, Click on **Folder View.**

 - Choose the dashboard from the list and click on it. You will be navigated to the dashboard report. 
 - Left side of the dashboard displays global filters used.
  - here you can apply available filter option and check the result depending on the filter applied, By clicking on **Apply** Button.
  - Click **Save,** to save the Filters applied.
  - To revert back to previously applied Filter click on **Default** Button. 


*Now, Let us See how to create a New dashboard.*
 
 ## Create Dashboard

**1.** Choose New->Dashboard from the drop down list on top of the screen. 

![
](https://raw.githubusercontent.com/sv18042016/fp1/90511a882ffd694c16d44cb8f74b6f97e9db823e/images/create_dash_ur_1.png)


## Select Layout

   **Layout formats are categorized in 2 ways,**
   
- **Flow Layout** This layout is provided with a scroll bar option to define your layout appropriately.

- **Grid (Fixed) Layout** All the reports in this layout will fit into single screen.

 Select the Layout using drop-down list and add reports to the layout.
 
To add Reports to layout selected, Click on **Add** link available under work space. 

![
](https://raw.githubusercontent.com/sv18042016/fp1/90511a882ffd694c16d44cb8f74b6f97e9db823e/images/create_dash_ur_2.png)

To Add Global Filters, Click on **Add Global Filters** Button.

**Dashboard global Filters** allows user to view limited data by applying filters on dashboard reports and it supports following filter types string, number, date and lookup.
 
|  **Type** | **Description** |
|  ------ | ------ |
|  String | For fields that contain letters or special characters. |
|  Number | For fields that contain numbers. |
|  Date | For fields that contain dates. |
|  Lookup | To view the lookup in dashboard filters it should be defined in lookup section first. |

**Fill up the dashboard global section;**

  -   **Filter Name :**  identifier name to the filter applicable.

  -   **Filter Type :**  type of filter used ( Eg: string, date, number).

  -   **Operator :**  filter operation that are applicable.

## Lookups

 Adding lookup to dashboard will refer set of query or list of items in filters.

**Fill up the lookup section ;**

   -   **Lookup name :**  name of the lookup field.
   
    -   **Lookup Type :**  refers to item or query type.
   
   -  **Connection**  Connection are referred only for Queries and it is disabled for Items.
     
    -   **Test Lookup :**  To test the lookup.
   
    -   **Multiple Selections :**  enables the selection of list, for multiple data.

## Dependency Filters

You can refer the existing lookup, based on which a new lookup is created to retrieve the data based on referred lookup. In this way  you can extract the data depending on referred lookup field.

   -   **Referred** on selecting the referred checkbox the following lookup will extract the data based on the previously created lookup for which the referred checkbox is enabled.
 
## Report Listeners 

The Listeners option allows to register callbacks to be notified when an event is detected on a specific label.
**For instance** if a filter is defined for dashboard containing 2 reports and listener is added on particular field for report_1 it results in filter applied on report_1 it self and report_2 will remain unaffected.

*Fill up the Report Listener Section ;*

   - **Reports** :  Displays the dashboard reports.
   
   -  **Add Listener :**  Adds multiple filters to reports.
   
   -   **Listen Filter :**  refers to filter option available.
    
   -   **Apply to field :**  applies filter options to field column in a report.
    
 On Clicking **Save** button It will navigate to **Save Dashboard** section.

![
](https://raw.githubusercontent.com/sv18042016/fp1/90511a882ffd694c16d44cb8f74b6f97e9db823e/images/create_dash_ur_3.png)

*Fill up save dashboard section :*

   -   **Name :**  name identifier for dashboard created.
                              
   -   **Title :**  title to refer the dashboard.
    
   -   **Info :**  summary information for dashboard created.
    
   **Share Status**   Enable any of the following privacy option to save the dashboard.
    
   -  **Private()** It enable access for user itself.
   
   -  **Public()**   It enable access for all the users. 
   
    -  **Share()** It enable access for specific set of users.
  
Select the tag in which you want to save **Dashboard Reports** and click **Save.**

![
](https://raw.githubusercontent.com/sv18042016/fp1/90511a882ffd694c16d44cb8f74b6f97e9db823e/images/create_dash_ur_4.png) 

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE5Mjg2MjY2NywyMjY2MjY4NDUsLTQ3Nj
Q2MzYxLC0xMDA4MzkwMzMsLTQxMzA5NTUxMSw2ODc1NTAzMTks
LTQ4NTQ4NDc2OSwxNjIwNjY1MjEwLC0xNjYxOTIwOTc2LDQ3MD
UyMTM4NiwyMDQ3MTI2MjUxXX0=
-->