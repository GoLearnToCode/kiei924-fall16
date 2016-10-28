# Week 6 Homework - Graded (20 points)

### Due Date: Next Thursday, 11:59pm

This week's homework is to build a poker application using React. This application should be submitted via GitHub, in a repository in your account named *week6*. For grading, the assignment will be automatically downloaded from your GitHub account, so **the name of the repository matters** -- make sure your submission lives at https://github.com/your-username/week6.

* "Poker" React app (20 points)
  * A React-based application that simulates the dealing of five random playing cards when a button is pressed (e.g. "Deal")
  * Use https://github.com/kiei924-fall16/poker-react as a starting point -- the easiest way is to download this as a zip file, rename it `week6`, `cd` into this new directory and run `npm install` from the command line. Make sure to include the `.gitignore` file that's included in the starting point.
  * The cards dealt must be unique, just like Vegas
  * Card images can be found using the following convention: http://golearntocode.com/images/cards/5_of_diamonds.png
  * You can use Bootstrap's *img-responsive* helper class to make the cards not so huge :)
  * Requirements for full credit:
    * Create your own React class to represent a card.
    * Store the "hand" (i.e. the five random cards) in `state`
    * Create your function to deal out five new cards, replacing the hand in `state`
