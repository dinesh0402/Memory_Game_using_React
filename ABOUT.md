# Memory Game 🧠
## A basic image matching game build using React.js

In this memory game, you will be basically given a 3 x 4 grid having 12 cards. You have to match 2 cards having the same image until all cards are turned up.

### How it works :-
* 👉 The cards are shuffled using useEffect hook of React. Whenever, the game is over or the 'new game' button is pressed, it fires up and shuffles the cards.
* 👉 We maintain 2 useState hooks to check the state of the 2 slected cards.
* 👉 If the selected cards are same, the cards remain turned up and disabled.
* 👉 Else, they turn back and hide themselves for the next turn.

### Technologies used :-
* React.js
