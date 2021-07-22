# Data_Visualization

Using Tools like Tableau is a great way for EDA (Exploratory Data Analysis) to perform initial investigations on data so as to discover patterns,to spot anomalies,to test hypothesis and to check assumptions with the help of graphical representations.


**TabPy for Predictive Analytics**

On the other hand, Tableau brings everything together in a visual environment that’s accessible to anyone functioning as a dashboard for supply chain analytics. Moreover it supports advanced predictive modeling and forecasting that can be connected to TabPy Server for Enterprise needs. Tableau opens an elegant and powerful view into your existing metrics and allows you to create new, customized algorithms. See how Tableau enhances your supply chain analytics below. Streamlining the supply chain means managing multiple complex factors all at once, in real time: optimizing inventory, streamlining transportation, and delivering just in time, every time. 

![GI_RGI_Analysis](https://user-images.githubusercontent.com/32416129/126684043-f6c012da-d7ab-40fc-a0ef-569b3fa87033.gif)


TabPy Server Running for Tableau Connections

TabPy (the Tableau Python Server) is an Analytics Extension implementation which expands Tableau's capabilities by allowing users to execute Python scripts and saved functions via Tableau's table calculations. Hence, TabPy is what is required to support predictive modeling (ie: supervised learning - Linear Regression or unsupervised learning such as clustering) in Python sci-kit learn packages.

![image](https://user-images.githubusercontent.com/32416129/126685433-7d688362-10b4-4d1b-a205-3c9ac2cc3a7a.png)
![image](https://user-images.githubusercontent.com/32416129/126685662-6fd0d8f7-fb9b-4fee-a959-53c65d359c2a.png)



Power BI for Data Visualization - Order/Supply Chain/Operations Management or Exploratory Data Analytics
Order Management Analytics is unlike Order Management System which is typically commercially off-the-shelf (COTS) information system which has the general functionality specifically for the industry (ie: retail merchandiser, food manufacturing etc.) integrated as an enterprise resource planning system. ERP application depending on the vendor brand (ie: SAP, Oracle Business Suite, Microsoft Dynamics 365) can be customized according business processes workflow, that collects inputs from departments including accounting, manufacturing, supply chain to deliver their products to customers in timely fashion.
Power BI or Tableau offers simple and fast solution for order management analytics to visualize enterprise operations (ie: sales, inventory, manufacturing output & delivery) performance, the best part of it is that it can be modified over the years without investing a hefty sum to IT or web development fee.
1. Benefits of Dashboard using Power BI:
→ To visualize data trends, patterns or business operations or supply chains KPI (ie: sales target achieved, dead-stock, shipment quantity etc) to gain insights for decision-making especially when data sources format is non-SQL database, for instance excel files which is typical file format available to download from various platform such as SAP, Oracle ERP, SAP/Oracle Business Intelligence software or amy corporate firm's in-house proprietary web portal so forth etc.
Importing multiple Excel files using Python ScriptMerged result after importing multiple Excel file using Python Script1 PowerBI support for Importing data from various sources

→ Support importing data from multiple sources (ie: SQL Database - MS SQL, Oracle, or non SQL file - Excel) before it's loaded into dashboard presenting for data visualization in real-time for interactivity using filters, instead of/unlike using Excel VBA Macro which will prevent other Excel worksheet from processing. In other words when using PowerBI , it frees up Excel for other data processing work while processing simultaneously for data visualization
1.2 PowerBI support for consolidating data using Python or R overcomes/address the limitation of Microsoft Query or SQL
→ Above image is an illustration of combining data from 2 separate Excel files and data consolidation analogy applies the same if sources are from multiple excel worksheet(s), SQL database to merge them based on identical attributes (ie: database fields or Excel columns) that fits the analysis requirements. The best part of merging using R or Python is that the fields or attributes names doesn't really matter, data type and values is what counts for the merging.
The flexibility of merging data from various SQL database or no-SQL sources (ie: multiple Excel files) matching on identical attributes is often limited by Microsoft Query Tables Pane, Criteria that is translated into SQL Statement.
1.3 Evaluation of Visualization Effects Power BI versus MS Excel
→ Below is my personal comparison between Power BI versus MS Excel based on experience performing basic arithmetic computation.
Overall, Power BI produce more interactivity of data with different input control functions (ie: List, Drop Down, Multi-Select, Single-Select) as a data slicer, although data slicer feature is also available in MS Excel.

Excel Data Slicer as Input Selection Control instead of Power BI List & DropDown as Input Selection ControlPower BI offering choice of List or Dropdown as Input Selection Control2. Power BI can allow producing geo-location visualization mapping from the location-based data which apparently not possible using MS Excel.
3. Overall, Power BI is intended for data visualization, hence the features allows more user-control to generate more stunning visualization unlike MS Excel allow user-control to generate basic decent visualization for dashboard.
4. In the above image, Power BI dashboard that i've created comprises of tabular data that is generated using the group-by function using Power Query/DAX Statement. One of the tabular is group-by attribute (Date) while another one is a combination of attributes (ie: Date & FE Technology etc). Apparently, the group-by with combination of multiple attributes makes it realistic in any business scenario context, which i find it visualize appealing than using MS Excel with Pivot Table Layout which result in data merging together when added into Rows of PivotTable Fields.
Excel PivotTable Layout2. Power BI - Python Script Editor to process Python Scripts/Statement
→ Power BI Python Script Editor is able to interpret Python script to generate bar chart to generate the same visual as what could be generated on some other IDE Editor (ie: PyCharm)
Power BI with Python Script Editor to process Python Script/Statement to generate Bar ChartPyCharm with the python statement to generate Bar Chart→ Power BI Python Script Editor when processing dataframe using aggregate and sort_values method as well as print(df) statement is somewhat different results from what is generated on some other IDE Editor (ie: PyCharm). Hence, in my opinion, Python Script is unsuitable for presenting tabular data for visualization in Power BI, which should be accomplished using Power Query or DAX statement instead.
Power BI with Python Script Editor to process Python Script/Statement for displaying data in tabular form. The results is somewhat different from what is generated using PyCharm.Same Python Script/Statement to display data in tabular form in PyCharm3. Power BI for Data Visualization as Dashboard
Overall, Power BI is still recommended regardless of what your budget expense is, it offers various choices/options of visualizations which can be downloaded from AppSource.
Below is an illustration of simplistic Power BI Dashboard which incorporates elements of Tabular Data, Stacked Bar Chart and Input Control (ie: List) which allows multiple select, which i prefer it over Drop-Down Box which is unable to display on the selected items.
Power BI can be used as a tool for EDA (Exploratory Data Analysis) for experimentation of data in A/B testing, however it still requires knowledge of Power Query/DAX function for computation that involves a combination of attributes. Knowledge of Python alone wont be adequate to achieve much to its fullest potential during EDA process.
