# Premier League Transfer Spending vs Club Financials

## What this is about
I wanted to find out whether clubs that earn more money actually spend more on transfers, or whether that's not really the case. I also had a look at which positions clubs spend the most on.

## The question
Does a club's revenue actually predict how much they spend on transfers? And where does most of the transfer money go by position?

## The data
I used two datasets from Kaggle (Global Football Transfer Market 2010-2026):
- transfers_history.csv - roughly 15,000 transfers, including the player, position, fee, and clubs involved
- club_financials.csv - revenue, wages and net transfer spend for clubs by season

## Tools
Python (pandas and matplotlib) for cleaning the data and making charts, and SQL (via DuckDB) for the grouping and aggregation queries.

## What I found
Revenue and transfer spend aren't that strongly linked - the correlation came out at 0.34, so richer clubs do tend to spend a bit more, but there's loads of variation and plenty of exceptions.

Some clubs spend way more than you'd expect given their revenue. The Saudi clubs (Al-Nassr, Al-Hilal, Al-Ittihad) spend over half their revenue on transfers each season, more than Man City or Man United do relative to theirs.

On the other end, clubs like Benfica, RB Leipzig and Ajax barely spend anything net - they're known for developing and selling players rather than buying, and the numbers back that up.

Centre-backs and central midfielders get bought the most overall, but interestingly right-backs actually command the highest average fee per transfer, which wasn't what I expected.

## How to run it
Open the notebook in Colab, upload the two CSV files when it prompts you, and run all the cells.

## Author
Harry



