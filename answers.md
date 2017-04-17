Activity 7 

#1. You would need cards, a desk to play it on, the deck

#2. 1. Create Deck 2. Check to see if there is 9 cards in the deck. 3. If there are draw 9 cards else draw the rest. 4. Look for two cards that add up to 11 if they are there replace or trash them. 5. Check to see if there is K,Q,J if there is replace or trash. 6. If there is nothing to trash, but there is still cards in the deck the game is lossed 

#3 yes

#4 a. dealMyCards is called in NewGame() and in the constructor when a new ElevensBoard is started
   b. anotherPlayIsPossible should have contain it and isLegal
   c. 0,1,3,6,7
   d. for (Integer i : cIndexes) {
  System.out.println(board.cards[i].toString());
}
   e.anotherPlayIsPossible() because it will know if the game should have ended because there is no more pairs, isLegal is only making sure the move was okay. 