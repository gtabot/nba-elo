# NBA Elo Project
This code base extends on the work originally started by [FiveThirtyEight's](https://abcnews.go.com/538) [The Complete History of the NBA](https://projects.fivethirtyeight.com/complete-history-of-the-nba/).

## Elo Rating System
The [Elo rating system](https://en.wikipedia.org/wiki/Elo_rating_system) is not new and has been used to rank chess players for decades. In 2015, [Nate Silver](https://en.wikipedia.org/wiki/Nate_Silver) adapted the Elo formula [for use in the NBA](https://fivethirtyeight.com/features/how-we-calculate-nba-elo-ratings/). The blog [ergosum.co](https://www.ergosum.co/) has a great [post](https://www.ergosum.co/nate-silvers-nba-elo-algorithm/) detailing the specific parameters Silver uses for his NBA calculcations.

## Compute

### Validate

- [nba_elo.csv](https://github.com/gtabot/nba-elo/blob/main/compute/nba_elo.csv) - Contains game-by-game Elo ratings and forecasts back to 1946 [[source](https://projects.fivethirtyeight.com/nba-model/nba_elo.csv)]
- [validate.ipynb](https://github.com/gtabot/nba-elo/blob/main/compute/validate.ipynb) - Notebook validating the implementation's correctness against FiveThirtyEight's published data