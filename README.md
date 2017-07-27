# King's Blackball

King's Blackball is a complex and accelerated variant of [war](https://en.wikipedia.org/wiki/War_(card_game)).
Cards are won in tricks.
Games are played in two rounds.
In the first round, each player starts with a deck of 52 cards.
In the second round, a player plays with the cards they won in tricks during the first round.
After the second round, the point values of cards each player won are counted, and the player with the highest score wins.

# Objective
The objective of the game is to win the greatest number of points.  Some cards have positive point values, some cards have negative point values.

# Game Setup
Each player starts with a standard 52 card deck.  Each player removes the Kings ("Black ball cards") and places them face up in front of them.  Then each player shuffles their deck.

# Tricks
A trick begins by each player placing a card from the top of their deck face up in the middle of the table.  The cards are then compared (see <b>Comparing Cards in a Trick</b>) with three possible outcomes: 
1. One player wins the trick. 
In this case, the player who won the trick takes all the cards and keeps them for scoring at the end of the game, or the player may blackball the trick (see <b>blackballing</b>).
2. All the cards played are trashed (eliminated from the game). 
In this case, the cards are put in a discard pile.
3. A war results.  
There are two ways to conduct a war: If each player played precisely the same card, then the war is conducted by playing two cards face down and the third card face up.  
If the two cards are different, then a single card is placed face down and the second is placed face up.  
The cards placed face up are treated as a new trick, so the result may be to trash all the cards from the original trick and the new trick, one player may win both tricks, or a second war may result.  
A third war cannot occur.
Instead, the highest card wins the trick or, if all cards are exactly equal, [sudden death](https://en.wikipedia.org/wiki/Sudden_death_(sport)) [rock-paper-scissors](https://en.wikipedia.org/wiki/Rock%E2%80%93paper%E2%80%93scissors) and the winning player wins the trick.

# Comparing Cards in a Trick

The winning card of a trick is determined by examining the class of the card.
The following table illustrates the outcome when comparing two cards for two players, A and B:

|Class - A|Class - B|Result|
|---|---|---|
|Top|Top|War|
|Top|Any class except Top|A wins trick|
|Pure|Pure|War|
|Pure|Any class except Top or Pure|A wins trick|
|Good|Good|War|
|Good|Any class except Top, Pure, or Good|A wins trick|
|Bad|Bad|Trash -- unless the cards are exactly the same, then war|
|Bad|Neutral|Trash|
|Bad|Evil|A wins trick|
|Neutral|Neutral|War|
|Neutral|Evil|Trash|
|Evil|Evil|War|

By swapping the roles of Player A and B, this table can be used to figure out the outcome in any two player situation.
A table specifying the class for each card can be found under <b>Card Classes & Point Values</b>

# Blackballing
The kings, placed face up in front of each player at the beginning of the game, can be played at any time during a trick to trash all the cards in the trick.  Blackballing a trick can be used to avoid winning cards with more negative point values.

# Card Classes & Point Values
The following table illustrates the point values and class memberships for each card.

|Card|Class|Point Value|
|---|----|---|
|2|Good|1|
|3|Bad|-2|
|4|Neutral|0|
|5|Bad|-2|
|6|Evil|-10|
|7|Pure|2|
|8|Good|1|
|9|Bad|-2|
|10|Top|5|
|Jack|Bad|-2|
|Queen|Good|1|
|King|Blackball|-5|
|Ace|Good|1|

# Calculating Score
At the end of the second round, each player sums up the total amount of points in cards that they won (<b>including blackball cards</b>).  



