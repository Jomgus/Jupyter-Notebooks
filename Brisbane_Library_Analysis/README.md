# Brisbane Libraries Data Analysis
The purpose of this project is to extract insights from reader behavior in Brisbane Australia across its many different libraries.  


## Key Insights
Juveniles and Adults compete for most active readers in Brisbane. Young adult activity drops off dramatically. 

## Key Visuals

There is a dramatic -92% drop-off in young adult activity from juvenile activity. However, adult attendance recovers nicely, with a 47% increase over juveniles.

![image](https://github.com/Jomgus/Jupyter-Notebooks/assets/96961712/86ab10e4-e43e-4ed6-b084-f425465e017c)

Busiest hours across Brisbane are consistently around 10am

![image](https://github.com/Jomgus/Jupyter-Notebooks/assets/96961712/858445b1-7cc4-4638-b0c6-074f263a2913)

Young adults seem to check out exclusively graphic novels, young adult fiction, and magazines. Emphasis should be placed on these to revive young adult interest in libraries. 

![image](https://github.com/Jomgus/Jupyter-Notebooks/assets/96961712/7674d7ad-85f3-48ed-bb9c-8ff9e6134712)




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
The website listing this dataset suggests the use of an API. This would have been convenient if it weren't that the API caps data at 32,000 rows; less than half of what you'll find in the CSVs that they offer. Because of this limitation, I opted instead to choose two CSVs at random and concatenate them into the main dataframe that will be used for the rest of this project. 

## Cleaning
* Fill NA rows in Language column with ENGLISH
* Stripping unwanted characters from item titles
* Formatting Date column to datetime so that we can extract the hours later
## Supplementary Analysis

Children book authors dominate the *top 5 authors checked out* list with 3 entries. If anything, this shows there is a sort of consensus among children about their favorite books

![image](https://github.com/Jomgus/Jupyter-Notebooks/assets/96961712/80f2c84b-3cd5-4450-8cc2-51f8a17b57d3)

Most popular libraries in Brisbane

![image](https://github.com/Jomgus/Jupyter-Notebooks/assets/96961712/b1834610-12bb-4c32-9868-1866198c4b41)

---

Branch names corresponding to their headings:

| Branch Code | Branch Heading |
| ----------- | --------------------------------- |
| CDE | Chermside |
| SBK | Sunnybank Hills |
| GCY | Garden City |
| IPY | Indooroopilly |
| ASH | Ashgrove |
| WYN | Wynnum |
| BSQ | Brisbane Square Library |
| CNL | Carindale |
| MTO | Mt. Ommaney |
| KEN | Kenmore |
| GNG | Grange |
| TWG | Toowong |
| HPK | Holland Park |
| FAI | Fairfield |
| BRR | BrackenRidge |
| MIT | Mitchelton |
| BUL | Bulimba |
| NFM | New Farm |
| CPL | Coopers Plains |
| CDA | Corinda |
| MTG | Mt. Gravatt |
| NDH | Nundah |
| ZIL | Zillmere |
| SGT | Sandgate |
| EPK | Everton Park |
| INA | Inala |
| BNO | Banyo |
| HAM | Hamilton |
| SCR | Stones Corner |
| CRA | Carina |
| WND | West End |
| VAN | Mobile Library |
| ANN | Annerley |
| MBG | Mt. Coot-tha |
| POP | Pop-up library |
| MITL | Mitchelton 24/7 Library Locker |
| NFML | New Farm 24/7 Library Locker |
| CRAL | Carina 24/7 Library Locker |
| GNGL | Grange 24/7 Library Locker |
| HPKL | Holland Park 24/7 Library Locker |
| BRRL | BrackenRidge 24/7/ Library Locker |

---

Chinese is the second most checked out language, which is consistent with Mandarin being Australia's [second most spoken language](https://profile.id.com.au/australia/language#:~:text=Overall%2C%2072.0%25%20of%20the%20population,using%20this%20language%20at%20home.)

![image](https://github.com/Jomgus/Jupyter-Notebooks/assets/96961712/11b1d76c-fcd0-489a-adcf-d81929f26f2c)

Picture books are the most popular item type

![image](https://github.com/Jomgus/Jupyter-Notebooks/assets/96961712/9d9b6c56-840d-4dbf-96e8-1ff4ca7b7885)

## Recommendations:

* Focus on enhancing the collection and promotion of children's books, as they dominate the top 5 most checked-out items.
* Investigate the factors contributing to the significant drop-off in young adult readership and develop targeted strategies to reengage this age group, potentially by emphasizing paperbacks, graphic novels, and magazines.
* Optimize library operations and staff scheduling around the peak hours of 10 AM to ensure adequate resources and services are available during high-demand periods.
* Expand the collection of Chinese language materials to cater to the growing demand from the Chinese-speaking community, which represents the second-most checked out language.
