---
layout:     project
title:     Control mouse with Hands
date:       2014-11-28
code:
doc:
demo:     xPjvshQgju8
best:       true
image_small: /files/projects_files/2014-08-01-Control-mouse-with-hands.png
short: Controll the mouse curser by tracking the user's hand using a RGB camera

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
