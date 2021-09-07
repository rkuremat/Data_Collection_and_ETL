# Data_Collection_and_ETL
I chose the 8 variables from American Community Survey (ACS) 5-Year Data on 2019 using API as follows:<br>

Variables:<br>
B01001_001E: Total_Pop<br>
B01001_002E: Total_Pop_M<br>
B01001_026E: Total_Pop_F<br>
B01002_001E: Median_Age<br>
B02001_002E: Race(White)<br>
B02001_003E: Race(African)<br>
B02001_004E: Race(NativeAmerican)<br>
B02001_005E: Race(Asian)<br>

This is because I am interested in the relation between median age, sex and race.<br>

After extracting data from ACS data site, create pandas DataFrame.<br>
When I created a table, I set state, county, track block_group as primary keys.<br>

Once I converted DataFrame to csv file and inserted the data into the table because I read the article that said this way is very fast.<br>
https://towardsdatascience.com/upload-your-pandas-dataframe-to-your-database-10x-faster-eb6dc6609ddf


