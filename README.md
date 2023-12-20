# Array-Sorting-and-Hashmaps

This Java code implements a simple quiz program that prompts the user to enter a state name and displays its 
capital. The program uses a HashMap data structure to store the state-capital pairs, where the state name is the
key and the capital name is the value. The program first initializes the may by adding state-capital pairs for 
the 50 US states. It then displays the unsorted list of state-capital pairs and then sorts the pairs 
alphabetically by state name using a TreeMap. The program then enters a loop where it prompts the user to enter 
a state name until a valid input is provided. The program handles different input cases, such as empty input, 
and the input "exit" to exit the program. If the user matches a state name in the sorted state-capital pairs map,
the program retrieves the corresponding capital name and displays it. Otherwise, the program indicates that the 
state name was not found. Finally, the program closes the scanner object that was used for user input. 
