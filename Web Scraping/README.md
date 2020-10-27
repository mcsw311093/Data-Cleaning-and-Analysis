# Web Scraping SEC using Beautiful Soup
Web Scraping SEC Financial Statements Balance Sheet

Each folder has Part 1 and part 2. 

Part1 - Aquiring and Parsing html code for each filing. 
Output - Each filing is saved as a CSV file, multiple CSV files delimited by year.  

Part2 - Concatenating each filing into a row of a dataframe. 
Output - Single Dataframe for stated company and certain period. 

Limitations - Variations within company filing over the years are inconsistent. Need to manually go through to finesse parsing specific periods. 

</br>
UniversalV1.ipynb work in progress... 

UniversalV1.ipynb was an attempt to create a master scraper for all companies by leveraging on the table of contents <href> tag. 
Currently UniversalV1.ipynb is only able to scrape Balance Sheet of Microsft from 2012 to Present. 
