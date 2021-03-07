# Missions-to-Mars
# Project Overview
#### Robin's web app is looking good and functioning well, but she wants to add more polish to it. She had been admiring images of Mars’s hemispheres online and realized that the site is scraping-friendly. She would like to adjust the current web app to include all four of the hemisphere images. To do this, you’ll use BeautifulSoup and Splinter to scrape full-resolution images of Mars’s hemispheres and the titles of those images, store the scraped data on a Mongo database, use a web application to display the data, and alter the design of the web app to accommodate these images.

## Project Deliverables
1. Scrape Full-Resolution Mars Hemisphere Images and Titles
2. Update the Web App with Mars Hemisphere Images and Titles
3.  Add Bootstrap 3 Components

## Resources
* Data Source: `Mission_to_Mars.ipynb` , `app.py` , `scraping.py` and `index.html`
* Software/Tools: MongoDB 4.4.3, Visual Studio Code 1.54.1, Flask Version 1.1.2,  Jupyter Notebook, 6.1.4 Python 3.8.5

## Deliverable 1: Scrape Full-Resolution Mars Hemisphere Images and Titles
> Using BeautifulSoup and Splinter, you’ll scrape full-resolution images of Mars’s hemispheres and the titles of those images.
### Requirements with screenshots:
1. Code is written that retrieves the full-resolution image and title for each hemisphere image 
![2](https://user-images.githubusercontent.com/76136277/110252669-81682a80-7f54-11eb-9508-7bf9731421b4.PNG)
2. The full-resolution images of the hemispheres are added to the dictionary. 
3. The titles for the hemisphere images are added to the dictionary. 
![3](https://user-images.githubusercontent.com/76136277/110252684-91800a00-7f54-11eb-8d4a-5d4b7a1fc10d.PNG)
4. The list contains the dictionary of the full-resolution image URL string and title for each hemisphere image. 
![4](https://user-images.githubusercontent.com/76136277/110252688-9f358f80-7f54-11eb-8314-c29b009f90a4.PNG)

## Deliverable 2: Update the Web App with Mars’s Hemisphere Images and Titles
> Using your Python and HTML skills, you’ll add the code you created in Deliverable 1 to your `scraping.py` file, update your Mongo database, and modify your `index.html` file so the webpage contains all the information you collected in this module as well as the full-resolution image and title for each hemisphere image.
### Requirements:
1. The `scraping.py` file contains code that retrieves the full-resolution image URL and title for each hemisphere image
![2](https://user-images.githubusercontent.com/76136277/110253486-9a72da80-7f58-11eb-80be-c215179667c3.PNG)
![3](https://user-images.githubusercontent.com/76136277/110253489-a52d6f80-7f58-11eb-8574-9d2d1af13e8e.PNG)
2. The Mongo database is updated to contain the full-resolution image URL and title for each hemisphere image 
![9](https://user-images.githubusercontent.com/76136277/110254237-5b468880-7f5c-11eb-95c4-7aab2ee3d3d4.PNG)
3. The `index.html` file contains code that will display the full-resolution image URL and title for each hemisphere image 
![7](https://user-images.githubusercontent.com/76136277/110253694-b9be3780-7f59-11eb-839d-1650d36c5969.PNG)
4. After the scraping has been completed, the web app contains all the information from this module and the full-resolution images and titles for the four hemisphere images
![2021-03-07 (6)](https://user-images.githubusercontent.com/76136277/110254758-7ca87400-7f5e-11eb-9c9a-a4e943689d85.png)

## Deliverable 3: Add Bootstrap 3 Components
> For this part of the Challenge, update your web app to make it mobile-responsive, and add two additional Bootstrap 3 components to make it stand out.
### Requirements:
1. The webpage is mobile-responsive
![2021-03-07 (11)_LI](https://user-images.githubusercontent.com/76136277/110254998-aa41ed00-7f5f-11eb-8ecf-76f5c8115e64.jpg)

2. Two additional Bootstrap 3 components are used to style the webpage 
    * Styling the "Scrape New Data" button - The background color was changed from red to black, as seen in the image below;
    ![2](https://user-images.githubusercontent.com/76136277/110255959-584f9600-7f64-11eb-848a-da8c91d36f0a.PNG)  
    
    * Customizing the facts table.      
    ![3](https://user-images.githubusercontent.com/76136277/110256634-e2e5c480-7f67-11eb-81d5-f685e6894dd8.PNG)
     
### Updated View of the web app

![2021-03-07 (3)](https://user-images.githubusercontent.com/76136277/110258712-001f9080-7f72-11eb-9e6d-5d7819dbbc9d.png)
