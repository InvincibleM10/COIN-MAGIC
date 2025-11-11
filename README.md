Aim of the Project
The aim of the "Coin Magic" project is to create and implement a fun console-based casino game in C++ that allows players to wager virtual money to participate in a range of number-based guessing games. Players can test their luck and decision-making skills by predicting the results of various number games in an organized and aesthetically pleasing menu-driven environment. The main goal is to create an engaging and entertaining experience that illustrates fundamental ideas of object-oriented programming, such as classes, inheritance, and polymorphism.

Objective
•	To create an interactive casino game using numbers that showcases the use of C++ object-oriented programming ideas like inheritance, classes, and polymorphism.  
•	To offer a menu-driven, aesthetically pleasing console interface that allows users to wager, deposit virtual currency, and play a variety of number-guessing games. 
•	To incorporate features for managing money, such as betting, winning, losing, and withdrawing amounts, as well as strong input validation and game flow control.  
•	Incorporating user-driven decision-making and chance-based outcomes, the goal is to replicate the dynamics of a real casino game while guaranteeing that the first round is always a win, the second is always a loss, and subsequent rounds yield random results.  
•	To incorporate easy navigation, educational feedback, and clear instructions throughout the game process in order to improve user engagement and the programming experience.

Tools and Technologies Used
•	Programming Language:
C++ (Object-Oriented Programming)
•	Development Environment:
Dev-C++ IDE (Integrated Development Environment) or any standard C++ compiler.
•	Standard Libraries:
•	<iostream> for console input/output
•	<vector> and <memory> for dynamic data structures and smart pointers
•	<cstdlib> and <ctime> for random number generation
•	<limits> for robust input validation
•	Platform:
Console-based application, compatible with Windows and other operating systems supporting standard C++.
•	Object-Oriented Concepts:
Classes, inheritance, and polymorphism for modular and scalable game structure. 
System Requirements
•	Operating System:
Windows XP or later, or any OS with a standard C++ compiler (e.g., Linux, macOS).
•	Processor:
Intel Pentium IV or equivalent (any basic modern processor)
•	Memory (RAM):
Minimum 512 MB RAM
•	Storage:
At least 10 MB free space for source files and executable
•	Software Dependencies:
•	Dev-C++ IDE, Code::Blocks, Visual Studio, or any C++ development environment
•	C++11 (or above) compatible compiler (for use of smart pointers and modern C++ features)
•	Display:
Console window capable of running C++ applications

Algorithm / Logic
1.	Start the Program:
Initialize random number generator to ensure each run is different.
2.	Display Welcome Screen:
Show the “COIN MAGIC” heading and introduction.
3.	Player Registration and Deposit:
•	Prompt user to enter their name (store for future references).
•	Ask user to deposit an initial amount (minimum ₹2000); reject if below minimum.
4.	Main Game Loop:
Repeat the following steps while player’s balance is at least ₹500:
•	Display player name, current balance, and menu of five number-based game options.
•	Prompt user to choose a game and enter a bet amount (minimum ₹500, not more than current balance); validate input.
5.	Game Play:
•	Call the selected game’s logic, passing the current round number.
•	Each number game prompts for a guess (odd/even, high/low, range, number, dice).
•	The actual number is shown and compared to the player’s guess to determine win or loss.
6.	Update Balance:
•	If player wins: add bet amount to balance.
•	If player loses: deduct bet amount from balance.
•	Display result and updated balance.
7.	After Each Round:
•	Ask the player if they want to play another game or withdraw money.
•	If “withdraw”, prompt for amount (up to current balance) and deduct; if balance is zero after withdrawal, exit.
•	If “play again”, continue loop, increasing round counter.
8.	Exit Condition:
End program if player’s balance falls below ₹500 or after full withdrawal.
Display a thank you message with the “COIN MAGIC” branding.
