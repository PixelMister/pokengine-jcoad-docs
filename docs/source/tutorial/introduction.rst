.. _introduction:

Introduction
############

What is Pokengine?
====================
Pokéngine is a browser-based, free-to-play monster-collecting MMORPG and game creation engine. It consists of many Regions created by members of our community. Whether you want to explore the many Regions or create your own for others to play, Pokéngine is an experience unlike anything else! Behind the scenes, Pokengine is a community focused on the creation of custom content, such as Regions and Dexes.

Whilst an MMO, it is an engine by nature, not an actual game. The game part is created by its users, meaning instead of Pokengine being just one game, it's several rolled into one.

The engine offers a collection of online browser-based tools, made for the sole purpose of editing and building the game. This includes;

:Mapbuilder:
    Pokengine's software to program and implement Tilefuser maps into the game engine.
:Tilefuser:
    Pokengine's software to create and manipulate tilemaps.
:Trainerer:
    Pokengine's software to test both trainer and mon overworld sprites.
:Animator:
    Pokengine's software to test and tweak animation strips.
:Transparency:
    Pokengine's software to add transparency based on a chosen colour.

What is Mapbuilder?
===================
**Mapbuilder** is Pokengine's software to program and implement Tilefuser maps into the game engine. Only users granted access to the Mapbuilder may use it to put their maps into the game.

Only users developing a region or who are part of the wider development team are granted access to this tool. Not all users may use this tool because it allows players a high degree of control over the game engine.

Mapbuilder works by using your Tilefuser map as a foundation. The Mapbuilder can add objects, NPCs, sprites, animations, or anything your map needs to make it come alive in the game. All map objects are implemented using Pokengine's custom programming language, jCoad, which is the focus of this guide.

Before jumping into the programming, here are a few Mapbuilder tips to get you started with the tool.

Rules of Mapbuilder
-------------------

#. Only use on Mapbuilder Tab at one time.

    - Multiple tabs may corrupt where your objects are saved.

#. When in doubt, compile your Mapbuilder Map.

    - To compile, press the "save" button in the "Settings" tab.

#. When your rage, refresh the page.

    - MapBuilder has an autosave function, however, sometimes an object may not save properly. If you find something on your map that is not working, refresh the page. You could possibly find a previously invisible object wreaking havoc on your map due to its appearance in the wrong location.

#. If you want to share, put it in there.

    - Mapbuilder maps are exclusive to you unless you specify its region in the "Settings" tab. Then, all regions helpers will be able to view and edit your map as well.
    - Ensure that only one person is editing the map at any one time, as you can overwrite work from others if working on the same map simultaneously.

#. Be careful!

    - You, and only you, are responsible for the programming of your region. Be cautious when working with event variables and spawning items and |Pokemon|.
    - In other words, don't spawn level 100 legendaries and Master Balls for everyone!
