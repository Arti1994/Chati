# Chati

This was a submission for a university project by me and 4 other students in 2021. 
The task was to develop a software to a given topic (2D interactive chat game) in a team of 5.
The project had to be done with the waterfall model, so that every student was responsible for
a particular phase. The resulting artifacts included specifications ("Lastenheft"),
architectural drafts including uml class- and sequence diagrams, the source code, documentation
and unit tests. Unfortunately, all other artifacts beside the source- and test codes got lost.

### Warning: 
The code is a catastrophe, full of singletons, global states, god classes and other anti-patterns.
It was the first projects of that scale that we have done at that time, so we didn't know better.
Keeping that in mind, at least it works fine and is (mostly) bug free.

## What is Chati about?

As already mentioned, Chati is a game-like 2D interactive chat application.
There is a server and a client part of the application. The server contains the business logic and the database,
the client contains a minimal model and the ui. Users can create accounts, login, create or join a "world"
and then interact with other users. Like in other 2D games, users can move around using the keyboard.
If they come close enough to other users, they can chat with them through text or voice chat.
