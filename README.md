# FlipkartDataScrape
This is the data scrapped of the E-Commerce website Flipkart where data of laptops on sale is being scrapped.

Procedure: -

I used selenium to automate the scrapping and then used BeautifulSoup to extract the html code.

I created a function to extract all the required details like Product Name ,Price , Rating out of 5, total no of Rating,Total no of Reviews,List of all the device specification.

Then created a table to scrape all the details of the remaining pages.

For simplicity I changed the data type of required columns

Then I extracted the .csv file.

Challenges: -

While extracting ratings and reviews I had to find a way out to seperate the numerical values from the string values so used split method and indexing.
