# Tic Tac Toe vs Bot

A single-file Tic Tac Toe game where you play against an unbeatable bot 
powered by the Minimax algorithm. No frameworks, no dependencies — just 
HTML, CSS, and vanilla JavaScript.

## How it works

- You play as **X**, the bot plays as **O**
- After each of your moves, the bot uses **Minimax** — a classic 
  decision-making algorithm — to simulate every possible sequence of 
  remaining moves and pick the one that guarantees the best outcome for 
  itself (winning if possible, drawing if a win isn't available)
- Because Minimax explores the full game tree, the bot **never loses** — 
  the best you can do against it is force a draw
- Win lines are highlighted with a short pulse animation when a game ends

## Features

- Unbeatable bot opponent (full Minimax search, no randomness or 
  difficulty levels — it always plays optimally)
- Running score tracker (wins / losses / draws) that persists across 
  rounds until the page is refreshed
- Clean dark-themed UI with hover and click feedback on the board
- "New Game" button to reset the board without losing the score tally
