# Font Credibility

This is my analysis of the claim that
[some fonts are more credible than others](http://opinionator.blogs.nytimes.com/2012/08/08/hear-all-ye-people-hearken-o-earth/) ([Hacker News discussion here](http://news.ycombinator.com/item?id=4362277)). That article claims that Baskerville has a small but statistically significant advantage in credibility over Comic Sans. It says, "The *p*-value for Baskerville is 0.0068." I'm not sure what that means, but this is my effort to analyze and understand the data myself.
I'm not a statistician, but I'm trying to learn statistics, and doing my own analysis seems like a good "homework assignment."

The data set is provided in the file `raw`. I use a Ruby script, `build-ad`, to put the data into a useful format for R, stored in `ad`. (You can run `build-ad` by typing `make` in the repo's top directory.) Some of my R commands are recorded in `explore`, so you can see what I'm up to.

I'm just an amateur, so comments are welcome! I'd love to learn something.




