##Guessing Game Flowchart
```mermaid
flowchart TD
A[Start/Generates a random number] --> Z[Prompt the user to guess] --> B{Does the user guess correctly?};
B -- Yes --> C[Congradulate the user] --> Y[End];
B -- No --> D{Did the user guess too high or too low?};
D -- Too High --> E[Inform the user the guess is too high] --> Z[Prompt the user to guess];
D -- Too Low --> F[Inform the user the guess is too low] --> Z[Prompt the user to guess];
```
