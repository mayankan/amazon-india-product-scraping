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

## Scraping Amazon Images <--The Most difficult detailt to scrap on Amazon-->

### 1. Importing the required libraries.
### 2. Getting Product Links using csv saved from first scraping.
### 3. Now, scraping of the product page is divided into two steps as follows:
### 3.1. The primary image of the product has different HTML tag for every product than other images. So, fetch the primary image, save it in a list.
### 3.2. Append all the other images for the product in the same list.
### 4. Using os library to make a directory in the same folder as the python notebook, fetch the image link using requests and save the image using shutil.

## Some modifications to this project for more features will be added in future.
