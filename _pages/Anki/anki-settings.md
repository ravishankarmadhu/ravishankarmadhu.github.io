---
permalink: /docs/anki-settings/
title: Anki Settings
sidebar:
  nav: docs
toc: true
toc_label: "Anki Settings"
toc_sticky: true
---
# Introduction

This guide is meant to help people get the most out of their Anki Experience. For me, it has been my number one tool to help me memorize a vast amount of information. However, I recognize it is not a user friendly piece of software. Hopefully, this guide will allow you to get the most out of this wonderful tool. 

I do want to point out, that even though I am a huge advocate for Anki - It is not for everyone. If you tried it before, and it does not work for you, I am not here to change your mind. 

Special thanks to Duncan Crow and Rylee Amos for helping me test and understand this software better. 
## What is the goal?
My goal for Anki is to have the necessary information I need before STEP 1. That is a lot of information that we will need to know in 1.5 years, and the best way that I have found is to use the AnKing Deck (29,000 cards), un-suspend the cards when we encounter them in lecture, and keep doing the reviews after we leave that block. 

This is why I always recommend to people to keep doing their anki even after we have left that week / block. I know it is a lot, but in the long run, I think we will see a lot of dividends. The information I present in this guide serves to further this goal of long term information retention. 

# How to use FSRS (the new Anki Algorithm)
## Update your Anki
This new algorithm is only available for the latest version of anki. Unfortunately, unlike other apps, Anki does not update itself - so you will have to do it manually. 

1. In Anki, got to the very top bar and select __Anki__ --> __About Anki__. 
<!-- ![[AboutAnki.png|600]]
![[VersionNumber.png|600]] -->
![](https://github.com/ravishankarmadhu/ravishankarmadhu.github.io/blob/master/_Media/Anki/AboutAnki.png?raw=true)
![](https://github.com/ravishankarmadhu/ravishankarmadhu.github.io/blob/master/_Media/Anki/VersionNumber.png?raw=true)

2. Check to make sure if it is at least Version __23.12.1__
3. If it is not, got to https://apps.ankiweb.net/, download the latest version of Anki for apple Silicon. 
<!-- ![[LatestVersion.png|600]] -->
![](https://github.com/ravishankarmadhu/ravishankarmadhu.github.io/blob/master/_Media/Anki/LatestVersion.png?raw=true)

5. Double click the file you just downloaded and drag the Anki icon into the applications folder. 
<!-- ![[DragIcon.png||600]] -->
![](https://github.com/ravishankarmadhu/ravishankarmadhu.github.io/blob/master/_Media/Anki/DragIcon.png?raw=true)
6. A pop-up will appear. Select Replace. __THIS WILL NOT RESET YOUR CARDS__

<!-- ![[SelectReplace.png]] -->
![](https://github.com/ravishankarmadhu/ravishankarmadhu.github.io/blob/master/_Media/Anki/SelectReplace.png?raw=true)

Now your version is up to date. 

## Intro to FSRS
FSRS is described as a newer spaced repetition algorithm meant to improve long term retention. I am not going to bore you with the technical details, but it claims to do the following:
- Individualizes the rate at which you see cards. Cards you always get right should be seen not as often. A card you always get wrong, will have a slower progression
- Give you less review cards per day to do 

Watch this video from the AnKing if you are curious. 
<iframe width="560" height="315" src="https://www.youtube.com/embed/OqRLqVRyIzc?si=WlFcVhuy4FniydUw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## How to Activate FSRS on your device
1. On your deck tab on Anki, click the gear wheel next to one of you decks. 
<!-- ![[GearWheelSettings.png|600]] -->
![](https://github.com/ravishankarmadhu/ravishankarmadhu.github.io/blob/master/_Media/Anki/GearWheelSettings.png?raw=true)
2. Scroll to the bottom untill you reach the __Advanced Tab__ and turn on FSRS
<!-- ![[TurningOnFSRS.png|600]] -->
![](https://github.com/ravishankarmadhu/ravishankarmadhu.github.io/blob/master/_Media/Anki/TurningOnFSRS.png?raw=true)
3. Once you do that, more FSRS settings will appear. Set your desired retention to 0.9. (This means that 90% of the time, you will get a mature card right). If you want a higher long term retention I would not recommend raising it above 0.95. You can also lower the retention. This will give you less cards per day, but the trade off is you are more likely to get the card wrong. If you are going to lower the retention, I would not drop it below 0.80. 
<!-- ![[Other FSRS Settings.png|600]] -->
![](https://github.com/ravishankarmadhu/ravishankarmadhu.github.io/blob/master/_Media/Anki/Other%20FSRS%20Settings.png?raw=true)
4. Select the Reschedule cards on change button.
5. Press the optimize button. 
6. Change your learning interval so that only has one learning stage that ranges from 15-30 minutes. 
<!-- ![[OneLearningStep.png|600]] -->
![](https://github.com/ravishankarmadhu/ravishankarmadhu.github.io/blob/master/_Media/Anki/OneLearningStep.png?raw=true)

## Ok, whats next?
Now just go about doing your reviews like normal. The biggest change that will occur is that the length of time that you will see a card after you press okay (Spacebar) will be dependent on your prior preformace. For instance, a brand new card could show up 6 days from know or 2 days from know depedning on how your reviews have gone recently. In theory, this should reduce the number of cards you need to do each day. 

However, about every month, you will need to "re-optimize" your settings. This can be done by opening up the settings and pressing the optimize button. Once you have done that, it will take a look at your past performance for the month, and edit the scheduling of cards to match up with your desired retention rate. 

# Can I just see what your settings are?
## Old Anki Algorithm Settings
<!-- ![[OldAnkiSettings.png]] -->
![](https://github.com/ravishankarmadhu/ravishankarmadhu.github.io/blob/master/_Media/Anki/OldAnkiSettings.png?raw=true)
## New Anki Settings
<!-- ![[NewAnkiSettings.png]] -->
![](https://github.com/ravishankarmadhu/ravishankarmadhu.github.io/blob/master/_Media/Anki/NewAnkiSettings.png?raw=true)