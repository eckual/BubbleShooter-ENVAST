Welcome to the Bubble Shooter game, a Unity project that offers a unique and challenging experience for both players and developers alike.

Why & How?
Unlike other bubble shooter games that rely solely on color, the explosions of bubbles in this game are triggered by another mechanic.
Each bubble is assigned a specific score, and bubbles with the same so merge together through multiplication. This process continues until the score reaches 2048, at which point the bubble and its neighbors finally bump up.
This feature sets this game apart from others and provides players with an engaging gameplay experience.

The project incorporates various external assets, including packages and elements from other projects. These external elements include visual effects, animations, coding approaches.

In this Bubble Shooter game, there are several main elements that needed to be implemented: the session controller, bubbles controller, input controller (player controller), VFX controller and the canvas. The session manager is responsible for managing the state of the game, including tracking the score and level progression ( did it by setting  levels settings  and when the  user  reaches the  level's score he goes to the reached level). The bubbles manager is responsible for generating the bubbles and handling their movement and collision detection (i needed a pooling here to instantite bubbles and bubbles manager to set every bubble by its  type and the  manager is also responsible for the merging process). The input manager handles user input, such as aiming and firing the bubbles (i've  done many searches and opened inspiring projects in order to have done an input system works good  in all platforms), while the canvas is the graphical interface that displays the game main elements  and handles rendering. Finally the vfx  controller which  is the  manager of VFX elements and it adds visual effects to enhance the overall gameplay experience  ( i've done it  using a pool system  also to generete effects and vfx controller to manager explosions and releases of the effects elements.  

While working on  this project, I encountered difficulties with the bubbles merge process and shooter movement mechanic across all input types. This required me to inspire from other projects as well as rewriting the code to address these issues. I was working by another canvas render  mode until  i realized i should  to use camera space rendering and sprite render components as they were new concepts to me so i tried hard to understand  how they should work and it was a really good challenge to me becayse  i start working on this project  by  another concept which  may not be good to start with.  Finally, the experience working on  this project  was literally great as it allows me to search and learn new  things in a short period of time. 
