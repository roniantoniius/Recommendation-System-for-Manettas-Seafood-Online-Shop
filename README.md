# Recommendation-System-for-Manettas-Seafood-Online-Shop

![image](https://github.com/roniantoniius/Recommendation-System-for-Manettas-Seafood-Online-Shop/assets/121453378/aa0f5520-f6d5-4a79-97fe-861d98287c62)

Image Source: Getty Images
## Business Understanding

In today's dynamic landscape of online seafood retail, businesses encounter several challenges related to consumer preferences, accessibility, and promoting healthy eating habits. With the increasing demand for convenient shopping experiences and diverse dietary choices, addressing these challenges becomes imperative for ensuring customer satisfaction and fostering a sustainable business model 🐟.

One of the primary concerns revolves around ensuring accessibility to seafood products for consumers, particularly those residing in landlocked areas or areas with limited access to fresh seafood markets. Additionally, promoting seafood consumption among children, who often exhibit reluctance towards seafood due to taste preferences or lack of exposure, poses a significant challenge. By understanding these obstacles, businesses can tailor their offerings and marketing strategies to cater to diverse consumer needs and preferences.

The proposed solution involves developing a personalized recommendation system for the online seafood shop, Manettas, using Content-Based Filtering techniques. By leveraging product descriptions, pricing information, and origin details, the system aims to provide tailored recommendations to users based on their preferences and previous purchase history. This solution not only enhances the shopping experience for customers by offering relevant and enticing product suggestions but also encourages seafood consumption by showcasing a variety of high-quality and sustainably sourced seafood options 🦐.

## Data Understanding 📊
The dataset for the Manettas online seafood shop recommendation project is obtained through Nested Scraping techniques using Beautiful Soup, resulting in a comprehensive collection of seafood product listings and details. This dataset serves as the foundation for our recommendation system development, providing rich information about various seafood products available on the platform.
- nama_produk: Represents the name or title of each seafood product listed on the Manettas online shop.
- harga: Indicates the price of the seafood product.
- kriteria: Describes specific attributes or characteristics of the seafood product, such as weight, quantity, or special features.
- asal_produk: Specifies the origin or source of the seafood product.
- link: Contains the URL link to the product page on the Manettas online shop, facilitating easy access to additional details or purchase options.
- deskripsi: Offers a detailed description of the seafood product, including its features, benefits, and cooking recommendations.
- kategori: Categorizes the seafood product into specific types or groups.


## Data Preprocessing
 - Feature Selection: Selecting features that are relevant and useful for the modeling process.
- Column Cleanup: Removing the word 'Origin: ' from the 'origin_product' column and converts it to a list [,] using the split method.
- Description Cleanup: Converts the 'description' column to a list using the split method.
- Removing Spaces: Removes unwanted spaces in the data.
- Feature Merging: Combines all used features into one main feature that contains information other than 'product_name'.
- Stemming: Performs stemming process to normalize the words in the dataset.
- Lowercasing: Changes all text to lowercase for consistency.
- Count Vectorizer: Converts text into numerical representation using Count Vectorizer for modeling preparation.

## Modelling
- Natural Language Processing
- Cosine Similiarity

## Evaluation
- average cosine similiarity
