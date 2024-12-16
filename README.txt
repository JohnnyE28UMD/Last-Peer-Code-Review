RULES and GUIDE to the DICE GAME
    Before playing the game, there are rules to understand. 
    1. There will only be 2 players when playing the game. 
    2. Each player will get 3 randomly generated numbers.
    3. The sum of all of these numbers will be your score.
    4. If any of these numbers are the same such as [1,1,2], then you will only be allowed to roll the number at the index that does not have the matching number.
    5. If all 3 numbers are the same, then you will automatically get 0 points.
    6. If all 3 numbers are different such as [1,3,6], you can pick which dice to re-roll BUT remember rules 4 and 5. If you re-roll and get 2 of the same numbers,
        those numbers will be fixed. If the last dice ends up being the same number, you will get a total of 0 points. Be CAREFUL!

PLAYING AND USING THE GAME
    1. First open the game by typing out "python consolidation_final.py". This will open and start the dice game.
    2. The game will start with player 1. Once player one is done with their turn, player two will go.
        There is only one round of this game.
    3. The game starts off giving the first player 3 randomly generated numbers.
    4. Depending on those numbers, they will have a chance to reroll. The game will ask you if you would like to reroll. Click Y for yes and N for no. 
        If you do not click Y or N, the game will continuously ask you to click Y or N.
        If you do not want to reroll, you will type out "EXIT" in all Caps.
    5. If you do not want to reroll any numbers or are unable to reroll any numbers, your turn will be over.
    6. Remember you can reroll as much as you want as long as it does not break rules 4-6 above under the GUIDE.
    7. After this, player two will go and repeat steps 1-5. 
    8. The game will then tell you the score of both players at the end and say who won.

ADVANCED FUNCTIONS EXPLAINED (NUMPY AND TIME)
    1. In this game, numpy and time are both imported to be used for different reasons.
    2. numpy is used to create an array which then has the "final_result" values added to it. Once each of the final_results are added to it per round, the average 
        value of all the rounds in the array is taken. Depending on if the array is greater or less than or equal to the average of 3 dice, a phrase will be 
        printed in the output.
    3. time is used in two separate ways. time.sleep is used to create suspense towards the end of the program when determining if the average points of the players
        is greater than, less than, or equal to the average of 3 dice. Time is also used at the start and end of the program. From the second you start the game to 
        the second the game is over, the time is measured in seconds and will tell the player in a statement how long they have played the game for. 
