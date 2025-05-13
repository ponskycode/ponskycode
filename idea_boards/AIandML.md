# AI and ML idea board

Where ideas go to sleep.

## Spider Solitaire RL AI solver
1. **Scope.**
Lets reduce the scope to one suit of cards. Then separate into three demo versions:
- The most basic, no cards hidden, six columns, the number of cards cut in half
- Medium, same as above but with hidden cards
- The full game, though with one suit only

2. **Environment.**
The place where the agent will be learning. In short what is needed:
    - Game state representation (tableau, stock, foundation, etc.)
    - Rule implementation (legal moves, winning conditions, etc.)
    - Maybe support for undoing moves?

3. **Evaluation and Iteration.**
    - Track win rates, average of moves, average rewards
    - Test on randomly generated conditions
    - Add complexity gradually?

&nbsp;
```
Useful libraries:
- gymnasium (gym)
- stable-baseline3
- numpy
- torch
```