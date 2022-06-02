## About V0.0.5: The spider update

This is the first update in which I add an additional monster to the game as I mentioned I'd do in the About for the first version. I originally thought that adding new
monsters would be slightly lower on my priority list but as I play the game almost every day to test new features I quickly realized that there was a fundamental problem
with the slime monster. The slime monster is only dangerous if it catches you by surprise. Once I started playing the game slower and being cautious about slimes being
around the corner, I knew I could theoretically keep playing the game infinitely. But if this is the only challenge the game would get boring very quickly! If you want
to reach level 50 all you had to do was to never take risks and move slowly throughout the maps. And this is why I designed the spider.

The spider, unlike the slime, is an eternal threat. When you lure a spider to water it won't die, it will only be slowed down and unable to kill you for a few seconds.
After that, you may run through the spider and escape but the second attribute of the spider is that it has a more advanced pathfinding than the slime. In the case of 
the slime, if it does not have a direct line of sight to you, it will start moving randomly. However the spider can track your precise location even if it does not have
a direct line of sight to you up to a certain distance limit. It can 'sense' you up to a certain distance. Once you go past this distance, the spider will start moving
randomly. But here is the new challenge: if for some reason you reach a dead end and need to backtrack, the moment you re-enter the spider's sense distance it will
immediately resume chasing you. Therefore now the player has an additional challenge of keeping detailed track of all of the water sources and also locations in the map
in which it can 'loop' the spider. Here by 'looping' I mean that you lure the spider into walking in a connected area so that you can walk in a 'loop' around it and 
escape even if there is no water around. This has brought many new challenges.

As of right now I believe that the optimal strategy when finding a spider is to first lure it into a water source. After the spider is slowed by the water, you must run
as fast as you can to get out of the spider's sense distance as fast as possible. Then as you keep exploring you must keep in mind the possibility that you are walking
into a dead end so you have to memorize places in which you can loop it or additional sources of water. If you need to backtrack, you better be prepared. And even if not,
the spider encounter still forced you to have to run through the maze at a faster speed than would be optimal when facing just a slime, which means that now if you are
unlucky you may get caught off-guard by a slime wandering around. Therefore now the optimal strategy is not to always be slow. You need to conciously think about your 
pace and go faster or slower depending on the circumstances. 

I decided that the spider with only appear on levels 10 and above. A player that is even able to reach level 10 should already be quite skillful at evading the slimes 
because from levels 1-9 you will have already faced at least 10 slimes but once a player is experience enough, they should be able to consitently reach level 10 in less
than 2 minutes which will also make the spider accessible without too much of a time investment. This monster also makes the game significantly harder to experienced
players able to reach this level will have to rethink their strategies if they even wish to go further. 

Right now I think that the game is at a point where I can take some time to focus primarily on polishing existing features and finding strategies to increase the
playerbase so that hopefully I can get additional feedback about the mechanics. However eventually I would like to add a third monster. Nothing is set in stone in my
mind regarding its future design other than I want it to be proyectile based and it should not appear until level 20. Also, I believe this should the final monster
released for this 'classic' version of the game. After that, my work will probably shift towards working on the RPG elements of the game which will most likely be a 
separate game mode. This 'classic' version of the game will always be available but there will be a separate game mode in which you can level up, modify your character,
learn skills, etc. But that will come further down the line. My immediate focus right now is to turn this game into something that people find on the google play store
and want to download and play. If I achieve this, I can then invest in growing the playerbase which would then mean the game would start generating a higher monthly
revenue. This is important because things like creating multiplayer servers or building an iPhone release will require capital and therefore would be easy if the game
was able to 'pay for itself' in a sense. It will probably take a while to get there but I'm sure it will be a fun journey. 
