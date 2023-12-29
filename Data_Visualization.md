# Multi-Step Data Analysis
1. Data Source -> Clean/Process ->
   - Visualize
   - Analyze
2. Data Mining Technologies
   - Geo Data
     - Using the Google Geodata API
     - Caches data in a database to avoid rate limiting and allow restarting
       - API key subset (service URL)
3. Search Engine Architecture
   - Web Crawler: mainly used to create a copy of all the visited pages for later processing by a search engine
4. Web Crawling Policy
   - A selection policy: states which pages to download
   - A re-visit policy: states when to check for changes to the pages
   - A politeness policy: states how to avoid overloading web sites
   - A parallelization policy: states how to coordinate distributed Web Crawlers
   - *robots.txt: a way for a website to communicate w/ web crawlers, an informal and voluntary standard*
5. Mailing Lists - Gmane
   - gmane.org has no rate limits
     - Crawl the archive of a mailing list
     - Do some analysis/cleanup
     - Visualize the data as word cloud and lines
