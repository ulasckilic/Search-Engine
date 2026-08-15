# Web-Crawler

# Search Engine from Scratch (Python)

A web crawler, inverted index and PageRank ranking implemented without
external libraries (no BeautifulSoup, no NetworkX).

- Crawler: DFS over the seed page, HTML stripped manually via string operations
- Index: dictionary-based inverted index, duplicate-free posting lists
- Normalization: punctuation stripping (noPunct) and case folding
- Ranking: iterative PageRank, damping factor 0.8, 10 iterations
- rankedLookup(index, key, graph) returns query results ordered by page rank

Course project — DSAI 301, Boğaziçi University.
