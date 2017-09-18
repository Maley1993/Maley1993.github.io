---
layout: post
title: BlocJams
thumbnail-path: "img/blocjams.png"
short-description: BlocJams is a Spotify replica for finding new songs and listening to your favorites.

---


{:.center}
![]({{ site.baseurl }}/img/blocjams.png)

## Explanation

The purpose of this project was to implement vanilla JavaScript to create a functioning replica of Spotify. After completing the app using vanilla JavaScript I refactored the code to utilize jQuery. This helped me understand the pros and cons of using plain JS versus jQuery.

## Problem

One problem that I had to solve for this application was making the player bar allow the user to play and pause a song. It had the ability to play the previous song or move to the next but it still didn't have the ability to start or stop a song.

## Solution

To give the player bar the functionality to play and pause a song I created the function togglePlayFromPlayerBar(). I then created a variable to hold the Play/Pause button in the player bar and added a 'click' event handler to it. The function checks to see if a song is currently playing or not. Based on that it then adjusts the icon to either Play or Pause and changes the state of the sound file. It also adjusts the play/pause button on the number cell.

## Results

After implementing this new function it flowed smoothly. One thing that was missing was the ability to start a song from the player bar if one had not yet been played. That will need to be added at a future time so that upon load, if the play button is hit on the player bar it will play the first song on the displayed album.


## Conclusion

Overall this project was great at getting my feet wet with using vanilla JavaScript to manipulate the DOM. It also showed me how to refactor plain JS into jQuery and save time from having to right out the long version of getting elements.
