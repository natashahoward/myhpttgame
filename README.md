# myhptpgame
My Harry Potter Top Trumps Game

My program is based on the game 'Top Trumps'. For those not familiar with the game, each card in the deck has a character, and all of the characters have a range of characteristics or catagories. For example, these catagories could be height or age. The cards are dealt evenly between players, and players cannot look beyond their top card. Without seeing the other player's cards, one player chooses a catagory in the hope that they score the best within that catagory. 

The data for the 'cards' comes from a Harry Potter API.
To make the game more user-friendly, when the user is asked to input yes or no, there are a range of answers it will accept eg. 'y', 'yeah', 'YES' will all be accepted as yes. If it still doesn't understand the answer to any question, it will loop back.

The game starts by explaining the rules, then asking the user if they're ready to play, followed by how many rounds they'd like to play.

At the start, the game randomly decides whether the computer or the user will get to choose the catagories. The catagories are birth year, house, ancestry and magic points. Should the computer be selected to pick the catagories, it follows a few tactical rules.

Each round, one the catagory is chosen, the game adds a point to the computer's score or the user's score as appropriate.

When all the rounds have happened, the game calculates the final score, then asks the user if they would like to play again.

Features I would like to introduce
- perhaps an option to pick difficulty levels? (for when the computer chooses catagories)
- an option to open the rules and then resume the game
- add option to quit at anytime
- cards are dealt at the start and don't come up again
- if a round is drawn, the two players look at their next card and the one who does better on the second card wins
- the winning player of each round gets to pick the next catagory
- when a player wins a round the cards are added to their deck
- high scores
