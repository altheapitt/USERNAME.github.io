---
layout: project
type: project
image: images/olympicrunner.png
title: Olympic Runner
permalink: projects/olympicrunner
# All dates must be YYYY-MM-DD format!
date: 2016-09-25
labels:
  - Eclipse
  - Game
  - EZGraphics
  - ICS111
  - UHM
summary: My first project in ICS 111 at the University of Hawai'i at Mānoa was to program a game just like the popular game of 'QWOP.'
---

<div class="ui small rounded images">
  <img class="ui image" src="../images/sora.gif">
  <img class="ui image" src="../images/jake.gif">
  <img class="ui image" src="../images/naruto.gif">
</div>

"Olympic Runner" is a game I created in the ICS introduction class at the University of Hawai'i at Mānoa, this was the first project for the class. Our task was to create a game that took user input, by interchanging the keys 'a' and 's,' the user's character would go further down the track. The goal of the game was to beat the other characters to the finish line.

## Characters...

<img class="ui small leftright floated image" src="../images/sora.gif">

My personal favorite, Sora, from Square Enix's "Kingdom Hearts" video game series. Sora already has a set pace in "Olympic Runner."

<img class="ui small leftright floated image" src="../images/jake.gif">

From one of my favorite TV shows as a kid, Jake, from Cartoon Network's "Adventure Time," also has a set pace but, is slower than Sora.

<img class="ui small leftright floated image" src="../images/naruto.gif">

And finally, the user's player! Naruto, from Shonen Jump's... Naruto. Naruto's speed is the one character that is controlled by user input.

## A quick reflection...

Wow, what a blast from the past! It is nice to reflect on my past achievements and compare myself to how I was back then. I remember thinking this project was very hard for me and I spent hours in the ICSpace at my university asking for help. I'm sure my TA at the time was fed up with seeing me all the time!

```js
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```

You can learn more at the [UH Micromouse Website](http://www-ee.eng.hawaii.edu/~mmouse/about.html).



