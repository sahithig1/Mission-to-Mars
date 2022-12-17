
                                                                                           Michelle Werner (6/12/2022)
# Mission to Mars: Web Scraping for NASA
---

<!--![alt](resources/___.png)-->
<img src="https://github.com/miwermi/mission-to-mars/blob/main/assets/amazing-mars.png" align="right" width="500" height="293" alt ="graphic: Amazing Mars">

## Project Overview

Junior data Scientist Robin does freelance astronomy work and hopes to work for NASA someday.  She spends a lot of time reading web articles and is currently fascinated with Mars.  For this project, I've helped Robin code a web scraper that puts together Mars data from several different sites:  

- MARS Planet Science (https://redplanetscience.com)
- California Institute of Technology's Jet Propulsion Lab (https://spaceimages-mars.com)
- Galaxy Facts on Mars (https://galaxyfacts-mars.com)
- Astropedia's Lunar and Planetary Cartographic Catalog (https://marshemispheres.com)

Figure 1: Robin and her telescope looking up at amazing Mars!

<img src="https://github.com/miwermi/mission-to-mars/blob/main/assets/web-scraping-flask-to-mongo.png" align="right" width="500" height="293" alt ="graphic: Flask to Mongo Web Scraping">

## Tech Specs

To show Robin my work, I've created an HTML index that populates with Flask from Python code and a Mongo database.  Each time my python code is run, each of the sites we're pulling from is visited and scraped with the help of Splinter and Beautiful Soup, and my Python code collects and stores as new batch of info in my Mongo database. Last but not least, the Mongo data is called back and my web page is rebuilt!

For presentation, i've used mobile friendly CSS components and used some of the Bootstrp 3 coponents. Overall, this exercise was fun to extract(scrape) data from multiple websites, use frameworks such as splinter and beautiful soup to present data in my own website, all by connecting to MongoDB.

Figure 2: Web Scraping with Splinter, Flask, Mongo and Python


## Webpage Preview

Following screenshots demonstrate data extracted for both Mars mission and mars hemispheres.

![Mars](https://user-images.githubusercontent.com/55648656/208264839-a4d80bf2-81d5-41af-9d63-ec5dde40f029.jpg)
![Hemispheres](https://user-images.githubusercontent.com/55648656/208264827-9ccdceed-869a-461a-8e8b-4b9e5f0797da.jpg)

