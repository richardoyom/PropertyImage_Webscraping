# PropertyImage_Webscraping
A code that downloads images using beautifulsoup

This Python script scrapes images from a given property listing page on nigeriapropertycentre.com. It specifically targets images associated with property listings and downloads them to a local directory.

The script:

Sends a GET request to the specified webpage.
Extracts image URLs from <img> tags using BeautifulSoup.
Modifies each image URL by adding /thumbs/ to the path.
Downloads the images and saves them in a folder named images within the user's Downloads directory (C:\Users\HP\Downloads\images).
Each image is saved as image_1.jpg, image_2.jpg, etc.
This script is useful for bulk downloading property images from the specified webpage while ensuring a resized version (via the /thumbs/ URL modification) is fetched.
