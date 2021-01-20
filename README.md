# Overview

This repo contains code for an autonomous machine that can play the popular mobile game “Piano Tiles”. The game features black and white tiles which move down the screen at increasing velocities, and the player must successively tap each tile before it moves off-screen. This was achieved by utilizing a Raspberry Pi and camera module in conjunction with an Arduino Uno and four servo motors. While in-game, the camera takes in live video feed allowing the Raspberry Pi to analyze the screen with computer vision in real-time. After determining which motor needs to activate, the Raspberry Pi communicates with the Arduino through a Serial connection to activate specific motors, which in turn tap the screen at the correct time to obtain high scores in the game.

For a working video demo, click [here](https://youtu.be/ksWPjOEyEJY)
