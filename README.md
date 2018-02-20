### BLACKJACK GAME


As a casual gamer, I'd like to be able to play blackjack from my terminal by typing the command:
blackjack start

Once the game has started, I'd like both myself and the dealer to be dealt two random cards:
Player 1: 2s 3d
Dealer: Ad Kh

Where the value of the card is denoted by one of [2,3,4,5,6,7,8,9,T,J,Q,K,A] and the suit of the card (clubs, diamonds, hearts or spades) is denoted by one of [c,d,h,s].
Once my cards have been dealt, I should be able to choose to stick or twist.

If I stick, my turn finishes.
If I twist, I am dealt a card. If that card takes me over the value of 21, then I am bust, and I lose the hand. If I am under the value of 21, I may choose to stick or twist again.
Once my turn is over, the dealer will take his turn. If he has less than 17, he will twist. If he has 17 or more, he will stick. If the dealer goes bust, I win.
If neither me nor the dealer goes bust, then the winner is the player with the highest value hand. In the event of the tie, the dealer wins.

Once my hand is finished, I can choose to exit the game or play again.
