###Status : 
  * Date : 24-8-15
  	* got the list of restaurants near the bangalore area and stored the list in [burrp_bangalore.txt](https://github.com/prodicus/big_data_project/blob/master/bin/burrp_bangalore.txt)
  	* using that list [burrp_bangalore.txt](https://github.com/prodicus/big_data_project/blob/master/bin/burrp_bangalore.txt), made a scaper which would scrape the links of the menu's of those particular restaurants and store it in the form of a dictionary with the key as the name of the hotel and its value being a list containg the links to it's menu (.jpg files). Stored it in [image_links_bangalore.txt](https://github.com/prodicus/big_data_project/blob/master/bin/image_links_bangalore.txt)
  	* completed the menu scraper which is [all_images.py](https://github.com/prodicus/big_data_project/blob/master/bin/all_images.py) which reads all the restaurent names from the file [image_links_bangalore.txt](https://github.com/prodicus/big_data_project/blob/master/bin/all_images.py) and scrapes the menu images creating seperate folders for each of the restaurants.
  * Date : 25-8-15
  	* [all_images.py](https://github.com/prodicus/big_data_project/blob/master/bin/all_images.py) downloaded all the images from the links in [image_links_bangalore.txt](https://github.com/prodicus/big_data_project/blob/master/bin/image_links_bangalore.txt). 
  * Date : 7-8-15
  	* "user_reviews_all"
  	   Scraped all the reviews of the restaurants in Bangalore and stored it in a dictionary with key-pair values as
  		* review : user review
  		* score : out of 5
  		* hotel : hotel_id
  		* title : the title of the user review
  	* "user_ratings"
  	   Scraped the total rating of the restaurants and stored it in a dictionary with key-value pairs as 
  		* rating : rating given by user
  		* hotelname : name
  		* hoteid : id
  		* totalvotes : number of users who have voted
  	* "image_cleansing"
  	   Cleansed the menu's of the restaurants according to dark and light images and then cleansed the images to greyscale
  	* "automation_scripts" :  wrote some scripts in this dir 
  	* "ocrd_menus" : contains the list of menus of the first 700 hotels in the file "burrp_bangalore.txt" and then storing it in different files based on whether the menu was dark or light

###To do : 
  * To classify the reviews scraped from the sites and classify the restaurants based on what it is good in. i.e make a tuple of the things a restaurant is good at and the name of the restaurant name.