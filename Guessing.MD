##Guessing Game Flowchart
```mermaid
flowchart TD
A[Start/Generates a random number] --> Z[Prompt the user to guess] --> B{Does the user guess correctly?};
B -- Yes --> C[Congradulate the user] --> Y[End];
B -- No --> D{Did the user guess too high or too low?};
D -- Too High --> E[Inform the user the guess is too high] --> Z[Prompt the user to guess];
D -- Too Low --> F[Inform the user the guess is too low] --> Z[Prompt the user to guess];
```
The guessing game first generates a random number, then prompts the user to guess the number. If the user guessed correctly, it will congratulate the user and exit.
If the user guessed incorrectly, it evaluates if the guess was too high or too low. If the guess was too high, it informs the user that the guess was too high,
and then prompts the user to guess again. If the guess was too low, it informs the user the guess was too low, and then prompts the user to guess again.
The user keeps guessing until they guess correctly or quit.
