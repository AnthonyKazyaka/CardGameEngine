# CardGameEngine

### To Do
[] Create a deck that contains 108 cards; two full standard decks plus 4 jokers
[] Create a shuffling system
[] Create a game
    [] Create a phase system to represent the different hands played and opening conditions
        [] High Pair
        [] Two Pair
        [] Three of a Kind
        [] Full House
        [] Forty
        [] Four of a Kind
        [] Straight Flush
        [] All Down
    [] Dealer and the player with the first turn are rotated after each hand
    [] Players must be dealt cards
    [] Players must be able to select a card to pickup
        [] Players must be provided the option to "buy" the top card of the discard pile and place it in their hand if the player whose turn it is picks up from the deck unless it is the first card of the game or a joker
    [] Players must be able to play certain sets of cards that meet opening conditions for the round
        [] Once open, players must be able to play cards from their hand into sets played in front of any player as long as that card is valid
        [] Once open, players may replace jokers played with the card it's standing in for if the player has it in their hand
    [] Players must be able to select a discard, so long as that card is allowed to be discarded
        [] A player may not discard any card that plays somewhere else on the table (or a high card in the High Pair and Two Pair hands) unless none of the cards in their hand are discardable for this reason, in which case any card in the player's hand may be discarded
    [] Once a player has no more cards in their hand, they are "out" and have won the round
    [] Score is tallied for each player and added to sum
        [] For low cards (2-10), their point value is their face value (e.g. "4" is worth 4 points)
        [] High cards (with the exception of the Ace) are worth 10 points
        [] Aces are worth 1 point if there is only one in the player's hand; otherwise they are 11 points each
        [] Jokers are worth 25 points each
        [] A player may not accumulate more than 100 points in a single hand
    [] Once all rounds are complete, the player with the least points is the winner
[] Create a game state system for game notation/multiplayer
[] Create a UI for the game