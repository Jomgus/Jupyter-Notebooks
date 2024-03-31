# San Francisco City Employee Salary Analysis

An exploratory analysis of San Francisco city employee salaries, investigating salary distributions, job roles, and compensation components to uncover insights into the city's workforce and priorities, with a focus on the highly-paid transit-related positions.

## Key Insights

**Transit-related job roles were among the highest-paid and most common positions, reflecting the city's investment in public transportation infrastructure.**

## Key Visuals

Pay distribution across salaries. Hue set to year shows how while the trend remains consistant, there is less data for the later years.

![image](https://github.com/Jomgus/Jupyter-Notebooks/assets/96961712/f14bb278-95b1-4b43-ac9a-42572dceb11f)

Salary by occupation reveals transit authority general managers are emphasized in the city

![image](https://github.com/Jomgus/Jupyter-Notebooks/assets/96961712/2e60eb06-e6c8-4c32-a655-379f9249d20b)

The *Most Common Occupations* chart further corroborates this emphasis on transity authority with transit jobs headlining here as well

![image](https://github.com/Jomgus/Jupyter-Notebooks/assets/96961712/e81fdc06-376b-4f90-bac9-588403ad247f)


### Data Source
* [Source](https://transparentcalifornia.com/salaries/san-francisco/)
* [License](https://creativecommons.org/publicdomain/zero/1.0/)

### Methods Used
* Querying relevant data from database
* Data Cleaning and Transforming
* Data Visualization

### Technologies
* DBeaver
* MySQL
* Python
* Pandas
* Seaborn
* Matplotlib

## Data Sourcing
Downloaded and inserted provided CSV of 148,000 rows into a **mySQL** table. From there, the relevant columns were queried before being exported as a CSV and read through **Pandas** 

* [original](San_Fran_Analysis/dataset/Salaries_Analysis.csv) 
* [transformed](San_Fran_Analysis/dataset/Salaries.csv)

## Cleaning
* Replaced *Not Provided* string values with null values which allowed for the columns to be converted to datatype float

## Recommendations
* Continue to prioritize and invest in transit-related roles and infrastructure, as these positions seem to be highly valued and well-compensated within the city's workforce.
* Conduct further analysis to understand the specific skills, qualifications, and responsibilities associated with the top-paying transit roles, and ensure that the city's recruitment and compensation strategies align with attracting and retaining top talent in these critical areas.
