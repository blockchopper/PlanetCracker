# PlanetCracker
A quickly hacked-together adaptation of the watermelon game; developed in 6 hours and 48 minutes.

If you find any bugs, you may keep them.

Pre-Defined Requirements:

Program a Game akin to "Suika World".

Game:
The player must drop circles of ascending diameter (fruits) into the playing area, where identical fruits combine to form the next, one step larger, circle.
There are 11 circles. After two of the largest circles are combined, they form a permanent circle roughly the size of the smallest circle, which cannot be combined with other circles.
The playing area is an upright rectangular box.
One circle, randomly (equal distribution) selected of the smallest 5 sizes, spawns at the top of the box, where it hovers attached to the top border of the box. it can be moved horizontally by moving the mouse cursor horizontally. It must not move beyond the corners of the box.
A dashed line and a dashed circle are displayed as a visual indicator of where the circle will land upon release. The circle must be displayed on top of already dropped circles, keeping collisions in mind. The dashed line connects the hovering circle and the dashed indicator circle.
Upon clicking the left mouse button, the hovering circle drops from its position vertically into the playing area. The circles in the playing area interact with basic physics (gravity and collision, as well as some "bounce" depending on the size of the colliding circles). The circles collide with each other and with the playing field borders.
When two identical circles collide, they disappear and the next larger circle appears at the point of collision (in the "middle"). Upon collision, a "pop" or similar sound must be played.
Upon release of a fruit, the hovering circle is replaced with the next randomly selected circle

When a dropped fruit collides with the top border, the game is over. The game is frozen, the final score is displayed with a "game over" text, and a button appears to start a new game.

Next circle display:
There should be a visual element outside the playing area which display the next fruit spawned, after the current one. It is updated upon release of a circle 

Succession display:
There should be a visual element which shows the order of circles as a guide to the player.

Score:
The player scores points for combining circles. The larger the diameter of the combined fruits, the higher the received score. The score must be visible displayed to the player in a score box outside the playing area.
