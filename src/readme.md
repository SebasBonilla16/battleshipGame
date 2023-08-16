Java Battleship Game Program

This Java program implements the classic game of Battleship! With this program, you can enjoy a game of Battleship right in your console. Your objective is to sink three battleships: Pain, Orochimaru, and Madara using as few guesses as possible.

Functionality of the Code:

The code comprises three primary classes:

1. BattleshipGame: This class initializes and manages the entire game process. It handles battleship setup, displays game instructions, captures user guesses, validates guesses, and concludes the game upon sinking all battleships.

2. Battleship: Representing the actual ships, this class has a name and a list of location cells. The "checkYourself" method evaluates a user's guess and determines whether it's a hit, miss, or a ship has been destroyed.

3. GameHelper: This class manages user input, battleship placement, and various game computations. It generates random starting positions for battleships, coordinates conversion, and startup position validity checks.

Running the Code:

Follow these steps to run the Battleship game:

1. Compilation: Open a terminal and navigate to the directory containing the files "BattleshipGame.java," "Battleship.java," and "GameHelper.java." Compile the Java files using this command:
   
    javac BattleshipGame.java

2. Execution: After compilation, run the Battleship game with the following command:
  
    java BattleshipGame

3. Gameplay: Follow the on-screen prompts to input your guesses and play the game. The program will provide feedback on whether your guesses hit, missed, or sunk a ship.

4. Quitting: To exit the game, simply close the terminal or press Ctrl+C.

Note
In the GameHelper class, lines 165, 176, and 195 are commented out to prevent interference with gameplay. If you wish to observe the ship placement process, you can uncomment these lines. However, during actual gameplay, keep these lines commented to avoid revealing ship positions to the user.

Enjoy your Battleship game(or games :P )! Should you have any inquiries or require further assistance, feel free to reach out to me at sebastianbonillaleal@gmail.com
