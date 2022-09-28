# Mission-to-Mars
27 SEP 2022 - Revisited this project to demo it for a friend and it is no longer working. It seems something has run afoul of Content Security Policy and will not allow certain scraped items to display in the flask app. Unfortunately I am not sure where to start to resolve this. I believe we were given a workaround to prevent this while we were working on this assignment, but I can't recall what it was. I will try to come back to this repo in the future to get it working. You can see my current work here. 

Dependencies Needed: flask, flask_pymongo, scraping, splinter, bs4, and chromedriver.exe. Please make sure chromedriver.exe is saved in the same folder as app.py. 

## Project Purpose and Summary
The purpose of this project was to write a scraping program using Python, use MongoDB to store the scraped data, and then use Flask to build a website that can display the scraped data. Various information about Mars was scraped using a Python script from several different websites. The data scraped included the most recent news headline and summary about NASA's Mars Mission, a "featured image", facts about Mars, weather on Mars, and pictures of Mars' hemispheres. This data was then stored in a MongoDB database to be accessed by our Flask application. A Flask app was then created that would visualize the information that had been scraped. The app also includes a button to scrape for new data, and update the images and stories with the most recent ones. Finally the app was customized using bootstrap to make it visually appealing, and to display on both desktop and mobile devices. 
