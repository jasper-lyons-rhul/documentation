# Building a Game

**Aim**: To build and deploy a game and develop and understanding of the game development ecosystem.

**Background**:

Games development is one of the largest parts of the computing industry. There are many platforms for writing games and indeed, many architectures and frameworks.

In this project you will need to build and deploy a game.

In the first term you will research existing games and their underlying technology platforms. You will also look at game building tools such as Unity3D. You will consider game frameworks such as PyGame and also investigate APIs for game development such as Vulkan.

You will need to be familiar with the design patterns required for gaming: Flyweight, publish/suscribe (for message passing), Object Pool, Service, Dirty Flag, Factory, Visitor, Singleton, Game Loop, State, Observor, Command, Event Queue (See perhaps [Game Programming Patterns by Robert Nystrom](http://www.gameprogrammingpatterns.com/contents.html). Also consider reading some of the material on [The Game Designs Patterns Wiki](http://www.gameplaydesignpatterns.org/)

Your target could be a tower defence game written in Python in which case you will need to understand Threading and Graphics in Python.

Perhaps you will use Blender and other tools and do some maths and produce an excellent Unity game.

Maybe you will program a platformer game on an Android device, using the sensors and learning about the Android lifecycle, Manifesto, and the mobile approach to gaming.

## Early Deliverables

1. A simple program displaying an animation using sprites or similar animation technology.
2. A program displaying a simple, interactive user interface. You might want to explore the different means of displaying and writing user interfaces (XML, Object Orientated, Immediate Mode).
3. A program that exhibits some 3D graphics using a relatively low level graphics API (Vulkan, OpenGL, WebGL, JavaFX etc. This might provide a starting point for choosing technology: https://en.wikipedia.org/wiki/List_of_3D_graphics_libraries)
4. A simple game using a game engine / library / framework. Think of it as an opportunity to learn about the technologies you'll use for your main game but keep it simple.
5. A report on design patterns in games an enumeration of common ones, the problems they solve and perhaps discuss some specific instances of their use.
6. A report on the specific technologies you've tried / intend to use for your game. You should do deep on you intended tech, show as deep an understanding as you can.
7. A report on animation techniques, enumerate them, perhaps tell a history of them, compare and contrast. The goal is to show a deep understanding of how animation in games is achieved.
8. A report on Threading an User Interfaces. What problems do games experience with user interfaces without threading, how does multi threading solve these problems and what different ways can this parallelism or concurrency be achieved? Perhaps review how it has actually been achieve in technologies or platform relevant to your game.
9. A report on designing games with graphical user interfaces for multiple platforms.
10. A report on the technologies used to write and draw graphical user interfaces.

## Final Deliverables

1. The Game Source Code:
    * You should use a consistent architectural style. Our suggestion is object orientation but you could opt for another with sufficient justification.
    * The game needs to have at least 3 "screens" or pages that are interactive using the GUI technology of choice.
    * You should publish your game! (Android Store, itch.io)
    * The game play should make use of animation.
2. The Report:
    * An in depth review of background materials you used to learn the concepts and technologies used to write the game, perhaps presenting a historical timeline of those concepts / technologies.
    * A description of the more difficult concepts involved in writing graphical games e.g. Multi Threading and threads / processes, event based systems (handlers, events), special consideration for the environment your game with run in (memory foot print, battery usage).
    * A description of the software engineering processes involved in writing your game.
    * A description of interesting techniques, hacks or data structures you used (or could have used) in writing your game.

## Extensions
The goal here is to push the envelop of the project, expand the breadth of technologies and concepts you'd need to learn to complete the game. Examples might be:

* Using complex game AI, perhaps also using machine learning to improve the performance of that AI.
* Using peripheral devices for interaction with the game.
* Enabling multiplayer modes with networking, perhaps through scoreboards or other means.
