# Tokenizing search engine queries for diverse results

You can find some additional details on what this is here: https://studium.dev/tech/simple-serp-strategy

to be continued...

## Notebook Setup
```bash
cd src
uv sync
uv run jupyter lab
```

### Dependencies

- [uv](https://docs.astral.sh/uv/)
- [polars](https://pola.rs/)
- [duckdb](https://duckdb.org)
- [aiohttp](https://docs.aiohttp.org/en/stable/index.html)
- [jupyter](https://jupyterlab.readthedocs.io)

## Search engines to diff _(tokenized query vs. original query)_
- [Google](https://www.google.com/)
- [Duckduckgo](https://duckduckgo.com/)
- [Bing](https://www.bing.com/)
- [Yandex](https://yandex.com/)
- [Brave](https://search.brave.com/) 
- [Yahoo](https://ca.search.yahoo.com/)
- [Ecosia](https://www.ecosia.org/)
- [Qwant](https://www.qwant.com/)
- [AOL](https://search.aol.ca)

## Resources used

- https://www.kaggle.com/datasets/dhruvildave/google-trends-dataset
    - A dataset of all the Google Trends all over the world

- https://trends.google.com
    - We have a crawler for adding additions to the Google Trends search queries datasets

- https://academictorrents.com/details/cd339bddeae7126bb3b15f3a72c903cb0c401bd1
    - This collection consists of ~20M web queries collected from ~650k users over three months. The data is sorted by anonymous user ID and sequentially arranged.

- https://figshare.com/articles/dataset/_Top_10_search_engine_queries_for_various_locations_/1070568
    - **DOI**: _10.1371/journal.pone.0063980.t001_
    - Top 10 search engine queries for various locations 

- https://figshare.com/articles/dataset/Search_query_lists/12398309
    - **DOI**: _10.6084/m9.figshare.12398309.v2_
    - Search query lists 

- https://osf.io/s65jd/
    - **DOI**: _10.7717/peerj-cs.1421._
    -  Research data for the paper "Query sampler: generating query sets for analyzing search engines using keyword research tools" 

- https://huggingface.co/datasets/s-emanuilov/query-expansion
    - **DOI**: _10.57967/hf/3881_
    - Query Expansion Dataset: This dataset is designed to train search query expansion models that can generate multiple semantic expansions for a given query. 