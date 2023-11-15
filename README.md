# Blackjack Game

Welcome to the Blackjack Game! This is a simple console-based implementation of the classic card game Blackjack written in Java.

## Rules of the Game

### Objective

The goal of Blackjack is to beat the dealer by having a hand value closer to 21 than the dealer's hand without going over 21. A hand value over 21 results in a bust and automatic loss.

### Card Values

- Number cards (2-10) are worth their face value.
- Face cards (King, Queen, Jack) are each worth 10 points.
- Aces can be worth either 1 or 11 points, whichever is more advantageous for the hand.

### Gameplay

1. Each player, including the dealer, is dealt two cards at the beginning of the round.
2. Players take turns deciding whether to "hit" (take another card) or "stand" (keep their current hand).
3. The dealer follows a set of rules for taking cards. Typically, the dealer will hit until their hand value is at least 17.
4. If a player's hand value exceeds 21, they bust and lose the round.
5. The player with a hand value closest to 21 without going over wins the round. In case of a tie, it's a push (no winner).

### Special Case: Blackjack

If a player or the dealer is dealt an Ace and a card with a value of 10 (10, Jack, Queen, King) as their initial two cards, they have a "Blackjack" and win the round unless the opponent also has a Blackjack, resulting in a push.

## How to Run the Game

1. Ensure you have Java installed on your machine.
2. Compile the Java files using a Java compiler. For example:
   ```bash
   javac *.java
   ```
3. Run the compiled BlackjackGame class:
   ```bash
   java BlackjackGame
   ```
Follow the on-screen prompts to play the game. Enter 'h' to hit, 's' to stand, and 'yes' or 'no' to play another round.

## Example Usage
```bash
Welcome to Blackjack!

Player 1's hand: 10 of Hearts, Ace of Spades (Value: 21)
Computer's hand: 7 of Diamonds and an unknown card

Do you want to play another round? (yes/no): yes
```

## Notes
This is a simplified version of Blackjack and may not include all the rules and variations found in a casino setting.
The computer player follows a basic strategy of hitting until their hand value is at least 17.
Have fun playing Blackjack!
   
