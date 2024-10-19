# Buidling a Retail Data Pipeline
## Project Description
In this project, I worked with retail data from Walmart, a multinational retail corporation. I retrieved data from the sources, like csv and parquet, prepared the data using some transformation techniques, and loaded the data in an easy-to-access format. 

## Project tasks
To build a data pipeline that extracts, transforms, aggregates and loads e-commerce data, ensuring the retail information flows smoothly. 

## Installation and Setup
To work on this project, download CSV file under the folder.
If you download jupyter noteboook (ipynb) in the folder, you can see the the description, tasks and step-by-step analysis with the python script. 

## Codes and Resources Used
 - Python was used for this project
 - Python libraries: (Pandas, os)

## Technial skills 
- Python
- Data Acquisition: extracting data from structured sources
- Transforming data using filtering data using pandas
- Preliminary analysis of sales data after cleaning data using subsetting and aggregate methods
- Loading and validating the data to store the transformed data and  validating it was stored correctly. 


## Results and Evaluation 
As the result of this project I built a data pipeline to process e-commerce data that focused on grocery sales. First, I created an extract() function that read the files, and then merged the files. Second, I implemented a transform() function that processes the merged dataframe by filling missing numerical values, adding a "Month" column, filtering for weekly sales over $10000, and dropping unnecessary columns. Next, an avg_weekly_sales_per_month funciton was created ti calculate the average bmonthl sales, utilizing a chain of operations to group and aggregate the relevant data. After that, I created a load() function taht saved the cleaned and agfregated dataframes as csv files without including an index. Lastly, I created a validation() function that checks for the existence of the generated CSV files in the current working directory, ensuring that the data pipeline operates correctly from extraction to validation. 
