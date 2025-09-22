# Data Guide

This project uses product & store data scraped from Tokopedia.  
Due to size and policy restrictions, the full raw dataset is not included here.  

- `Sample-Data_Tokopedia_Scraping.xlsx` and `Sample-Data_Tokopedia_Clean.xlsx` → sample of 100 rows (for demo purposes).  
- Full dataset available upon request or can be regenerated using `notebooks/01_data_scraping.ipynb`. 

## 📑 Data Dictionary

| Column Name            | Description                                           |
|-------------------------|------------------------------------------------------|
| produk                 | Product name                                          |
| harga                  | Product price in Rupiah                               |
| rating_produk          | Average product rating (1–5)                          |
| total_rating_5         | Number of reviews with 5-star rating                  |
| total_rating_4         | Number of reviews with 4-star rating                  |
| total_rating_3         | Number of reviews with 3-star rating                  |
| total_rating_2         | Number of reviews with 2-star rating                  |
| total_rating_1         | Number of reviews with 1-star rating                  |
| total_review_produk    | Total product reviews                                 |
| jumlah_terjual         | Total units sold per product                          |
| sub_kategori           | Product sub-category                                  |
| toko                   | Store name                                            |
| lokasi                 | Store location                                        |
| rating_toko            | Average store rating (1–5)                            |
| total_review_toko      | Total store reviews                                   |
| url_produk             | Product page URL                                      |
| kategori               | Main product category                                 |
