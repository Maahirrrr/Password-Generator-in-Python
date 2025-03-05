# Password Generator

A simple Python project to generate a random password based on user-defined length. The program includes numbers, letters (both lowercase and uppercase), and a wide variety of special characters.

## Features

- **Random Password Generation:** Creates a secure, random password.
- **Customizable Length:** User can specify the length of the password.
- **Extensive Character Set:** Uses digits, letters, and many special characters.

## How It Works

1. **Character Set:**  
   The program defines a string containing all characters that can be used in the password. This includes:
   - Digits: `1234567890`
   - Lowercase letters: `abcdefghijklmnopqrstuvwxyz`
   - Uppercase letters: `ABCDEFGHIJKLMNOPQRSTUVWXYZ`
   - Special characters: `!@#$%^&*()_+-=[]{}|;:'",.<>?/~\``

2. **Password Generation:**  
   It asks the user for the desired length of the password, then randomly selects characters from the set until the password reaches the specified length.

3. **Output:**  
   The final generated password is displayed to the user.

## How to Use

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/password-generator.git
