# Santa's Helper
[Santa's Helper - The Game](https://cruzines.github.io/SantasHelper-Game/)
## Description
Santa's helper is a Game where the player has to help Santa fill his bag with presents. To do so, the player has to catch christmas presents that are falling from the top of the screen. The Game ends when the player catches an object that no child wants to receive.

## MVP
- Game has one Santa with his bag
- Objects fall randomly from the top of the screen
- Santa moves to the left and to the right, at the bottom
- The number of caught presents appear on the screen

## Backlog
- Add music
- Difficulty increases
- Level up

## Data structure

### index.html
<section id = "start-page">
<section id = "game">
<section id = "gameover-page">

### script.js
- Canvas
- DOM pages
- DOM buttons
- Images
- Variables
- handleStart () {}
- draw () {}
- animateSanta () {}
- inscreaseSpeed () {}
- restart () {}
- Event Listeners () {}

### style.css
- Start page:
    center
    startbutton
    instructions-box
- Game page
    myCanvas
- Game over page
    gameover-page h1
    gameover-page h3
    dw
    restartbutton

## States and States Trasitions

- StartScreen
- GameScreen
- GameOverScreen

## Task

- Main - buildDom
- Main - buildStartScreen
- Main - addEventListener
- Main - buildGameScreen
- Main - buildGameOverScreen
- Game - startLoop
- Game - buildCanvas
- Game - updateCanvas
- Game - drawCanvas
- Santa - draw
- Santa - move
- Objects - draw
- Objects - move
- Game - addobjects
- Game - checkCollision
- Game - GameOver
- Game - addEventListener

## Additional Links

### Git
[Repository](https://github.com/cruzines/SantasHelper-Game)

### Slides
[PresentationSlides](https://view.genial.ly/618276ef95ed480dbd10f84b/video-presentation-santas-helper)
