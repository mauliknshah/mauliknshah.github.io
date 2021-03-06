---
title: Warlight AI agent
layout: post
icon: fa-lightbulb
icon-style: regular
---
#### A warlight AI game-playing agent
#### Area: Decision Planning; Technologies: Java.
#### Links: [Github Repo](https://github.com/mauliknshah/WarlightAI)

Warlight is a special constrained game that is like playing Risk in real-time, in which a player needs to destroy all the armies of the other player in a maximum of 100 rounds, otherwise, the game would be termed as a draw. For more instructions : [Warlight AI Challange Rules](http://theaigames.com/competitions/warlight-ai-challenge/rules)

The architecture was designed based on the POMDP framework, a realtime value iteration, and Bayesian Games to generate an agent that can win a game. The agent performed sensibly initially, but due to 2-second response time, the agent couldn't catch up planning at that time. The final presentation PDF gives a brief about the overall methodology: [Final Presentation](https://github.com/mauliknshah/WarlightAI/tree/master/ReadMe/FinalPresentation.pdf)
