# Amazon-Fashion-Discovery-Engine
Build a recommendation system which suggests similar products (apparel) to the given product (apparel) in an e-commerce website.
## Problem Statement

Personalized product recommendations are the alternative way of navigating through the online shop. More people find products they need. Even if they didn’t think of them.

Build a recommendation engine which suggests  similar products to the given product  in any e-commerce websites ex. Amazon.com, myntra.com etc.

## Objective 

The recommendation engine, uses information about 1,80,000 products and each product will have multiple features named:

1. Title of the product  
2. Brand of the product
3. Color of the product
4. Type of the product
5. Image of the apparel

## Model Building

Out of the 180k data points, the dataset was reduced to 16k points by removing the duplicates and performing text preprocessing on the dataset.

Three approaches: <b> Text-based product similarity,text-semantic based product similarity and visual feature based product similarity are used for this case study.</b>
<b>
1. For text-based similarity, techniques like BOW and TF-IDF are used.
2. For text-semantic based similarity, techniques like Word2Vec and Average Word2Vec are used.
3. For visual feature based similarity, CNN based architecture (VGG-16) is used.
</b>
