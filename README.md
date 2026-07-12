# Premier League Transfer Spending vs Club Financials

## What this is about
I wanted to find out whether clubs that earn more money actually spend more on transfers. I also had a look at which positions clubs tend to splash the most cash on.

## The question
Does a club's revenue actually predict how much they spend on transfers? And where does most of the transfer money go by position?

## The data
I used two datasets from Kaggle (Global Football Transfer Market 2010-2026):
- transfers_history.csv - roughly 15,000 transfers including the player, position, fee and clubs involved
- club_financials.csv - revenue, wages and net transfer spend for clubs by season

## Tools
Python (pandas and matplotlib) for cleaning the data and making charts. SQL (via DuckDB) for the grouping and aggregation queries.

## What I found
Revenue and transfer spend aren't that strongly linked. The correlation came out at 0.34 so richer clubs do tend to spend a bit more but there's loads of exceptions. 

The Saudi clubs are a good example of where the money doesn't add up how you'd expect. Al-Nassr signing Cristiano Ronaldo and Al-Hilal picking up Neymar helped push their spend to over half their revenue in some seasons, way more than what Man City or Man United spend relative to what they earn.

Then you've got clubs like Benfica, RB Leipzig and Ajax who barely spend anything net. Benfica selling João Félix for over €120m is a good example of why - they're a club built around developing players and cashing in rather than buying big.

Centre-backs and central midfielders get bought the most overall in terms of total money spent, which makes sense given how many transfers happen in those positions. But right-backs actually have the highest average fee per transfer. Trent Alexander-Arnold's valuation is a good example of how expensive that position's become even though fewer of them get bought.

## How to run it
Open the notebook in Colab, upload the two CSV files when it prompts you, and run all the cells.

## Author
Harry


