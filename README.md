# Elastic-Game-Search
3-node Elasticsearch + Flask UI + Kibana analytics on Amazon Video Game Reviews as a Course Project for COMP6231 (Distributed Systems) at Concordia


# Elastic Game Search

Distributed search + analytics on the Amazon Reviews (Video Games) dataset:
a 3-node Elasticsearch cluster (Docker) with a Flask web UI and Kibana dashboards.

## What it does
- Full-text search over video game products (title + description)
- Filters: minimum rating, price sorting
- Product detail page: shows reviews + embedded Kibana analytics for that ASIN

## Tech stack
Elasticsearch • Kibana • Flask • Python • NLTK • Docker Compose

## Quickstart
### 1) Install
```bash
pip install -r requirements.txt
python nltk_download.py
