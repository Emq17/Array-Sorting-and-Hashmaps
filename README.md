<p align="center">
<img src="https://i.imgur.com/arX3quW.png" alt="Logo"/>
</p>

<h1 align="center">Array Sorting And Hashmaps</h1>


- Part 1: This program is a simple quiz game that tests the user's knowledge of US state capitals. The program first
defines a static two-dimensional array called "stateCapitalPairs" which contains the names of US states as
well as their corresponding capitals. Then, the program defines three methods. The first method, 
"displayStateCapitalPairs()", simply prints out the list of state-capital pairs to the console. The second
method, "sortStateCapitalPairsByCapital()" sorts the "stateCapitalPairs" array in alphabetical order by 
capital name. Finally, the third method, "promptUserandCheckAnswers()", prompts the user to answer the 
capital city of each state and checks the user's answers against the correct answer stored in the 
"stateCapitalPairs" array. The program keeps track of the number of correct answers and displays the total
score the end. The "main()" method simply calls the three other methods in order to display the 
state-capital pairs, sort them, and prompt the user for answers. Overall, this program is a simple yet 
effective way to test and improve one's knowledge of US state capitals.

- Part 2: This Java code implements a simple quiz program that prompts the user to enter a state name and displays its 
capital. The program uses a HashMap data structure to store the state-capital pairs, where the state name is the
key and the capital name is the value. The program first initializes the may by adding state-capital pairs for 
the 50 US states. It then displays the unsorted list of state-capital pairs and then sorts the pairs 
alphabetically by state name using a TreeMap. The program then enters a loop where it prompts the user to enter 
a state name until a valid input is provided. The program handles different input cases, such as empty input, 
and the input "exit" to exit the program. If the user matches a state name in the sorted state-capital pairs map,
the program retrieves the corresponding capital name and displays it. Otherwise, the program indicates that the 
state name was not found. Finally, the program closes the scanner object that was used for user input. 
