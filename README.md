# Mission_to_Mars

Webscraping is a method of getting data from web sources quickly instead of manually extracting the data from each website yourself. We use Chrome Developer Tools to identify HTML components. We also use BeautifulSoup and Splinter to automate the scrape. We will use Mongo to store the data, and to display the data we will use Flask. Any business can find a benefit to webscraping. For instance, a company may be able to monitor its own, or its competitors brand reputation.

The first step is understanding how a webpage is built. Every webpage is put tofether using some combination of Javascript, HTML, and CSS. After getting familiar with how the target sites are built, a programmer can write a Python script that utilizes the libraries BeautifulSoup and Splinter. Splinter is the tool tat automates a web browser, and BeautifulSoup will extract data from the websites. We then store the data into a NoSQL database, MongoDB. NoSQL databases store data that isn't as structured or clean as the data that may store into an SQL database. A key characteristic of NoSQL and SQL databases is that NoSQL databases hold data that have no real relationships to one another, and the data is stored within JSON data structures. To show off our analytics we will build a web application with Flask. With Flask we can update the scraping code and update the page with the most recent data.

In this project we will write a script that can collect all relevant information regarding the mission to mars, and then building an online portfolio to show off to others, and perhaps even NASA!

Steps:
