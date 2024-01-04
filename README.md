# Simple Bot Program

## Overview

The Simple Bot is a Java console application designed to interact with users by performing a series of tasks including greeting, name recognition, age guessing, counting, and testing the user's basic programming knowledge.

## Features

- **Greeting**: The bot introduces itself and requests the user's name.
- **Name Reminder**: The bot acknowledges the user's name in a friendly manner.
- **Age Guess**: The bot estimates the user's age using remainders provided by the user.
- **Counting**: The bot demonstrates its ability to count up to a number specified by the user.
- **Knowledge Test**: The bot quizzes the user with a simple programming question.
- **Farewell**: The bot ends the interaction with a congratulatory message.

## Requirements

- Java Runtime Environment (JRE) or Java Development Kit (JDK) to run the Java program.
- No external libraries are required.

## Installation

To use the Simple Bot, follow these steps:

1. Ensure Java is installed on your system. You can check by running `java -version` in your command line.
2. Download the `SimpleBot.java` file to your local system.
3. Compile the program using `javac IntroductionToJava/SimpleBot.java` from the command line within the directory where the file is located.
4. Run the compiled program with `java IntroductionToJava.SimpleBot`.

## Usage

Once the program is running, simply follow the on-screen prompts:

1. Enter your name when the bot asks for it.
2. Provide the remainders of your age when divided by 3, 5, and 7 to let the bot guess your age.
3. Tell the bot how high to count, and it will count out loud for you.
4. Answer the programming knowledge question by entering the number corresponding to the correct answer.
5. Once you answer the question correctly, the bot will congratulate you and wish you a nice day.

## Example Interaction

```
Hello! My name is Joudi.
I was created in 2000.
Please, remind me your name.
> John
What a great name you have, John!
Let me guess your age.
Enter remainders of dividing your age by 3, 5, and 7.
> 1
> 2
> 1
Your age is 22; that's a good time to start programming!
Now I will prove to you that I can count to any number you want.
> 5
0!
1!
2!
3!
4!
5!
Let's test your programming knowledge.
Why do we use methods?
1. To repeat a statement multiple times.
2. To decompose a program into several small subroutines.
3. To determine the execution time of a program.
4. To interrupt the execution of a program.
> 2
Congratulations, have a nice day!
```

## Troubleshooting

- If the program does not compile, ensure you have the correct Java version installed and that the `javac` command is properly executed.
- If the bot does not accept your input, make sure you are entering the expected data type (e.g., integers for age remainders).

## License

The Simple Bot is open-source and free to use. There is no license associated with this sample code.
