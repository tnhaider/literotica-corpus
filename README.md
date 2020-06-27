# Literotica Corpus crawled from literotica.com 
It contains an indecent amount of erotic fanfiction (over 110000 documents, either whole stories or chapters).

best_literotica contains the stories with the highest star rating (rated by the users).

last_12_literotica contains the best stories of the last 12 months (at the time of crawling).

last_30_literotica contains the best stories of the last 30 days (at the time of crawling).

The rest is divided into genres.

We excluded all texts that had a rating of lower than 4.

The texts have the following filename schema:
id_title_rating.txt

If you want to crawl it again, here is the crawler:
https://github.com/tnhaider/crawler/blob/master/erotica_crawler.py

