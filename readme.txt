Scraping a Particular Website

A not-for-profit company asked me to find the contact person and the mailing address of
the Community Foundations of Canada (CFC) sites across the nation.

Doing this task manually, this is, by copy-pasting each required field into a spreadsheet,
would mean doing this 195 (foundations) * 11 (fields) = 2145 times. So my next thought was
to automate the procedure by scraping the CFC website. Fortunately, all that information 
is included in their website in a straightforward schema.

Here is the code used to scrape their website, get the requested information, and write it
in the format requested into a csv file.






