# Chati

This was a submission for a university project by me and 4 other students in 2021. 
The task was to develop a software to a given topic (2D interactive chat game) in one semester in a team of 5.
The project had to be done with the waterfall model, so that every student was responsible for
a particular phase. The resulting artifacts included specifications ("Lastenheft"),
architectural drafts including uml class- and sequence diagrams, the source code, documentation
and unit tests. Unfortunately, all other artifacts beside the source- and test codes got lost.

### Warning: 
The code is a catastrophe, full of singletons, global states, god classes and other anti-patterns.
It was the first project of that scale that we have done at that time, so we didn't know better.
Keeping that in mind, at least it works fine and is (mostly) bug free.

## What is Chati about?

As already mentioned, Chati is a game-like 2D interactive chat application.
There is a server and a client part of the application. The server contains the business logic and the database,
the client contains a minimal model and the ui. Users can create accounts, login, create or join a "world"
and then interact with other users. Like in other 2D games, users can move around using the keyboard.
If they come close enough to other users, they can chat with them through text or voice chat (and very bad video).
There are many other features, including a friend list, roles & permissions to mute/ban users and more,
notifications, private password protected rooms, a juke box, and a chat bot with a voice synthesizer.
The following screenshots show how the application looks like:

![Screenshot1](https://github.com/Arti1994/Chati/blob/master/doc/Screenshot1.png)

![Screenshot2](https://github.com/Arti1994/Chati/blob/master/doc/Screenshot2.png)

![Screenshot3](https://github.com/Arti1994/Chati/blob/master/doc/Screenshot3.png)

![Screenshot4](https://github.com/Arti1994/Chati/blob/master/doc/Screenshot4.png)

![Screenshot5](https://github.com/Arti1994/Chati/blob/master/doc/Screenshot5.png)

## Can I use Chati?

Unfortunately, as the source of some resources is uncertain (and so the rights to publish), I had to delete some files. The state of the Client 
in this repo is hence unusable. However, the server side application can still be started.

## Credits

Following libraries were used to build Chati:
* Front End / Gui: [LibGDX](https://github.com/libgdx/libgdx)
* Network & Serialization: [Kryonet](https://github.com/EsotericSoftware/kryonet)
* Database: [Apache Derby](https://github.com/apache/derby)
* Webcam Access: [Sarxos](https://github.com/sarxos/webcam-capture)
* Text-To-Speech Synthesizing: [MaryTTS](https://github.com/marytts/marytts)
* Miscellaneous: [Google Guava](https://github.com/google/guava)
* Tests: [JUnit 4](https://github.com/junit-team/junit4)
* Mocks: [Mockito](https://github.com/mockito/mockito)

Following resources were used to build Chati:
* Skin: [ShadeUI](https://ray3k.wordpress.com/artwork/shade-ui-skin-for-libgdx/)
* Emojis: [OpenMoji](https://openmoji.org/)
* Music: [Bensound](https://www.bensound.com/royalty-free-music)

All of the icons used in the application are self made!

The resources for maps and avatars were provided by one student in the group who does not remember were he got it from. So it is uncertain if we are
allowed to publish the application with all resources available. Thus, those resources were removed from this repo to avoid any legal issues.
