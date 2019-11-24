# Germany_University_Database
A  creation of MySQL database for German Universities using Python

"https://en.wikipedia.org/wiki/List_of_universities_in_Germany" page lists the universities in Germany. 
The web page was scraped using BeautifulSoup and the information for each university was then extracted and stored in a form of data frame.

The collected data was then cleaned, organised to make meaningful data from it.
The universites were visualized on the map of Germany and then the GeoJSON file containing the information of the states of Germany, was used along with  '.csv' file to create a chorpleth, indicating the distribution of the universities across German states.

The data also visualized the Academic and the Administrative staff along with the number of students in the top 20 universities with highest budgets.

The data frames were converted to the tables in MySQL tables after creating the database using Python. The stored data was then retrieved into the dataframes, thus depicting the ease of data transfer between MySQL and Python data frames using the mysql and sqlalchemy packages.

