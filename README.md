# C++ Terminal Game Suite

Two casino-style game simulations written in C++: a roulette wheel and a slot machine. Both are standalone terminal applications with full game loops, input validation, balance tracking, and randomised outcomes seeded from system time.

## Roulette

A red/black roulette simulator with a menu-driven betting interface.

- Three bet sizes (100 / 300 / 500 kr)
- Bet type selection: red, black, or exact number
- Randomised spin results with srand(time(0)) seeding
- Balance tracking with win/loss calculation
- Input validation with cin.fail() and stream recovery

## Slots

A 3x3 slot machine with multi-line win detection.

- Symbol grid randomly populated on each spin
- Win detection across rows, columns, and both diagonals
- Bonus condition: full-grid match for maximum payout
- Configurable bet sizing with payout multipliers
- Balance management and bust detection

## Stack

C++, standard library only (iostream, cstdlib, ctime, limits)
