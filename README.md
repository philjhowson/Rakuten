# Rakuten Classification Challenge
***

This project uses a multi-modal approach to the classification problem posed by Rakuten:

"The goal of this data challenge is large-scale multimodal (text and image) product data
classification into product type codes.

For example, in Rakuten France catalog, a product with a French designation or title
Klarstein Présentoir 2 Montres Optique Fibre associated with an image and sometimes with
an additional description. This product is categorized under the 1500 product type code.
There are other products with different titles, images and with possible descriptions,
which are under the same product type code. Given these information on the products, like
the example above, this challenge proposes to model a classifier to classify the products
into its corresponding product type code."

The challenge data is not hosted on this repository. For access to challenge data, please
visit the challenge site below, register, and then download the data.

[Rakuten Multimodal Product Data Classification](https://challengedata.ens.fr/challenges/35)



## Project Organization
------------------------------------------------------------------------
    root
    ├── .devcontainer # for the streamlit app
    ├── data # contains image and text data
    │   ├── images # contains images
    │   │    ├── image_test # test data for submissions
    │   │    └── image_train # the data used for model training and validation
    │   ├── processed # processed data files
    │   └── raw # the raw text file from the rakuten challenge
    ├── images # contains output images from data exploration and model evaluation
    ├── metrics # output metrics for model training and evaluation
    ├── models # output folder for model saves, this is not on github due to model sizes
    ├── src # contains source code for exploration, and model training and evaluation
    │   ├── data # code for data formatting
    │   └── models # code for training models
    ├── streamlit # contains the files for the streamlit app
    │   ├── images # contains images used in the streamlit app
    │   └── items # contains src files for the streamlit app 
    ├── .gitignore
    ├── LICENSE
    ├── README.md
    └── requirements.txt

## Project Introduction
