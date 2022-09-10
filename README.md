#Problem Statement <br />
Write a C++ program to build a mini cricket application named Gully Cricket App.<br />
#Project Requirements <br />
1. There should be two teams: TeamA and TeamB <b<br />r />
a. Each team will have 3 players. <br />
b. The 
player names will not be entered by the user. You can assign names to the players yourself <br />
3. There should be two innings <br />
a. Each inning will be of 6 balls (one over) <br />
i. In each inning, one batsman from the batting team will bat for 6 balls and one bowler from the bowling team will bowl 6 deliveries <br />
ii. One batsman from the batting team and one bowler from the bowling team will be selected randomly for each inning <br />
b. TeamA will always bat first which means TeamB will always bowl first.<br />
3. In each delivery, runs can be scored from 0 to 6.<br />
4. There will be no criteria to get wickets. In simple words, once a batsman starts his inning, he will bat for all the 6 balls without getting out/dismissed/retired hurt etc.<br />
5. After completion of two innings i.e. after each team has done batting, scored runs will be compared to decide the winner or to decide if there is a tie.
**Note:** The match will conclude only after each batting team has faced 6 deliveries. In the second inning, at any point of time during the match, if the score of TeamB is greater than the runs scored by TeamA (in the first inning) then the match should not end. The match should continue until TeamB has faced all the 6 deliveries.<br />
#Rough Algorithm<br />
1. Create a class Team that can store the following data<br />
 a. Team name<br />
 b. The three players<br /> 
 c. Total runs scored<br />
2. Greet user with a welcome message<br />
3. Initialize two teams<br />
4. Display team details<br />
5. Select a batsman and a bowler for the first inning<br />
6. Start playing the first inning<br /> 
7. Record total runs scored by the batting team in the first inning<br /> 
8. Select a batsman and a bowler for the second inning<br /> 
9. Start playing the second inning<br />
10. Record total runs scored by the batting team in the second inning<br />
11. Decide the winner<br />
#Approach<br />
1. Create a class Team that can store the following data:<br /> 
 a. Team name<br />
 b. The three players<br /> 
 c. Total runs scored<br /> 
2. Create two global variables to store the name of the current batsman and current bowler in the inning being played<br /> 
3. Define functions to perform each task in the app. For example, define the following functions to perform a specific task<br /> 
 a. A function to greet the user with a welcome message<br /> 
 b. A function display players of each team<br /> 
 c. A function to randomly select a batsman and a bowler from the respective teams before the inning starts.<br />
 d. A function to start the inning with current batsman and current bowler details when the inning starts<br />
 e. A function to play cricket in each inning<br />
 f. A function to display runs scored by batting team at the end of each inning<br />
 g. A function to decide the winner and print the final message<br /> 
4. Use escape characters such as ‘\t’, ‘\n’ wherever needed to keep program output clean<br /> 
5. Use usleep() function as applicable along with user-friendly messages<br />
**Note:** In the above given ‘Approach’ section, each task may require more than one function. It is totally up to you how you write code to perform a task. You can take help from the given code template to build the Gully Cricket Application.<br />
