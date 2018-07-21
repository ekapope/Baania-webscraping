# Basic tool for scraping property listings from Thailand housing site, written in Python using Beautiful Soup.

Baania is one of the biggest property listing website in Thailand. This project is focused on condomenium listings in Bangkok, both new and resale.

Web scraping using bs4.
http://bannia.com/

Please note:
  1. Scraping this website is only allowed for personal use.
  2. Given the "sleep" intervals embedded in the code, it gently scrapes the pages so it will take a while to complete the operation.
  3. From observation, each results page contains roughly 18 listings. This code extracts variables from each property listing, and saves to a excel file for further analysis.
  4. The data was then cleaned and added rental/resale price per sq.m., distance to the train station column. The distance from each property to the nearest metro station is obtained from this link. https://github.com/ekapope/Estimate-distance-between-two-latitude-longitude-locations-Python-
