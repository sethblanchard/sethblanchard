# Pythagorean Pennants
## Repurposing the pennant on your wall to tell your favorite team's future

How good was your team last year? Really, how good were they? I know, if that pass in week 9 was a little higher you sneak into the playoffs. Your favorite player doesn't get injured in week 4 - you win the division. You lost 10 games but the season felt better than that. 

We all talk around how wins, in the NFL especially[1][1], don't capture an accurate picture of how your team performed. So if we all implicitly state that wins aren't the right number, what is? Point Differential.

Point differential is the sum of the points a team scored minus the sum of the points it allowed for all the games it has played in a season. For example, this year the New England Patriots won 12 games and had a point differential of +55 for the season, where as the Arizona Cardinals won 10 and also had a point differential of +55 points. Two different win totals, same difference in points score and points allowed for the entire season.

### Enter Pythagoras 
So we have a better picture of how good our team was - eh (shrugs) - what are we going to do with that? This is where we bring back 8th grade geometry and apply Pythagoras. Not exactly the Pythagorean Theorem, but the Pythagorean Expectation.  The Pythagorean [2][2] Expectation takes point differential and turns it into an expected number of wins. The pennants above display this visually. The horizontal line show the point difference while the vertical line shows the difference in expected wins. You can quickly tell which team should have won (or lost) more games and the relationship between expected wins and point differential. 

## The Weight of Expectation

Now that we have aligned reality with our expectations what can we do with this new number. It turns out that the expected wins (and wether it was more or less) have an impact on the future. A team that was expected to win more games than it did usually does the next season and vice versa. The chart below shows how a teams expectations can weigh down or buoy wins for the next season. It isn't exact[3][3] but it can give us a good idea of the direction our team is heading next season. 

#### Footnotes 
[1] Because the sample size in the NFL - 16 games - is so small.
[2] It is name the Pythagorean Expectation because the formula looks a lot like the one you learned in middle school. It was invented by Bill James and applied first to baseball and has since moved to other sports with slightly different formulas. Learn more about the [Pythagorean Expectation](http://en.wikipedia.org/wiki/Pythagorean_expectation). 
[3] It doesn't take into account things like player movement. So while the 2011 Broncos should have not won quite as many games the following seasons adding Payton Manning is clearly a difference maker.

#### About 

I learned about the Pythagorean Expectation by reading [Bill Barnwell](https://twitter.com/billbarnwell)'s  work on [Grantland](http://grantland.com/contributors/bill-barnwell/). It made being a fan of the football team in our nations capitol even more frustrating but provided insight into teams performance from year to year that I really have enjoyed having. I wanted to  

#### Graphic
- Data is from [Pro-Football Reference](http://www.pro-football-reference.com) and is available as a [google doc](https://docs.google.com/spreadsheets/d/1XkJxHtFrhZOgBjxJXMIejxepBolQhBO_KXgtbAGcHhE/pubhtml).
- The charts were built using [d3.js](http://d3js.org) and specifically [these](http://bl.ocks.org/mbostock/3884955) [three](http://bl.ocks.org/mbostock/1166403) [examples](http://bl.ocks.org/mbostock/8027637). 
- This is clearly a remix so I'd love to see what you do with the data and the statistical approach. Let me know [@sethblanchard](https://twitter.com/sethblanchard).