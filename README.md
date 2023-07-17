# j1-league-web-scraper

This project aims to scrape data for players belonging to the Japanese J1 League. This is in response to a request from a football club in Japan that is interested in analysing detailed player information.

The project will produce two Excel files containing the following data:

1. **`Player Information`**: An Excel file including each player's name, team, birthplace, nationality, height, weight, and previous clubs.
2. **`Playing Time Statistics`**: An Excel file containing time spent by each player in the following categories:
   
   * `Time in Last Appearance` (最終出場)
   * `Time Played in Full Match` (フル出場)
   * `Time Spent as Reserve` (控え)
   * `Time since Subbed On` (途中出場)
   * `Time until Subbed Off` (途中退場)
   * `Time as Non-squad Member` (メンバー外)

The data will be scraped from 'https://soccer.yahoo.co.jp/jleague/category/j1/teams' and 'http://soccer.phew.homeip.net', parsed, and then stored in the aforementioned Excel files for further analysis.

The scraping scripts (Python) are available in the `notebook` folder.
