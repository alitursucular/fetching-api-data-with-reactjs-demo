# Fetching data from a RESTful API with React (Fetch API)
This project simply shows fetching data from a RESTful API (_https://exchangeratesapi.io/_). This foreign exchange rates API allows us to retrieve current and historical foreign exchange rates published by the European Central Bank. Although, there are many types of queries mentioned on their website, we will be using `latest?base=GBP` as for the _query string_ to keep this project simple. (Note that, base currency is set to GBP so, other listed currencies are based on GBP). Since we are bringing in a real world data and playing with it, I consider this project is a bit more complex than staying in the local environment. Once data is fetched, we filter our results and create a dynamic _table_ element to display.

For the **blog post** and the **demo** of this repo please visit: https://alitursucular.github.io/fetching-api-data-with-reactjs/

---

Note: The source code is in the _master branch_ while, the build code is in _gh-pages_.