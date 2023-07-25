**README - Vowel, Consonant, and Digit Counter**

**Description:**
This C++ program allows users to input a string (without spaces) and then counts the number of vowels, consonants, and digits in the input string. The program uses a simple loop to iterate through each character of the input string and increment the corresponding counters based on the character's type.

**Compilation and Execution:**
To compile and run the program, follow the steps below:

1. Save the provided C++ code in a file named "main.cpp" (or any other preferred filename with a .cpp extension).

2. Ensure you have a C++ compiler installed on your system (e.g., GCC or MinGW for Windows users).

3. Open a terminal or command prompt and navigate to the directory where the "main.cpp" file is saved.

4. Compile the C++ code using the following command:
   ```
   g++ -o vowel_consonant_digit_counter main.cpp
   ```
   This will generate an executable file named "vowel_consonant_digit_counter" (or any other specified name after `-o`).

5. Run the program by executing the generated executable:
   ```
   ./vowel_consonant_digit_counter
   ```
   For Windows users, the command would be:
   ```
   vowel_consonant_digit_counter.exe
   ```

**Usage:**
1. When the program is executed, it will prompt the user to enter a string (without spaces).

2. After entering the string and pressing the Enter key, the program will analyze the input and display the results.

**Input Constraints:**
- The input string must not contain any spaces.

**Output:**
The program will display the following statistics about the input string:
- Number of vowels
- Number of consonants
- Number of digits

**Example:**
```
Enter a string (without spaces): Hello123

Results
----------------------
Vowels: 2
Consonants: 3
Digits: 3
```

**Note:**
- The program treats uppercase and lowercase vowels and consonants as separate entities.
- Any non-alphabetic characters (other than digits) will be considered consonants.

**License:**
This program is provided as-is without any warranty. You are free to use, modify, and distribute it for educational or personal purposes. However, use it at your own risk, and the author shall not be liable for any damages or issues caused by its usage.
