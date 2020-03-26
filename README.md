# Snake
Building Snake from scratch in Advanced Software Development.  <a href="https://benspector3.github.io/projects/snake/index.html" target="_blank"> Play the demo! </a>

<img height=400 src="img/snake.gif">

**Table of Contents**
- [Setup](#setup)
- [Learning Objectives](#learning-objectives)
- [Worksheet](#worksheet)
- [Plan of Attack](#plan-of-attack)

# Setup

To install this project, first clone the [template](https://github.com/benspector3/asd-template/) repository by entering these commands into your bash terminal:

```bash
git clone https://github.com/benspector3/asd-template.git
rm -rf asd-template/.git
```

Then, rename the folder to `snake`

# Skills Practiced (Bonus points for adhering to best practices)
- Separation of Concerns and Abstraction
- Keeping code organized between `initialization`, `core logic`, `helper functions` and `event handler` sections
- Controlling DOM elements with jQuery
- Managing data for DOM elements with Objects and Factory Function
- Managing a collection of Objects with an Array
- Iteration
- Initializing new DOM elements with jQuery

# Worksheet

Before beginning, complete the <a href="https://drive.google.com/open?id=1h9DBLktvwVCODaAn4vg5FKnbkbyYjLIMik5IMYMbhY0" target="_blank"> Snake Worksheet </a>

<img src="img/snake-visualization.jpg">

# Plan of Attack
1. Get the Snake's head to appear on the screen
2. Move the snake continously. Limit movement to one axis at a time (horizontal/vertical movement, never diagonal)
3. Change direction according to keyboard inputs from the user.
4. Detect collisions between the snake's head and the wall
5. Get the Apple to appear on the screen
6. Position the apple randomly
7. Detect collision between the apple and the snake's head
8. Reposition the apple upon colliding with the snake.
9. Add a new snake piece upon colliding with the apple.
10. Make the new snake pieces follow the snake's head
11. Detect collision between the snake's head and the rest of its body
12. Keep track of and display the score

