Scripting Challenge - Bootcamp Module #11

Introduction:

In this challenge, we were tasked with scraping text from a website. We leveraged the package, BeautifulSoup, to parse and extract the text elements from a website. Next, we scraped a table from a website and converted the object to a pandas dataframe. After converting the object to a pandas dataframe, we performed some analysis on the dataframe.   

Scrape Title & Preview Text from Mars News:

Used BeautifulSoup to scrape text and title from website. I then created an empty list to store dictionaries for each title and preview article. I used a for loop to extract each of the text elements and w/in the loop extracted the title and preview text elements. Finally, I appended the text elements to the empty list previously created.

Scrape & Analyze Mars Weather Data:

For this portion, I scraped a table using BeautifulSoup. I extracted all headers and rows from the table. Next, I created an empty list from which to append the headers using a for loop. Then I initialized a dataframe comprising the headers. I proceeded to add the row level data to the previously created dataframe. Finally, I analyzed the data using groupby and various aggregation funcitons.

Resources Used:

Scraping from a Table Using Beautiful Soup https://www.youtube.com/watch?v=SydCFe5eF4o](https://www.youtube.com/watch?v=aGCyqj8nPKw)https://www.youtube.com/watch?v=aGCyqj8nPKw
