# Brisbane Libraries Data Analysis
The purpose of this project is to extract insights from reader behavior in Brisbane Australia across its many different libraries.  


## Key Insights
Juveniles and Adults compete for most active readers in Brisbane. Young adult activity drops off dramatically. 

## Key Visuals
![image](https://github.com/Jomgus/Jupyter-Notebooks/assets/96961712/86ab10e4-e43e-4ed6-b084-f425465e017c)

There is a dramatic -92% drop-off in young adult activity from juvenile activity. However, adult attendance recovers nicely, with a 47% increase over juveniles.

![image](https://github.com/Jomgus/Jupyter-Notebooks/assets/96961712/858445b1-7cc4-4638-b0c6-074f263a2913)

Busiest hours across Brisbane are consistently around 10am

![image](https://github.com/Jomgus/Jupyter-Notebooks/assets/96961712/7674d7ad-85f3-48ed-bb9c-8ff9e6134712)

Young adults seem to check out exclusively paperbacks, graphic novels, and magazines. Emphasis should be placed on these to revive young adult interest in libraries. 





### Data Source
* [Brisbane City Council](https://www.data.brisbane.qld.gov.au/data/dataset/library-checkouts-branch-date)
* [License](https://creativecommons.org/licenses/by/4.0/)

### Methods Used
* Data Cleaning and Transforming
* Data Visualization
* API calling
* Inferential Statistics

### Technologies
* Python
* Matplotlib
* Pandas
* Jupyter
* Numpy

## Data Sourcing
The website listing this dataset suggest the use of an API. This would have been convenient if it weren't that the API caps data at 32,000 rows, less than half of a single CSV they offer. Because of this limitation, I opted instead to choose two CSVs at random and concatenated them into the main dataframe that will be used for the rest of this project. 

## Cleaning
* Fill NA rows in Language column with ENGLISH
* Stripping unwanted characters from item titles
* Formatting Date column to datetime so that we can extract the hours later
## Supplementary Analysis
![image](https://github.com/Jomgus/Jupyter-Notebooks/assets/96961712/508b96bc-f96a-444d-b44a-3fad29944d9c)

Children books dominate the top 5 items checked out list with 3 entries. If anything, this shows there is a sort of consensus among children about their favorite books

![image](https://github.com/Jomgus/Jupyter-Notebooks/assets/96961712/b1834610-12bb-4c32-9868-1866198c4b41)

Most popular libraries in Brisbane

| Branch Code | Branch Heading                    |
| ----------- | --------------------------------- |
| MITL        | Mitchelton 24/7 Library Locker    |
| VAN         | Mobile Library                    |
| MBG         | Mt. Coot-tha                      |
| MTG         | Mt. Gravatt                       |
| MTO         | Mt. Ommaney                       |
| NFM         | New Farm                          |
| NFML        | New Farm 24/7 Library Locker      |
| NDH         | Nundah                            |
| POP         | Pop-up library                    |
| SGT         | Sandgate                          |
| SCR         | Stones Corner                     |
| SBK         | Sunnybank Hills                   |
| TWG         | Toowong                           |
| WND         | West End                          |
| WYN         | Wynnum                            |
| ZIL         | Zillmere                          |
| BSQ         | Brisbane Square Library           |
| BUL         | Bulimba                           |
| CRA         | Carina                            |
| CRAL        | Carina 24/7 Library Locker        |
| CNL         | Carindale                         |
| CDE         | Chermside                         |
| CPL         | Coopers Plains                    |
| CDA         | Corinda                           |
| EPK         | Everton Park                      |
| FAI         | Fairfield                         |
| GCY         | Garden City                       |
| GNG         | Grange                            |
| GNGL        | Grange 24/7 Library Locker        |
| HAM         | Hamilton                          |
| HPK         | Holland Park                      |
| HPKL        | Holland Park 24/7 Library Locker  |
| INA         | Inala                             |
| IPY         | Indooroopilly                     |
| KEN         | Kenmore                           |
| MIT         | Mitchelton                        |
| ANN         | Annerley                          |
| ASH         | Ashgrove                          |
| BNO         | Banyo                             |
| BRR         | BrackenRidge                      |
| BRRL        | BrackenRidge 24/7/ Library Locker |

![image](https://github.com/Jomgus/Jupyter-Notebooks/assets/96961712/cf7c99f8-ddfc-482f-bfc0-231d50937bb0)

Chinese is the second most checked out language, which is consistent with Mandarin being Australia's [second most spoken language](https://profile.id.com.au/australia/language#:~:text=Overall%2C%2072.0%25%20of%20the%20population,using%20this%20language%20at%20home.)

![image](https://github.com/Jomgus/Jupyter-Notebooks/assets/96961712/9d9b6c56-840d-4dbf-96e8-1ff4ca7b7885)

Recommendations:

* Focus on enhancing the collection and promotion of children's books, as they dominate the top 5 most checked-out items.
* Investigate the factors contributing to the significant drop-off in young adult readership and develop targeted strategies to reengage this age group, potentially by emphasizing paperbacks, graphic novels, and magazines.
* Optimize library operations and staff scheduling around the peak hours of 10 AM to ensure adequate resources and services are available during high-demand periods.
* Expand the collection of Chinese language materials to cater to the growing demand from the Chinese-speaking community, which represents the second-most checked out language.
