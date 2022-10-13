# RockPaperandScissors
I have created a game (Rock, Paper and Scissors) using a few custom functions, random module and looping concept here

Step 1, 
Getting the computer choose randomly between Rock, Paper and Scissors. 
I have used Random Module to generate a random integer between 1 and 3 and created the 'get_computers_choice()' function.
A random number between 1 and 3 is assigned to the random_number variable.
If random number is, 1 = 'Rock', 2 = 'Paper', 3 = 'Scissors'.
Then with the help of dictionary, I have assigned these as Key-Value pairs and reurned the computer's choice({1:'Rock', 2:'Paper', 3:'Scissors'}).
Basically this function will be returning eihter of 'Rock'/'Paper'/'Scissors'

Step 2,
Now, to get the user input I have created another function 'get_user_input()' where the return value should be either of 'Rock'/'Paper'/'Scissors'.
Since the input should be any one of (rock/paper/scissors) and not anything else, I added an if statement checking whether the input is in the mentioned list of ['rock,'paper','scissors], if it is, it will break.
I have then converted the input to lowercase as it should be matching with the computer's value.

step 3,
Now to decide if its a draw/win/lose, I have created another function 'get_result(users_pick, computers_pick)'.
The 2 arguments passed inside the function will fetch the computer's choice as well as the user's choice
Through conditional statements, if computers_pick == users_pick, I have set to return 'draw'.
We see this from the users view, therefore, If it is {'scissors' : 'paper' or 'rock' : 'scissors' or 'paper' : 'rock'} I have set to return 'win'.
Unless return 'lose' (if any of the top conditions fail)

Step 4,
Printing the results in this step using print function while passing the computer's pick, user's pick, result in quotes as strings and passing the values correspondingly.
