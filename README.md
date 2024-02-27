# Trustpilot Scraper

Scrape Trustpilot utilising Smartproxy's Web Scraping API

<p align="center">
    <a href="https://dashboard.smartproxy.com/register?page=web-scraping-api%2Fpricing&utm_source=socialorganic&utm_medium=social&utm_campaign=github_website_scraper" ><img src="https://i.imgur.com/v4Z5CXu.png"></a>
</p> 

## Dependencies

```http
glom
BeautifulSoup
```

## Authentication

Once you have an active Web Scraping API subscription you can set your password in the dashboard Web Scraping API > Authentication method, you can also try sending a request right from the dashboard Web Scraping API > API playground method tab simply by clicking on Send Request. You will also see an example of curl request generated on the right. 

### This Pyhton code example uses Base64 encoded ```user:pass``` authentication.

| Parser type | Example location         | Download |
| -------------------- | ------------------------ | -------- |
| HTML to JSON        | [Trustpilot_parser.py](https://github.com/Smartproxy/trustpilot_python_scraper/blob/main/Trustpilot_parser.py) |``` curl https://raw.githubusercontent.com/Smartproxy/trustpilot_python_scraper/blob/main/Trustpilot_parser.py > Trustpilot_parser.py ``` |
| JSON to JSON                 | [trustpilot_json_parser_glom.py](https://github.com/Smartproxy/trustpilot_python_scraper/blob/main/trustpilot_json_parser_glom.py)   | ``` curl https://raw.githubusercontent.com/Smartproxy/trustpilot_python_scraper/blob/main/trustpilot_json_parser_glom.py > trustpilot_json_parser_glom.py ``` |

## HTML to JSON

This Python script extracts review text, review date & star ratings straight from the HTML of Trustpilot website and saves them to a JSON file.

## JSON to JSON

This Python script extracts dozens of data points from a JSON that gets loaded when you visit Trustpilot. Data points include but are not limited to - bussiness information (name, URL, website, location etc.), reviews (text, rating, name, positive/negative), ratings.
