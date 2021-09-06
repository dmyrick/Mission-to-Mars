# Mission-to-Mars

## Purpose
The purpose of this project was to web scrape data from different websites concerning Mars. The tools used were Python, Flask, MongoDB, Web-Driver Manager, BeautifulSoup, and Splinter. The web application will be updated automatically when the data extracted is scraped. The following was extracted:
  1. Current title and corresponding summary from the NASA news webpage.
  
  ![ScreenShot](https://github.com/dmyrick/Mission-to-Mars/blob/main/Resources/title_summary.png)
  
  2. Featured images from the Jet Propulsion Laboratory's Space Images webpage.
  
  ![ScreenShot](https://github.com/dmyrick/Mission-to-Mars/blob/main/Resources/featured_img.png)
  
  3. Collect data to input into a table from the Mars Facts webpage.

![ScreenShot](https://github.com/dmyrick/Mission-to-Mars/blob/main/Resources/mars_facts.png)

  4. Images of Mars's hemispheres from the Mars Hemispheres webpage. Once the scraped data listed above and images of Mars’s hemispheres and titles were stored on a Mongo database, a web application was used to display the data. Additionally, CSS Bootstrap was used to update the button's background to green and add the hemisphere images as thumbnails. 

![ScreenShot](https://github.com/dmyrick/Mission-to-Mars/blob/main/Resources/planets.png)
