# Basketball

I had scraped a basketball reference site found [here](https://www.basketball-reference.com)

I had gathered the 95-96 Bulls team's games in the regular season

## Data

* Date
* Whether or not the Bulls were playing at home 
* The opposing Team
* Outcome (Win or Loss)
* Bulls' Points
* Opponent's Points
* Total Wins at that point
* Total Losses at that point
* Win Streak/Lose Streak

# BBC Articles

This was a much bigger scrape. From BBC New's [home page](https://www.bbc.com/news), I had gathered their top stories on the front page. Then I took all the urls and scraped those articles on the front page.

## Contents

The urls I had gotten were some from other front pages and some were video articles. This is why there are three different csv files.

## Data

* Title
* Text - Written parts of article
* Headers of article
* Published Date
* Url

### Libraries

* `requests`
* `BeautifulSoup from bs4`
* __pandas__
* __re__
* __time__

