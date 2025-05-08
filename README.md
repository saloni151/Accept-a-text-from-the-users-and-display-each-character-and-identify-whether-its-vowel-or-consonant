# Accept-a-text-from-the-users-and-display-each-character-and-identify-whether-its-vowel-or-consonant
This Python program encourages the user to input a line of text and then analyzes each character to determine whether it's a vowel, consonant, or space.

# Features
Accepts user input as a line of text.

Iterates through each character in the input.

Identifies and displays whether each character is:

A vowel (a, e, i, o, u,A,E,I,O,U)

A consonant (any other alphabetic character)

A space

Outputs a final message indicating the end of the program.

# How to Implement
The program prompts the user to enter a line of text.

It defines a list of vowels for comparison.

Using a while loop, it iterates through each character in the input:

If the character is a space (" "), it prints "It is a space".

If the character is found in the list of vowels, it prints that the character is a vowel.

If the character is an alphabetic character but not a vowel, it prints that the character is a consonant.

Non-alphabetic characters (excluding spaces) are also treated as consonants in this implementation.

After processing all characters, it prints "The program is over".

