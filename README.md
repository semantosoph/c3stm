# c3stm – CCC Stage Manager Tool

This is an Android App that may be useful when doing timekeeping for speakers or other stage managing duties like managing large crowds with several helpers. I wrote this based on my experiences as a stage manager on several Chaos Communication Congresses.

This is an MIT App Inventor 2 project. You may develop further features only with this tool.

## Introduction

The App is only useful on large tablets with a screen size of 9" or 10". You may still find it useful for personal timekeeping but small displays are just not readable from the stage.

## The main screen

The left column (only visible on screens >= 1280px) works as info center with links to some important pages. 

The right column consists of several forms:
* Overall length of talk. Use the start Button to start the countdown. This will lock the talk length.
* 4 points of warning where you will be alerted visually that you should show the remaining time to the speaker in the next minute. These may be changed during the countdown.
* Q&A toggle and time.
* The remaining time. If Q&A is checked, this counts down to (talk length - Q&A time). Use the show Button to display the current minute in the message screen.
* A message field. The message may have multiple lines. Use the show Button to display the message in the message screen.
* Flash colors: Tap on a color Button to display a flashing display. Use your devices back key to close the flashing screen.

## The message screen

The message screen alsways opens with font size set to maximum. That may result in an invisible message. The slider at the bottom of the screen can be used to adjust the font size so that the message is fully visible and readable. Use your devices back key to close the message screen.
