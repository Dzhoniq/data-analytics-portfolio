# Cleaning Bank Marketing Campaign Data
## Project Description
In this project we have been asked to work with a bank to clean the data they collected as part of recent marketing campaign. The campaign aimed to get customers to get customers to take out a personal loan. They want to conduct more marketing campaigns in the future, and they would like to ensure it conforms to the specific structure and data types so that they can then use the cleaned data you provide to set up a PostgreSQL database, which will store this campaign's data and allow data from future campaigns to be easily imported. 

## Project tasks
To clean, reformat, and split the data, saving three final csv files. Each file has the names and contents as required below:
## `client.csv`

| column | data type | description | cleaning requirements |
|--------|-----------|-------------|-----------------------|
| `client_id` | `integer` | Client ID | N/A |
| `age` | `integer` | Client's age in years | N/A |
| `job` | `object` | Client's type of job | Change `"."` to `"_"` |
| `marital` | `object` | Client's marital status | N/A |
| `education` | `object` | Client's level of education | Change `"."` to `"_"` and `"unknown"` to `np.NaN` |
| `credit_default` | `bool` | Whether the client's credit is in default | Convert to `boolean` data type:<br> `1` if `"yes"`, otherwise `0` |
| `mortgage` | `bool` | Whether the client has an existing mortgage (housing loan) | Convert to boolean data type:<br> `1` if `"yes"`, otherwise `0` |

<br>

## `campaign.csv`

| column | data type | description | cleaning requirements |
|--------|-----------|-------------|-----------------------|
| `client_id` | `integer` | Client ID | N/A |
| `number_contacts` | `integer` | Number of contact attempts to the client in the current campaign | N/A |
| `contact_duration` | `integer` | Last contact duration in seconds | N/A |
| `previous_campaign_contacts` | `integer` | Number of contact attempts to the client in the previous campaign | N/A |
| `previous_outcome` | `bool` | Outcome of the previous campaign | Convert to boolean data type:<br> `1` if `"success"`, otherwise `0`. |
| `campaign_outcome` | `bool` | Outcome of the current campaign | Convert to boolean data type:<br> `1` if `"yes"`, otherwise `0`. |
| `last_contact_date` | `datetime` | Last date the client was contacted | Create from a combination of `day`, `month`, and a newly created `year` column (which should have a value of `2022`); <br> **Format =** `"YYYY-MM-DD"` |

<br>


## Installation and Setup
To work on this project, download CSV file under the folder.
If you download jupyter noteboook (ipynb) in the folder, you can see the the description, tasks and step-by-step data cleaning and saving data using Python scripts. 

## Codes and Resources Used
 - Python was used for this project
 - Python libraries: (Numpy, Pandas, Dateetime)

## Technial skills 
- Python
- Data Acquisition: upload csv file
- Data-cleaning skills
- Data splitting 
- Data saving into csv files


## Results and Evaluation 
I started by reading the cleaning requirements. Then I split the main data source into three dataframes. As part of the clening rquirements, I modified values, added new features, and converted data types. Finaly, after ensureing that all cleaning requirements were implemented, I saved data into multiple files.


