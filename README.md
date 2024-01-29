# Web-Scrapping-Daraz-PK

The provided code is part of a project that uses Python to scrape, analyze, and manipulate data from the e-commerce website Daraz. 
<br><br>
Initially, the code navigates to the website and extracts product names and reviews. It iterates over multiple pages to gather a comprehensive dataset. The extracted reviews are then subjected to sentiment analysis using the Sentiment Intensity Analyzer from the nltk library. This process classifies each review as positive or negative based on its compound score.
<br><br>
In addition to reviews, the code also extracts detailed product information such as price, rating, number of reviews, availability on Daraz Mall, and country of origin. It navigates to each product's individual page to gather more detailed information.
<br><br>
Finally, the code performs data manipulation on the extracted information. It iterates over the products on the search results page, extracting details such as whether the product is available on Daraz Mall or from a private seller, average price, number of listings, average unit selling, seller ratings, and number of followers. After gathering the information for a product, it navigates back to the search results page and undoes the selection of the current product before moving on to the next one.
<br><br>
Overall, this project demonstrates a comprehensive use of Python for web scraping, sentiment analysis, and data manipulation, providing valuable insights into product information and customer reviews on Daraz. 😊
