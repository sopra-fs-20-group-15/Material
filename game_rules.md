### Game Rules

Basic idea: There are three distinct mechanisms that influence a players score:

- Normal points:
    -- they are distributed among the players if the correct word is guessed by the active player
    -- since guessing the correct word requires good clues as well as the intuitiv intelligence of the active player, all players get points
    -- the passive players who give the clues get 15 points each
    -- the active player who guessed the clue gets 20 points

- Bonus points:
    -- both passive and active players can score bonus points
    -- the amount of bonus points a passive player gets, is determined by how fast he can come up with a clue, these are the different time frames and corresponding bonus points (the time frames show the state of the timer at the time of submitting the clue):
    - 25-30 seconds: +6 points
    - 20-25 seconds: +5 points
    - 15-20 seconds: +4 points
    - 10-15 seconds: +3 points
    - 5-10 seconds: +2 points
    - 0-5 seconds: +1 points

    -- the amount of bonus points an active player gets, is determined by how fast he can guesses the word, these are the different time frames and corresponding bonus points (the time frames show the state of the timer at the time of submitting the guess):
    - 20-30 seconds: +5 points
    - 10-20 seconds: +3 points
    - 0-10 seconds: +1 points
    
    -- bonus points are only distributed if the correct word is guessed at the end of the round, this should ensure that player stick to the main goal of the game instead of going on ego trips

- Negative points:
    -- if a passive players guess is eliminated due to being a duplicate of another players guess, the player gets negative points
    -- the more duplicates of a word there are in a round, the more points are subtracted from a players score:
    - one duplicate: -5
    - two duplicates: -10
    - three duplicates: -15
    - four duplicates: -20
    - five duplicates: -25
    - six duplicates: -30

Note: During the development and test playthroughs the point system might be adjusted, if any unbalance is noticed.