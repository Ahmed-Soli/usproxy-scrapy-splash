# usproxy-scrapy
this script uses scrapy framework to scrape proxies from us-proxy.org using splash to render the javascript and perform pagination licks

# Installation
Make sure to install docker and scrapy-splash on your OS following this guide
https://github.com/scrapy-plugins/scrapy-splash

# Installation

```bash
pip install scrapy
pip install scrapy-splash
```
## Usage

```
scrapy crawl usproxy -o filename.json or filename.csv
```
