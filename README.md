# Interactive Chatbot

## Description
This is a simple interactive chatbot written in Python. The chatbot engages users by greeting them, guessing their age based on input remainders, counting to a specified number, and testing their programming knowledge. The project is designed to demonstrate basic programming concepts such as functions, input/output operations, and control flow.


## Installation
1. Clone the repository:
git clone https://github.com/yourusername/interactive-chatbot.git
2. Navigate to the project directory:
cd interactive-chatbot
3. Ensure you have Python 3.x installed on your machine.
## Usage
To run the chatbot, use the following command:
python chatbot.py

Follow the prompts in the terminal to interact with the chatbot.

## Features
- **Greeting**: The bot introduces itself and shares its creation year.
- **Name Reminder**: Asks the user for their name and acknowledges it.
- **Age Guessing**: Guesses the user's age based on the remainders of dividing their age by 3, 5, and 7.
- **Counting**: Counts from 0 to a user-specified number.
- **Programming Quiz**: Tests the user's knowledge of programming concepts with a multiple-choice question.

## Code Structure
The script consists of several functions:
- `greet(bot_name, birth_year)`: Greets the user and displays the bot's name and birth year.
- `remind_name()`: Prompts the user to enter their name.
- `guess_age()`: Asks for remainders to guess the user's age.
- `count()`: Counts from 0 to a specified number provided by the user.
- `test()`: Tests the user's programming knowledge with a multiple-choice question.
- `end()`: Concludes the interaction with a friendly message.

## Customization
You can customize the bot's name and birth year in the `greet()` function call at the bottom of the script:
