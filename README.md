# Blocker and Breaker Eng Design

*Design: N.A.*
*1-Pager: N.A.*
*Content: N.A.*
*Logging: TBD*

## Objective

Design and implement the game **Blocker & Breaker**.  We refer the game as **BnB** in this document.

## Gameplay

In a game, the player is represented with a pink heart 💖. In the beginning, a player is placed in a very dark area ▓. To win the game, they should find a path ➤, get out of this dark area 🌑, and see the light ☀️.

However, things are not so easy. In the pursuit of the light, there are different kinds of blockers underneath the darkness. A blocker can sabotage the movement of the player (💖); a blocker can make the pink circle become darker (⬜️). 

If the player encounter a lot of block, their pink circle may become darker and darker, and finally turns into a dark heart (🖤). When the heart becomes a COMPLETELY dark, the player get lost in the darkness, and the endless darkness is awaiting for them.

## How to Win?

- Be lucky. avoid blockers as possible
- Be bold. do not afraid of blockers
- Be happy. find hidden objects in the darkness, they will help you mitigate the damage caused by blockers and assist you win the game

## Technical Design

Will use `UIKit` and `SprikeKit` .	