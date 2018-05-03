---
layout: post
title: Lessons Learned from Applying Machine Learning to Amazon's Pricing Structure
--

### Why Amazon?

Scraping Amazon means working around a few roadblocks. What do they have to
protect and why? Websites like camel camel camel and Keepa have the price history
of a massive swath of Amazon products. Their business model is to provide price
updates and price history to users on a subscription or view- advertisement
basis.

Although I don't plan on making a business out of this, I'm simply a curious
consumer. I wondered- would there be a way for me to determine whether the price
I'm paying for a product on Amazon is its actual value?

### Approach
1. Scraped Clothing, Jewelry, and Shoe category products using
Selenium
2. Analyzed the data using Pandas
3. Modeled the data with a first degree linear regression using Scikit Learn
4. Plotted and visualized the data using Matplotlib

### Modeling
The top 4 features that accounted for the greatest amount of variation in list
price were
1. Average Customer Review
2. Product Specifications Image (using an image instead of bullets in the
  specifications)
3. Number of Description Bullets
4. Number of answered customer questions

### Conclusion
Looking forward, I'd like to
1. Look a competitor websites to gather more features
2. Scrape more data from Amazon
