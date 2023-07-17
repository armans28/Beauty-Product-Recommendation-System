# Beauty-Product-Recommendation-System

To view the user's portfolio blog on the Beauty Product Recommendation system using collaborative filtering, please visit [My Blog](https://danielrs.systeme.io/beauty-product-recommendation) to see the explanation of the notebook.

# Dataset Content

Here's a table that explains the user columns in the dataset:

| Column Name | Description |
| --- | --- |
| overall | The overall rating given by the reviewer |
| verified | Whether the reviewer is a verified purchaser of the product |
| reviewTime | The date and time when the review was written |
| reviewerID | A unique identifier for the reviewer |
| asin | A unique identifier for the product |
| reviewerName | The name of the reviewer |
| reviewText | The text of the review |
| summary | A summary of the review |
| unixReviewTime | The date and time when the review was written in Unix time format |
| vote | The number of votes the review has received |
| style | A dictionary of product metadata, such as color and size |
| image | The URL of an image associated with the product |

This table describes the columns in the dataset and provides a brief description of each column. The `overall`, `verified`, `reviewTime`, `reviewerID`, `asin`, `reviewerName`, `reviewText`, `summary`, `unixReviewTime`, `vote`, `style`, and `image` columns provide information about the reviews and the products being reviewed.

Here's a table that explains the Meta data (Product data) columns in the dataset:

| Column Name | Description |
| --- | --- |
| category | The category of the product |
| tech1 | Technical information about the product |
| description | A description of the product |
| fit | Information about the fit of the product |
| title | The title of the product |
| also_buy | A list of ASINs for products that are frequently bought together with the product |
| tech2 | Additional technical information about the product |
| brand | The brand of the product |
| feature | A list of features of the product |
| rank | The sales rank of the product in its category |
| also_view | A list of ASINs for products that are frequently viewed together with the product |
| details | Additional details about the product |
| main_cat | The main category of the product |
| similar_item | A list of ASINs for products that are similar to the product |
| date | The date the product was added to the dataset |
| price | The price of the product |
| asin | A unique identifier for the product |
| imageURL | The URL of an image associated with the product |
| imageURLHighRes | The URL of a high-resolution image associated with the product |

This table describes the columns in the dataset and provides a brief description of each column. The `category`, `tech1`, `description`, `fit`, `title`, `also_buy`, `tech2`, `brand`, `feature`, `rank`, `also_view`, `details`, `main_cat`, `similar_item`, `date`, `price`, `asin`, `imageURL`, and `imageURLHighRes` columns provide information about the products in the dataset.

# Citation
Justifying recommendations using distantly-labeled reviews and fined-grained aspects
Jianmo Ni, Jiacheng Li, Julian McAuley [Empirical Methods in Natural Language Processing (EMNLP), 2019](http://cseweb.ucsd.edu/~jmcauley/pdfs/emnlp19a.pdf)

## Dataset Source

You can get the data from [Beauty Product Dataset](https://cseweb.ucsd.edu/~jmcauley/datasets/amazon_v2/).  There are 2 datasets, namely [Meta Data Dataset](https://datarepo.eng.ucsd.edu/mcauley_group/data/amazon_v2/metaFiles2/meta_All_Beauty.json.gz) and [Review Dataset](https://datarepo.eng.ucsd.edu/mcauley_group/data/amazon_v2/categoryFiles/All_Beauty.json.gz).
Choose the `All Beauty`

![image](https://github.com/armans28/Beauty-Product-Recommendation-System/assets/119162844/7f88378e-2fd6-4e97-8727-93f142f14807)


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
