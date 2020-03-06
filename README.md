# NPI_Crawler

## Requirements
1. NPI_crawler uses Chrome as the browser for crawling (i.e.,web driver)
2. v. Chrome >= 80.0
3. If your Chrome's version is other than 80.0, please download the [webdriver] (https://chromedriver.chromium.org/downloads) associated with your current chrome version.
4. AND put your unzipped Chrome Driver in the bin fold under home directory 
5. The input file type is a txt file with delimiter ',' 
6. The output database by default saved in the directory of crawler

## Functionality of this crawler 
1. This crawler use web driver to submit npi id to target website, and scrape/parse data from the html. 
2. This crawler allow users to resume crawling from where stopped last time
3. This crawler utilizes sqlite3 as database
