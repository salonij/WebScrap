# WebScrap
scraping stackoverflow.com website to get the list of job openings .
- Aim to scrap job opening details from stackoverflow website is accomplished using BeautifulSoup library in python.
- BeautifulSoup library is used to fetch the 'div' that contains list of job openings from website .
- Then link of each job's description is fetched from 'a' tag and json file containing information of each job 
  is fetched from 'script' tag.
- Json library is used to parse json data and to fetch useful job information .
- Pandas library is used to store the details in Dataframe for better visualization of data and also to export data 
  to excel sheet.
