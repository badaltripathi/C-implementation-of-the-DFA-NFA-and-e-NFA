**Project Overview: Nondeterministic Finite Automaton with ε-transitions (e-NFA) Simulator**

**Objective:**
The provided C++ program simulates a Nondeterministic Finite Automaton with ε-transitions (e-NFA). It enables users to define the e-NFA's states, final states, alphabet, transitions, and allows checking strings against the defined e-NFA.

**Components:**
1. **`e_NFA.hh`**: Header file for the e_NFA class declaration and its member functions.
2. **`Menu.hh`**: Header file for the Menu class declaration and its member functions.
3. **`main.cpp`**:
   - Includes necessary headers, declares a Menu instance, an e_NFA instance, and a string variable.
   - Defines a menu with options to manage e-NFA configuration and string checking.
   - Utilizes a loop to continuously display the menu and execute the selected option.

**Classes:**
1. **`e_NFA` Class:**
   - Manages the e-NFA configuration.
   - Enables users to define states, final states, alphabet, transitions, and check strings against the e-NFA.
   - Provides functionality to show transitions, save e-NFA configuration, and load e-NFA configuration.

2. **`Menu` Class:**
   - Manages the menu interface.
   - Allows the addition of submenus and the execution of menu options.

**Menu Options:**
1. **Define States (Option 1):**
   - Allows users to define states for the e-NFA.

2. **Define Final States (Option 2):**
   - Allows users to define final states for the e-NFA.

3. **Define Alphabet (Option 3):**
   - Enables users to define the alphabet for the e-NFA.

4. **Define Transitions (Option 4):**
   - Allows users to define transitions for the e-NFA.

5. **Show Transitions (Option 5):**
   - Displays the transitions of the e-NFA.

6. **Check String (Option 6):**
   - Prompts users to enter a string and checks whether it is accepted by the e-NFA.

7. **Save e-NFA Configuration (Option 7):**
   - Saves the e-NFA configuration to a file.

8. **Load e-NFA Configuration (Option 8):**
   - Loads the e-NFA configuration from a file.

9. **Exit (Option 9):**
   - Exits the program.

**User Interaction:**
- Users can interact with the e-NFA by defining its properties and checking strings against it through the menu-driven interface.

**Compilation Instructions:**
- Compilation instructions are provided as comments at the beginning of the main file.

**Conclusion:**
This e-NFA Simulator offers a convenient way for users to define and interact with a Nondeterministic Finite Automaton with ε-transitions. The menu-driven approach enhances user experience, providing functionalities to define states, final states, alphabet, transitions, and check strings for acceptance by the e-NFA.

HOW TO COMPILE:

g++ -c e_NFA.cc
g++ -c main.cc
g++ main.o e_NFA.o -o e_NFA
./e_NFA
