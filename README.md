# Contoso-Data-Modeling

#  Objective:
This project takes together 20 million data points from huge datasets and establishes a beneficial relationship between them for the data modeling technique. then this dashboard is to provide a detailed analysis of sales data across product categories, promotions, and geographical regions, enabling stakeholders to identify top-performing categories, evaluate promotion effectiveness, understand regional sales distribution, and recognize individual contributions.

#  Steps:
##  Identification of data:
    • Download the data set with all reference about the file from kaggle.
    • Separate the fact tables and dimension tables
    • Fact tables:
    • Fact tables contain quantitative data, such as sales amounts, quantities, costs, and other metrics that can be measured and aggregated.
    • Dimension tables: Dimension tables contain descriptive attributes that provide context and meaning to the data in fact tables. These attributes are often textual but can also be numerical or date/time data.
    • Find the keys are,
        • Primary Key - a Primary Key is a specific choice of a minimal set of attributes that uniquely specify a tuple in a relation.
        • Self reference key – self referencing to the own table.
        • Foreign Key – Foreign Keys that reference Primary Keys to establish the relationships between the fact table and the associated dimension tables.

##  Import the data:
    • Using “Get Data”, we can upload the csv format data file.
    • Apply it for each 25 files separately.
##  Set up Relationships:
    -  After loading the data, go to "Model".
    -  Establish relationships between your dimension and fact tables based on
    the keys provided.
##  Establishing the Relationships:
    1. Navigate to the Model View:
    • select the "Model" icon on the left sidebar.
    2. Drag and Drop Keys:
    • Drag the PK from each dimension table to the corresponding FK in
    the fact table.
    3. Verifying the Relationships:
    • Ensure that relationships are correctly set up and marked with the
    correct cardinality.
##  Apply and Close:
    • Click on "Close & Apply" to save your changes and load the data model
    into Power BI for further analysis and visualization.
##  Check the data integrity:
    Once all relationships are set up, validate the data integrity by creating some
    basic visualizations to ensure the relationships are working as expected.
##  Visualizations:
    1. Stacked Bar Chart: Sales by Product Category
    2. Column Chart: Promotion impact in Sales Amount
    3. Map View: Sales by Area
    4. Table View: Employees Sales Performance
##  Data Modeling:
    • Connection Established: 43 active connections.
##  Save the file:
    Save the file .pbix format
File: https://drive.google.com/drive/folders/1HrHs3bMsSugzyEqlo12FfvXrquv9DxMy?usp=sharing

##  Result:
This dashboard provides a comprehensive overview of sales data, allowing users to understand sales performance across different product categories, promotions, and geographical areas. The combination of bar charts, a map, a table, and a donut chart offers multiple perspectives on the data, aiding in effective decision-making.

Dashboard:
![Screenshot 2024-07-26 112033](https://github.com/user-attachments/assets/fb3e09b6-5a51-4326-9789-7f5440447dba)
