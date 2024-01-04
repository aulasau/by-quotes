![Alt text](imgs/wordcloud_categories.png)


## Belarusian quotes, proverbs, sayings
A dataset of Belarusian expressions collected from open Internet sources.
The latest version of the dataset is **[here](data/full_df_v_0.1.csv).**

The dataset was put together for **Notion** to receive a random quote every day.
<br>
See here -- > [![Static Badge](https://img.shields.io/badge/Notion-template_random_quotes-red)](https://aulasau.notion.site/20768d1595884bf7bb41a74964f3953c)

---
#### Sources
The data was collected from:
1. Web pages:  
   1.1. [a selection of quotes from Radio Svaboda](https://www.svaboda.org/a/24255332.html)  
1.2. [selection from the National library website](https://www.nlb.by/by/infarmatsyynyya-resursy/elektronnyya-infarmatsyynyya-resursy/resursy-natsyyanalnay-bibliyateki-belarusi/virtualnyya-praekty-vysta-ki-i-kalektsyi/virtualnyya-praekty-bibliyateki/klasiki-susvetnay-litaratury-yanka-kupala-i-yakub-/vyslo-i-vykazvanni-afaryzmy-belaruskikh-pesnyaro )  
1.3. [quotes from the website dumki.org ](dumki.org )

3. pdf books:  
2.1. [Belarusian folk art. Proverbs and sayings. In two parts](https://kamunikat.org/prykazki-i-prymawki-post-46436 )  
2.2. [Ales Zaika. Proverbs and sayings from Kosovchyna](https://knihi.com/Ales_Zajka/Prykazki_i_prymauki_z_Kosauscyny.html )

#### Why these particular resources?

I wanted to start somewhere. I found a certain number of quotes on websites. But it seemed insufficient, so I decided to look at the books again. I chose the first ones that fit the content. 
Getting something out of books is quite difficult, so for now I have limited myself to these two.
The complexities of parsing and reading from pdf can be seen in [this notebook](pdf_quotes_scraping.ipynb).

---
#### Statistics on the dataset

There are currently **9655 entries** in the dataset.

<ins>the content of the dataset by source:</ins>
![Source shares](imgs/general_stats.png)

<Ins>categories within sources: </ins>
![Categories inside sources](imgs/category_ratio_squares.png)