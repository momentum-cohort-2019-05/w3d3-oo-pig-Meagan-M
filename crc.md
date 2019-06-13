class PGDie
    rolls die
    returns a number (1-6)
collaborators: Score

class Score
    tracks each player's turn score
    tracks the total game score for each player
collaborators: HumanPlayer, ComputerPlayer

class Turn
    randomly selects initial player
collaborators: HumanPlayer, ComputerPlayer

class HumanPlayer
    requests user input to roll or hold for each turn
        or
    until player rolls a 1 and turn is over
collaborators: PGDie, Score, Turn 

class ComputerPlayer
    rolls until score is 20 each turn
        or
    until player rolls a 1 and turn is over
collaboarators: PGDie, Score, Turn
