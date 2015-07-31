---
layout:     project
title:     Control mouse with Hands 
date:       Fall 2014
code:  
doc:        
demo:
best:       true
---
The hand tracking is based on color recognition.  For achieving this I do: <br />
1) Sampling color from the hand. <br />
2) Each color in the profile produces a binary image which in turn are all summed together.<br />
3) Produce binary image for each color.<br />
4) Smooth them.<br />
5) Get convex points.<br />
6) Get the points furthest away.<br />
7) Find the angle of furthest points.<br /><br />

Then, I found the hand in picture and track it to move the mouse by hand movement, and I visualized mouse click when the person opens his fingers. 