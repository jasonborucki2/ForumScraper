# ForumScraper
Uses Beautiful Soup to scrape all 8500 threads in one of the most popular online forums of the last 20 years.

The end result is a dictionary containing all threads created including their authors, number of views, replies, and ratings. 

The GetThreads class takes all the lists of the HTML elements that isolates each threads creator and all other associated elements.

The scrapeThreads function takes in a page number and calls the beautiful soup module and extracts all the information that will be imported into the class.
From here, the class extracts all the necessary information and uploads it into a python dictionary. 
