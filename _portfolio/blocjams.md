---
layout: post
title: Bloc Jams
thumbnail-path: "img/blocjams.png"
short-description: Bloc Jams is a dynamic music app for web and mobile devices.

---

{:.center}
![]({{ site.baseurl }}/img/blocjams.png)

## Explanation

Bloc Jams is a dynamic web and mobile music player. The project consists of a landing page, a collection page, and an album page. On the landing page, we use animation to highlight the selling points of the website. On the collection page, the user may select an album to listen to. Finally, on the album page, users may play music from an album of their choice. 

## Problem

The most challenging part of the application was building dynamic and intuitive behavior for the music player, making sure the appropriate play or pause button element appears when it is hovered over or clicked, and what must happen to the interface when playing and pausing the music. It is a goal of this project to communicate these states to the user visually, so that they may play and pause the music as they please, in an easy interaction with a friendly user interface. 

## Solution

I used JavaScript and jQuery to implement the functionality. I used a clickHandler function to deal with what happens when you click anywhere along the song row, and the proper pause and play behavior. I also used an onHover and an offHover function to specify what the behavior should be when you hover over the row and hover away from the row, and what the state of the buttons should be depending upon whether or not a song is playing. 

Using clickHandler, onHover and offHover functions, I implemented the following: when clicking a song to play it, the song number should change to a pause button. When the mouse leaves the table row of the currently playing song, the pause button should remain. When we switch songs, the previously playing song's table cell should revert the content back to the song number. When we hover over each of the songs that aren't playing, the play button should still appear; we don't show the play button when we hover over the playing song.

In the clickHandler function, I wrote code for reverting the song number for currently playing song because the user played a new song. Other cases included switching from a play to pause button to indicate a new song is playing, and also switching from a pause to play button when the current song is paused, with the concurrent functionality of playing or pausing the song, depending upon the circumstance. 

## Results

The results of this code mean the user is able to click and hover, and see the correct buttons, in addition to the correct song-playing behavior. 

Otherwise, on the home page, we animated the selling points so that they appear when the user scrolls down the page a certain length. The animation triggers when the user scrolls 200px into the selling points area. Otherwise, if their screen is already large enough, we animate the points automatically. 

## Conclusion

I spent this project coding with JavaScript and jQuery, as well as implementing complicated music player behavior that affords the user an intuitive and delightful experience. I also made this website mobile-friendly by using media queries, so the user can play their songs even on a smaller device, like a phone or tablet. I implemented and learned a lot during this project, and feel well-equipped to tackle music applications in the future. 