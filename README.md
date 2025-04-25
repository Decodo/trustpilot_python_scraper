<p align="center">
<a href="https://dashboard.decodo.com/?page=residential-proxies&utm_source=socialorganic&utm_medium=social&utm_campaign=resi_trial_GITHUB"><img src="https://github.com/user-attachments/assets/60bb48bd-8dcc-48b2-82c9-a218e1e4449c"></a>
</p>


[![](https://dcbadge.vercel.app/api/server/Ja8dqKgvbZ)](https://discord.gg/Ja8dqKgvbZ)

## Dependencies

```
http
glom
BeautifulSoup
```

## Authentication

Once you have an active Web Scraping API subscription, you can set your password in the dashboard Web Scraping API > Authentication method. You can also try sending a request right from the dashboard Web Scraping API > API playground method tab, simply by clicking on Send Request. You will also see an example of a curl request generated on the right. 

### This Python code example uses Base64 encoded ```user:pass``` authentication.

| Parser type | Example location         | Download |
| -------------------- | ------------------------ | -------- |
| HTML to JSON        | [Trustpilot_parser.py](https://github.com/Decodo/trustpilot_python_scraper/blob/main/Trustpilot_parser.py) |``` curl https://raw.githubusercontent.com/Decodo/trustpilot_python_scraper/blob/main/Trustpilot_parser.py > Trustpilot_parser.py ``` |
| JSON to JSON                 | [trustpilot_json_parser_glom.py](https://github.com/Decodo/trustpilot_python_scraper/blob/main/trustpilot_json_parser_glom.py)   | ``` curl https://raw.githubusercontent.com/Decodo/trustpilot_python_scraper/blob/main/trustpilot_json_parser_glom.py > trustpilot_json_parser_glom.py ``` |

## HTML to JSON

This Python script extracts review text, review dates, and star ratings directly from the HTML of the Trustpilot website and saves them to a JSON file.

## JSON to JSON

This Python script extracts dozens of data points from a JSON that gets loaded when you visit Trustpilot. Data points include, but are not limited to, business information (name, URL, website, location, etc.), reviews (text, rating, name, positive or negative), and ratings.
