# Indeed-Job-Scrapping
Using python to scrap data analyst job on Indeed and turn them into csv file. 

So you’re in the job market, and you want to work smarter rather than harder at finding new and interesting jobs for yourself? Why not build a web scraper to collect and parse out job posting information for you? Set it, forget it, and come back to your data riches in a nice tidy format! How, you ask? Let’s take a look together

For this project, I wanted to explore data science-related jobs posted to a variety of cities on indeed.com, a job aggregator that updates multiple times daily. I conducted my scraping using the “requests” and “BeautifulSoup” libraries in python to gather and parse information from indeed’s pages, before using the “pandas” library to assemble my data into a dataframe for further cleaning and analysis.

All of the information on this page is coded with HTML tags. HTML (HyperText Markup Language), is the coding that tells your internet browser how to display a given page’s contents upon accessing it. This includes its basic structure and order. HTML tags also have attributes that are a helpful way of keeping track of what information can be found where within the structure of the page.

In the near future, I’ll post again to describe how I used this data further to examine what sorts of jobs were available, and my attempts to classify whether jobs with no salary information would be above or below the median salary of those jobs I collected that did have salary information.

