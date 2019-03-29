## Last Week's Accomplishments

> This week, I created print_table(), a function that prints the two current cards in play, which uses unicode. I have also started
> to implement the play_game() function, which, when called in the main, will run the game to play until a winner is found.

## This Week's Plan

> This upcoming week, I need to figure out why my play_game() function isn't working, and after that, add md files for each step,
> and hopefully finally finish this path of the project.

## Anything Blocking?

> The play_game() function is currently not working. It seems that when play_game() calls turn(), each player's hand isn't updating,
> so that the same cards are played over and over. I'm not yet sure if this is a somehow a problem with how I passed the player's decks
> in, or if the cards aren't removing from the beginning then adding to the winner's hand for some reason.

## Notes

> Remember to change the cards to add to the front of the list, not the back, as the cards are being played from the back.
