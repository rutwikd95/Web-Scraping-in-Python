# Web-Scraping-in-Python

- We use "request" to grab the data from the Url.

- Using BeautifulSoup, we get the required table from the webpage contents.

- Using Table Rows (tr) and Table Data (td) , we get the required fields and records form the table and store it in an empty list data[].

- We separate the cells with pdf because that is what we are trying to grab from the webpage.

- We arrange all the grabbed data in a DataFrame with "Date" and "Report" as column names.

