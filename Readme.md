# Snake game using OPENCV Python
In this project I am going to learn how to use Gesture Control to create Snake Game. 
I first look into hand tracking and then I will use the hand landmarks to find gesture of my hand to move the Snake.

## How to install
1. Clone this repository on your computer
`https://github.com/paveldat/snake_game.git`
2. Install all the requirements
`run libraries.bat`
3. Run the program
`python main.py`

## Help
You might face issue with webcam not showing and you get errors.
To solve it just change the value in this line (for example to `1`).
`cap = cv2.VideoCapture(0)`
Increment this number until you see your webcam.

## Goal
Move your index finger across the screen, guiding the snake with your finger.
Donuts appear in random places, which you need to collect to increase the length of the snake's body, as well as increase your score.
If you lose, press the "r" on your keyboard and start moving the snake further. Thus, the game will start over.

## Snake structure

<img src="https://github.com/paveldat/snake_game/blob/main/img/snake.png">

## Enlargement of the snake's body

<img src="https://github.com/paveldat/snake_game/blob/main/img/new_length.png">

## Length reduction

<img src="https://github.com/paveldat/snake_game/blob/main/img/length_reduction.png">

## Check for collision

<img src="https://github.com/paveldat/snake_game/blob/main/img/collision.png">

Compute distance between head and each point.
If any low below a threshold collision detected, then Game Over.

## Result
![Alt Text](https://github.com/paveldat/snake_game/blob/main/img/result.gif)
