# soccer-xg-course-of-the-game

I have explored how the course of a soccer match influences the relation of the expected goals (xG) score to the actual score. Using data from FiveThirtyEight and weltfussball.de, I found that team who are leading for longer period of the match overperform their xG scores more than teams that lead for a shorter period. Furthermore, using data from statsbpmb, I have  discovered that teams who are leading admit for more and have less expected goals than when there is a draw. I explain this by the shift of strategy that often happens when one teams go ahead: while the leader focuses on defending, the team behind puts their efforts into scoring goals.

A summary can be found in soccer-xg-course-of-the-game_paper.

The code (in Python) consists of five notebooks:
- the web scraper for the data from weltfussball.de: weltfussball_data
- the data from weltfussball.de are merged with the data from FiveThirtyEight: spi_plus
- analysis of these data: weltfussball_analysis
- download of the data from statsbomb: statsbomb_data
- analysis of the data from statsbomb: statsbomb_analysis
