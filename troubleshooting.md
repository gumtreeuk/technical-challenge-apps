# Troubleshooting

Even though we are often updating this pages, there are issues that you could face when accessing the Mock API. Thus if you happen to face an error, try the following steps:
1. Ensure the app is running by entering a query that wouldn't match with the search results (e.g. year only accepts numbers)

http://mcu-search-mock.mocklab.io/search?make=rAv&model=BQ9m88M6T79&year=kjh

**Once you confirmed the API is up and running:**

1. Open developer tools on Google Chrome
2. Go to the network tab
3. Paste the correct query as per [Readme.md](https://github.com/gumtreeuk/technical-challenge-apps/blob/main/README.md)
4. Press enter
You should see the response and the search result items in that view

![This is an image](https://raw.githubusercontent.com/gumtreeuk/technical-challenge-apps/main/mcu-api-troubleshoot.png)
