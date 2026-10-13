# Wordle Solver (C)

A solver for five-letter word-guessing games. Give it a secret word and it searches the vocabulary for it — or play interactively: it proposes guesses and narrows the field using your green/yellow/gray feedback until only the answer remains.

## What's inside

- **solver.c** — the solver program (automatic mode with a target word, or interactive mode driven by feedback).
- **search_util.c / search_util.h** — vocabulary loading, letter scoring, and the filtering logic that applies feedback to cut the candidate set.
- **vocabulary.txt** — the word list it searches.

## Build & run

```sh
make            # builds solver
./solver irate  # solve for a known word, or run with no argument to play interactively
```

## Tech

C, Make
