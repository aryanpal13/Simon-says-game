# Simon Game

A web-based *Simon Says memory game* inspired by the classic 1978 electronic game. 
This project was built using *HTML, CSS, and JavaScript* and challenges the player's ability to remember sequences of lights and sounds that get longer with each level.

---

## Game Description

*Simon Says* is a pattern memory game. 
The system randomly lights up buttons in a certain sequence, and the user must reproduce that exact sequence by clicking the same buttons in the correct order.

Each successful round adds a new button to the sequence, increasing the difficulty as the game progresses. 
If the user clicks the wrong button, the game ends and resets.

---

## How to Play

1. *Start the Game*  
   - Press any key (on desktop) or tap the screen (on mobile) to begin.
   - A sound plays and a button lights up — remember it!

2. *Repeat the Sequence*  
   - Click the button(s) in the *same order* as shown.
   - Each correct round adds *one new step* to the sequence.

3. *Wrong Input = Game Over*  
   - A wrong move plays a "wrong" sound and shows a Game Over screen.
   - Press a key to restart.

---

## Features

- Fully responsive and interactive UI
- Random color sequence generation
- Sound effects for each button (Green, Red, Yellow, Blue)
- Game over restart mechanism
- Pure JavaScript with no external libraries

---

## Color to Key Mapping

Each color button is associated with a unique sound:

| Color  | Sound File       |
|--------|------------------|
| Green  | green.mp3        |
| Red    | red.mp3          |
| Yellow | yellow.mp3       |
| Blue   | blue.mp3         |
| Wrong  | wrong.mp3        |
