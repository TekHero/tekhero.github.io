---
title: Swifty Arrows
date: 2016-03-12 04:26:35 +0300
subtitle: Game
image: '/images/App-Icons/SwiftyArrows-App-Icon.png'
---

Swifty Arrows was a game that I made entirely in Swift with no use of any game development framework such as SpriteKit. In Hindsight, it probably would've been beneficial to have done that. This game was also one of my highly rated games during the time of it's release. The premise of the game was to utilize the swipe gestures available, such that the game would randomly decide which is the correct way to swipe and you'd have to copy it exactly within a predefined amount of time. So if the app showed a right arrow, you'd have to swipe right but if you didn't...it's gameover.

The game was very fast paced and quite addicting to play but the unfortunate part to this game was the development aspect of it. At the time of building the app, I was still early in my knowledge of how Timers worked, so if you'd imagine everytime you restarted the game, a new timer would be created but unknowingly there was a memory leak in part of that since the Timer would be recreated over and over again and never handled properly. This was before I've come to understand how memory leaks worked or potential causes, so for awhile of it's usage, the app would just crash after a few mins of playing the game and I never really solved it.

Maybe one day I'll recreate this one as well.