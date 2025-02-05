ChatGPT lucky did this for me but it basically added some functinons that changed the player back and forth depending on if the user matched a card, it would stay their turn but if they didn't it would switch to the other player, and the player with the most points wins!

Added the functions:
switchPlayer() - Switches the turn between Player 1 and Player 2.
updateScores() - Updates the score display after a match.
declareWinner() - Determines and announces the winner at the end of the game.

And Other Key Modifications:
Introduced currentPlayer to track whose turn it is.
Added scores object to track each player's score.
Turn Display: Shows which player's turn it is.
Score Display: Updates live as players make matches.
Turn Logic: If a player makes a match, they go again; otherwise, the turn switches.