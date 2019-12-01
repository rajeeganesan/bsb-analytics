# bsb-analytics


goal: identify whether or not plate discipline can be 
utilized as a predictive model to identify a player's clutch, BA, WPA & wins.

clutch is a statistic defined by fangraphs to
compare the player's WPA in high leverage 
situations to the player's performance
without any weighting for leverage.

this is to be compared with the disc rating for each player.
this disc rating uses a form of a z-score to calculate 
an overall rating of how disciplined a hitter is based on 
their score in comparison to the MLB average. in this case, 
a negative disc rating indicates a more disciplined hitter.

calculated average disc ratings among all
MLB teams that had eligible players with the following plots.

then, i was able to use each player's disc ratings to identify 
a potential correlation between disc rating and 1. clutch, 2. BA, 3. WPA, in order
to attempt to find a potential predictive model, and then combining player's
disc ratings and finding the relationship with actual wins.
