# Forcefield
Creates a forcefield that protects you from enemies

[Forcefield](https://tshock.co/xf/index.php?resources/forcefield.71/)

Forcefield creates forcefields on users that protect them from enemies (by pushing or killing the enemies).

Command:
forcefield <type> [player name] [-p parameters]
if [player name] is given then a player whose name matches will be given the forcefield
if -p is specified, all arguments following it will be passed to the forcefield.
Eg /ff heal -p 100 1 will create a healing forcefield on yourself that heals 100 lifepoints every 1 second.
Likewise /ff heal example -p 100 4 will create a healing forcefield on player 'example' that heals 100 lifepoints every 4 seconds.

To remove a forcefield from yourself or someone else just use the command again.
Eg to remove from self: /ff heal
Eg to remove from example: /ff heal example
To remove all of your own forcefields: /ff

Buffing forcefields:
Buffing forcefields accept buff IDs as parameters.
/ff buff example -p 1 2 3 15 7
Will buff player example with buffs 1, 2, 3, 15, and 7

Valid types:
push
kill
heal
mana
buff
evil
blackhole 

forcefield.use
