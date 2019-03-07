**Project Overview: Nondeterministic Finite Automaton (NFA) Simulator**

**Objective:**
The provided C++ program simulates a Nondeterministic Finite Automaton (NFA). It allows users to define the NFA's states, final states, alphabet, transitions, and check strings against the defined NFA.

**Components:**
1. **`NFA.hh`**: Header file for the NFA class declaration and its member functions.
2. **`Menu.hh`**: Header file for the Menu class declaration and its member functions.
3. **`main.cpp`**:
   - Includes necessary headers, declares a Menu instance, an NFA instance, and a string variable.
   - Defines a menu with options to manage NFA configuration and string checking.
   - Utilizes a loop to continuously display the menu and execute the selected option.

**Classes:**
1. **`NFA` Class:**
   - Manages the NFA configuration.
   - Enables users to define states, final states, alphabet, transitions, and check strings against the NFA.
   - Provides functionality to show transitions, save NFA configuration, and load NFA configuration.

2. **`Menu` Class:**
   - Manages the menu interface.
   - Allows the addition of submenus and the execution of menu options.

**Menu Options:**
1. **Define States (Option 1):**
   - Allows users to define states for the NFA.

2. **Define Final States (Option 2):**
   - Allows users to define final states for the NFA.

3. **Define Alphabet (Option 3):**
   - Enables users to define the alphabet for the NFA.

4. **Define Transitions (Option 4):**
   - Allows users to define transitions for the NFA.

5. **Show Transitions (Option 5):**
   - Displays the transitions of the NFA.

6. **Check String (Option 6):**
   - Prompts users to enter a string and checks whether it is accepted by the NFA.

7. **Save NFA Configuration (Option 7):**
   - Saves the NFA configuration to a file.

8. **Load NFA Configuration (Option 8):**
   - Loads the NFA configuration from a file.

9. **Exit (Option 9):**
   - Exits the program.

**User Interaction:**
- Users can interact with the NFA by defining its properties and checking strings against it through the menu-driven interface.

**Compilation Instructions:**
- Compilation instructions are provided as comments at the beginning of the main file.

**Conclusion:**
This NFA Simulator offers a convenient way for users to define and interact with a Nondeterministic Finite Automaton. The menu-driven approach enhances user experience, providing functionalities to define states, final states, alphabet, transitions, and check strings for acceptance by the NFA.

HOW TO COMPILE:

g++ -c NFA.cc
g++ -c main.cc
g++ main.o NFA.o -o NFA
./NFA
