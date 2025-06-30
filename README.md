core-aesthetic
==============

2-player group battle game

Core-aesthetic is a deck battler where your deck is made up of elements that can build finite groups.  Battling happens in rounds where each round has two phases: defense and attack.  During the defense phase, you build your defense groups, and during attach phase, you build your attack groups and order them to hit your opponent's defense groups.  Both sides attack simulataneously, and you win by completely destroying your opponent's defense.

Defending groups start with HP equal to their order.  When groups are attacked, they lose HP, and can only regain it through rest where they're removed from a round of battle.

There are three types of attack:

1. attack by a normal subgroup divides the defending group
2. attack by a non-normal subgroup of order N removes N HP from the defending group
3. attack by a non-subgroup of order N removes N HP from the defending group, but the attacking group is destroyed

How to Run
----------

Core-aesthetic runs in web browsers and needs to be hosted by a webserver.  To host it, start up a webserver that gives access to the index.html file within the core-aesthetic top-level directory.  For example, if you have python (>=3) installed, navigate to the core-aesthetic directory and run

```
> python -m http.server 8000
```

This will start a server exposing that directory on port 8000.  You can then access the program by pointing your web browser to the URL `http://localhost:8000`.


Dependencies
------------

Dependencies are included.

* phaser
