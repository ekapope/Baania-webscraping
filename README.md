# Basic tool for scraping property listings from Thailand housing site, written in Python using Beautiful Soup.

This is the first episode of web scraping project which focused on condomenium listings in Bangkok, Thailand. You can find my second project [here](https://github.com/ekapope/web-scraping-using-selenium-and-bs4).

Baania is one of the biggest property listing website in Thailand. This project is focused on condomenium listings in Bangkok, both new and resale.

http://bannia.com/

Web scraping using bs4.

001_CondoScraping_gh.ipynb : To obtain all links for every condomenium listed in the website.

002_CondoScraping_gh.ipynb : To scrape the infos and store in excel file.

Condo_info_Combined - Cleaned.xlsx : Clean Data for first glance in MS Power BI


Please note:
  1. Scraping this website is only allowed for personal use.
  2. Given the "sleep" intervals embedded in the code, it gently scrapes the pages so it will take a while to complete the operation.
  3. From observation, each results page contains roughly 18 listings. This code extracts variables from each property listing, and saves to a excel file for further analysis.
  4. The data was then cleaned and added rental/resale price per sq.m., distance to the train station column. The distance from each property to the nearest metro station is obtained from this [link.](https://github.com/ekapope/Estimate-distance-between-two-latitude-longitude-locations-Python-)


# Data Visualization using Microsoft Power BI.
The data is then imported and visualized via MS Power BI, follow this [link](https://app.powerbi.com/view?r=eyJrIjoiZWI0MTc3MWMtMDU2MC00MGYyLWI1N2UtZmY1NDkwMGViMjI5IiwidCI6IjA4OTgzZGFmLTVhY2EtNGY0NC1iYzY1LWMyM2NlMzJkNDZlYyIsImMiOjh9) for the dashboard.



[Thanks to this author for Power BI project inspiration.](https://www.accelerating.tech/blog/visualizing-real-estate-markets-with-power-bi/)
