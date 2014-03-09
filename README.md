So here's a puzzle for you.

You start with an empty string and clipboard. You can perform four operations:

    Append a character to the string
    Delete a character from the end of the string
    Copy the entire string into the clipboard
    Paste the contents of the clipboard at the end of the string

Each operation takes a different amount of time:

    Append takes 1 tick
    Delete takes 1 tick
    Copy takes 3 ticks (CTRL-A-C)
    Paste takes 2 ticks (CTRL-P)

The question is *"What's the shortest string length that requires a delete to create most efficiently?"*.

This is an IHaskell notebook explaining how to find a solution. [Read on for more](http://rampion.github.io/CopyPastePuzzle/).
