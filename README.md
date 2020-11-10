# Guess the number

(Read the problem and then read the breakdown section)

You will build the "Guess the number" page. This is a 2 players game. The first player is giving a number between 1 and 10 while the second is not looking. Then the second player is trying to guess the number. The player receives a message, depending on the guess ("Your guess is lower" or "Your guess is higher" or "You guessed the number!"). Note that you should verify the data entry of the first player and give the appropriate message.

## Breakdown
When we have a complex problem, we should break it down to smaller parts so we can handle them. Here we have two problems:
1. Get the number (let's name it "target") from the first player and verifiy the data entry and
2. Get the "guess" from the second player and evaluate it with regard to the "target"
The first problem can be break into two simpler problems:
1.1 Get the "target"" from the first player and
1.2 verify that "target" is inside the limits (1-10)
The second problem can be break into two simpler problems:
2.1 Get the "target"" from the first player and
2.2 Compare it to "target" and display the approprite message
I think that you can work from here on. If not, please read the steps you should follow, at the bottom of the message.

## Testing
In order to test your page, you should try all possible values:
* give a proper "target" value, a less than 1, a more than 10; so you will check the data entry verification.
* give a correct "guess" value, a smaller, a larger; so you will check the evaluation. 


## Steps for guess.html
1. Prompt the user for the "target" number (here the user is the first player)
2. Check if the "target" is lower than 1 and display a message if it is.
3. Otherwise check if the "target" is higher than 10 and display a message if it is
4. (Optional. Try to combine the two conitions above into one if-else if).
5. Prompt the user for the "guess" (here the user is the second player)
6. Check if the guess is lower than the target. If so, display a message.
7. Otherwise check if the guess is higher. If so, display a message.
8. Otherwise the user guessed the number so display a message.