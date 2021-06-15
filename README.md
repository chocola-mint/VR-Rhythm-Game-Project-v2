# Orbitone
### A Cytus-inspired take on the Virtual Reality Rhythm Game Genre.

##### Final Project for the course Virtual Reality (2021 Spring)
---
**(June Demo Build)**

## Table of Contents
1. [Controls](#controls)
2. [Technical Details](#technical-details)
    1. [Beatmap Helper](#beatmap-helper)
3. [External Packages Used](#external-packages-used)
---
## Controls

*Orbitone* is developed around the Oculus Quest 2 device, which uses the Oculus Touch controllers, and so we will only provide controls for said device here. Though, theoretically, the analogous buttons on other VR devices should be able to invoke the respective functionalities as well.

The trigger buttons (L1/R1) are used to click ingame UI after selecting them by touching them ingame.

The grip buttons (L2/R2) can be held to rotate the ingame UI horizontally by moving the controllers around. This will only work if only one controller has its grip button held, and the rotation will follow that controller.

The gameplay simply involves driving your controllers towards the notes that appear on the orbits. You have to hit them from the side facing you.

---
## How To Play
You will first be greeted by the main menu, which contains the **Track Select** button and the **Settings** button. Move one hand to the Track Select button and press the trigger button, and you will be brought to the track select screen. Currently, only one song is available for you to play, *Enemy Approaching* from the game *Undertale*, composed by *Toby Fox*. Move your hand to the button that has the name of the song written over it and click it to start playing. Notice that when you hover your hand over the button, you can see the Local Record, which should be 000000 if this is your first time playing.

Your objective is simple. By hitting the diamond-shaped notes that appear as the song progresses to the rhythm of the song, your score will grow more and more. Not missing a note will let you build up a combo, which increases your score. The closer you are to hitting a note as it is at its biggest, the better your score will be, graded by "Perfect", "Good", and "Bad". The UI present during this section will tell you your current performance, with the number of notes you've landed a "Perfect", "Good", "Bad" on, the number of notes you've missed, and the number of combos currently accumulated.

At the end of the song (which should last only a minute), you will be brought to the results screen, at which you can view your performance throughout the song and your score, which will be recorded locally. If this score is better than the best local record stored, you will find that your score now appears in the track select screen.


---
## Technical Details
### Beatmap Helper

The Beatmap Helper is a beatmapping tool that lets the user approximate "notes" of a given song and generate a list of timestamps to be transformed into a beatmap. In the Unity Editor, you can open it in your web browser by going to **Window -> Beatmap Helper**.
###### We ultimately ended up using the open source software, Audacity, to complete the design flow instead, but the Beatmap Helper is left here for historical purposes.

---
## External Packages Used
Note that a lot of packages included in the project folder went unused. (such as FMOD, Probuilder, and an Audio Sequencer plugin) Due to time constraints, we don't have the time to strip them.

* Tween for Unity
(c) 2016 Digital Ruby, LLC
https://www.digitalruby.com/unity-plugins/
Created by Jeff Johnson

