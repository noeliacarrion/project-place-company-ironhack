# Project "Best place for a game company"

### The aim of this project is to find the best location for a company in the gaming industry to grow. 
The repository contains the following files:
  - Folder "out" with the databases(after cleaned and after geoqueries) and the maps
  - 2 Jupyter notebook with de code. The first one contains all the data cleaning, the other one the geoquery and the request to Google API
  
### Requeriments

- First of all, it's important to stay near to other tech new companies, so I've categorized the type of each company.

- My first decition was to select companies which were founded beetween 2009 and 2019 but the database contained values to 2013, so I've modified the requirements and select companies from 2007.

- I was looking for locationes where the total money raised was at least 1 million. 

- To expand the gaming industry I've decided to find locations out USA and see what kind of companies there are in other countries.

- It's important the satisfaction's employees(30% of them have at least 1 child) as well as executives. For that reason, I've used Google API to find close to the radius schools or kindergarten and Starbucks.

### Cleaning process

I've cleaned the database with all requeriments except the total money raised. Before selecting companies by money I was forced to normalize the values of total money raised. 

### Geoqueries and Google API

Using pymongo I've found the companies nearest to others. After that, I've performed some calculations to determine the money by office, the employees by office and a simple ranking by money, employee and the number of offices around. After sorting by ranking I've found that the best location is Vancouver in Canada but I wanted to keep in mind other requeriments like schools and Starbucks. 

### Results

After all the process, the best location to the company is East Hastings Street(Vancouver, Canada). There are two companies with an important total money raise, and a number of employees according to our company. In the radius it is located Hootsuite, one of the most important companies in technology field. I've found too 3 schools close to that street, so it seems to be a good location.

The principal map was made with Folium but it's available a link to Tableau with some graphics https://public.tableau.com/profile/noelia3261#!/vizhome/Bestplaceforagamecompany/Historia1?publish=yes

To summarize, I invite you to read this article about the impact of gaming industry on Canada.

https://betakit.com/report-canadas-gaming-industry-contributes-3-7-billion-to-economy/
