Web Scraping with Beautiful Soup — A Use Case

https://towardsdatascience.com/web-scraping-with-beautiful-soup-a-use-case-fc1c60c8005d

In this notebook, I will give a brief introduction to obtaining data from a webpage,
i.e., web scraping, using Python and libraries such as Requests to get the data and
Beautiful Soup to parse it. Web scraping becomes necessary when a website does not 
have an API, or one that suits your needs.

As an example, I use a webpage that has a consistent HTML structure, but this approach
can be generalized. While there are some frameworks, such as Scrapy, that can provide 
such service, I decided to this as a learning experience.

The Use Case 

A not-for-profit organization wants to reach out to the Community Foundations of Canada
(CFC) sites across the nation. They asked me to find each contact person and their mailing 
address, and put all the information in a special format in a spreadsheet.

Doing this task manually, by copy-pasting each required field into the spreadsheet, would
mean doing this 195 (foundations) * 11 (fields) = 2145 times! So my next thought was to
automate the procedure by scraping the CFC website.

Here is the code used to scrape their website, get the requested information, and write it
in the format requested into a CSV file.






