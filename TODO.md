### 24.12.2018
    - add to Github

### 27.1.2019
    - Add functionality to block images and CSS from loading as described here:
        https://www.scrapehero.com/how-to-increase-web-scraping-speed-using-puppeteer/
        https://www.scrapehero.com/how-to-build-a-web-scraper-using-puppeteer-and-node-js/

### 29.1.2019
    - implement proxy support functionality
        - implement proxy check

    - implement scraping more than 1 page
        - do it for google
        - and bing
    - implement duckduckgo scraping


### 30.1.2019
    - modify all scrapers to use the generic class where it makes sense
        - Bing, Baidu, Google, Duckduckgo

### 7.2.2019
    - add num_requests to test cases [done]

### 25.2.2019
    - https://antoinevastel.com/crawler/2018/09/20/parallel-crawler-puppeteer.html
    - add support for browsing with multiple browsers, use this neat library:
    - https://github.com/thomasdondorf/puppeteer-cluster [done]
    
    
### 28.2.2019
    - write test case for multiple browsers/proxies
    - write test case and example for multiple tabs with bing
    - make README.md nicer. https://github.com/thomasdondorf/puppeteer-cluster/blob/master/README.md as template


### 11.6.2019
    - TODO: fix amazon scraping
    - change api of remaining test cases [done]
    - TODO: implement custom search engine parameters on scrape()
    
### 12.6.2019
    - remove unnecessary sleep() calls and replace with waitFor selectors
    

### TODO:
1. fix googlenewsscraper waiting for results and parsing. remove the static sleep [done]
2. when using multiple browsers and random user agent, pass a random user agent to each perBrowserOptions
3. dont create a new tab when opening a new scraper
