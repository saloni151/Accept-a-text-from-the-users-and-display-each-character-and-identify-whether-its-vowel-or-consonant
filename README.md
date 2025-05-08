# Accept-a-text-from-the-users-and-display-each-character-and-identify-whether-its-vowel-or-consonant
This Python program encourages the user to input a line of text and then analyzes each character to determine whether it's a vowel, a consonant, or a space.

# Features
1. Accepts user input as a line of text.

2. Iterates through each character in the input.

3. Identifies and displays whether each character is:

- A vowel (a, e, i, o, u,A,E,I,O,U)

- A consonant (any other alphabetic character)

- A space

Outputs a final message indicating the end of the program.

# How to Implement
1. The program encourages the user to enter a line of text.

2. It defines a list of vowels for comparison.

3. Using a while loop, it iterates through each character in the input:

4. If the character is a space (" "), it prints "It is a space".

5. If the character is found in the list of vowels, it prints that the character is a vowel.

6. If the character is an alphabetic character but not a vowel, it prints that the character is a consonant.

7. Non-alphabetic characters (excluding spaces) are also treated as consonants in this implementation.

8. After processing all characters, it prints "The program is over".

