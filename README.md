# Amazon India Products Scraping

## There are two separate links we scrap in this project

## 1. Amazon Search Page to get Product Links
## 2. Amazon Product Pages scraped from Search Page to get Product data like Product Name, Images, Price, Description, etc.
### Note : This project is developed in Python 3.

## Scraping Amazon Search Page using following steps

### 1. Importing the required libraries.
### 2. Creating the search link using Amazon's search query page link.
### 3. Scraping all the product names and links using Beautiful Soup find method.
### 4. Saving all the scraped data in csv using pandas.

## Scraping Amazon Product Details

### 1. Importing the required libraries.
### 2. Getting Product Links using csv saved from first scraping.
### 3. Make Functions to clean scraped data like removing \n and extra whitespaces from HTML content.
### 4. Make a pandas Dataframe to store scraped data from Amazon Product Page.
### 5. Now, scraping of the product page is divided into multiple steps as follows:
### 5.1. Scrap the Product Name, Category, Price, Seller, Terms and Conditions using the unique tags and remove the unnecessary tags and characters using the functions defined earlier.
### 5.2. The primary image of the product has different HTML tag for every product than other images. So, fetch the primary image, save it in a list.
### 5.3. Append all the other images for the product in the same list.
### 4. Using os library to make a directory in the same folder as the python notebook, fetch the image link using requests and save the image using shutil.
### 5. After the images are saved in a local directory successfully, add the scraped data for the product in pandas Dataframe and convert it to csv for further usage.

## Some optimisation to this project will be added in future.