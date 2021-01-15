Scraping Medium with this Repository
To use this scraper to collect your own data, you simply have to clone this repository to your local drive, then acquire a few more tools to make the scraper work.

First you will need to download the Chrome Driver and place it in the same directory as the "scrape_master.py" and "medium_scraper.py" files. You will also need the following Python libraries you will need: Selenium, Pandas, BeautifulSoup.

Before you can run the scraper, you need to specify the tags and range-of-dates to scrape in the "scrape_master.py" file.





Afterwards you should be able to execute a scrape of multiple Medium tags for any range of dates by simply calling $python scrape_master.py


How it works.
This scraper pulls data from Medium's archive pages. Each archive page is associated to a story-tag and is a collection of Medium timeline cards organized by date.

Image of the "data-science" Archive


Structure of the Scraped Data
Title -title of article on timeline card
Subtitle -subtitle of article on timeline card
Image (yes/no)-whether the article has a preview image on its timeline card
Author -writer of the story
Publication - the name of the publication the article may have been posted in
Year - Month - Day-date the article was published
Tag - text
Reading Time- Time to read the article
Claps-Number of claps the article received
Comment (yes/no)-whether the entry is a comment on another article
Story Url-link to story
Author URL-link to Author's Medium homepage

Example of Data Scraped from a Timeline Card
