# Password Generator

This is a simple password generator program written in Java. The program generates a random password based on a specified length, including lowercase letters, uppercase letters, digits, and special characters.

## Features

- Generates a random password of specified length.
- Includes lowercase letters, uppercase letters, digits, and special characters.

## Requirements

- Java Development Kit (JDK) 8 or higher

## How to Use

1. **Clone the repository**:

    ```sh
    git clone https://github.com/sulogna2001/generate_password.git
    ```

## Code Explanation

The program includes the following key components:

1. **Character Sets**: 
    - `lower_cases`: String containing all lowercase letters.
    - `upper_cases`: String containing all uppercase letters.
    - `special_characters`: String containing common special characters.
    
2. **Password Generation**:
    - The program reads the desired password length from the user.
    - It then iterates over the specified length, randomly selecting characters from the combined character sets (lowercase, uppercase, digits, special characters).
    - The resulting password is printed to the console.

## Example

Here is a sample execution of the program:

```sh
Enter the length of the password: 12
Generated Password: 4gH@2kL#9mN$
