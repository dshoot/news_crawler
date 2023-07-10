
# news_crawler
Trivial news crawler. Crawls 'https://www.dailymail.co.uk/news/index.html' by default.
Stores news in json format in hashed by URL directories. Potentially other stuff like images can be stored in those folders in the future.
Supports 2 modes: bfs for Breadth-first search, and dfs for Depth-first search.
Can be started by means of crawl_news_site function with appropriate parameters.
news_domain parameter controls news path inside the news site.
