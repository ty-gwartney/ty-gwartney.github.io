---
layout: essay
type: essay
published: true
title: The Singleton at the End of the World
date: 2018-11-29
labels:
 - Design Patterns
---
It's good to hear somebody else put words to thoughts you yourself have had, perhaps unconsciously, or to ideas you've formulated and put into action at some time in your life. Until now, I hadn't realized a program I wrote last year was actually designed in line with a classic software design pattern (the "Singleton" pattern), but learning this is reassuring. Maybe the way I wrote the program wasn't as thrown-together as I felt it was at the time... allow me to explain.

The program I'm referring to is a simple "zombie apocalypse" game that was intended as a learning experience. The game is only one level, featuring a single player character that runs away from attacking zombies. If the player is touched by a zombie, they die, and the game ends. Additionally, the player can pick up barbed-wire pieces and drop them to slow down the zombies, which happens on contact. That's it. That's the whole game. So how does this fit any kind of classic pattern, you may be asking?

As I mentioned, this game follows the Singleton design pattern very closely, maybe even completely. The Singleton pattern is one of many software design patterns programmers have noticed recurring across many applications, and described in a general way. The idea behind the Singleton pattern is that in some program or application, there is one particular object, and only one instance of it, to which many other objects in the program respond, or re-orient themselves according to the changes in this object. For my zombie game, this Singleton object is the player character. The motion of the oncoming zombies depends only on the coordinates of the player character, and as the player moves around the screen, the target of motion for each zombie changes accordingly. The barbed-wire objects work in a similar way: they are placed in the center of the player's position whenever dropped, and remain there.