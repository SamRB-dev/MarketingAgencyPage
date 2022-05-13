A fully customized single page website with simple mobile UI for representing a marketing agency, ALLIES for brand awareness.

# Overview:
This project is me trying to solve some design issues in the existing website which I encountered
during my investigation of the page UI elements. It's not 100% perfect but I tried my best to solve
some issues as I could as a beginner while learning the full capacity of Github, git & netlify :D

# Build with:
* HTML
* CSS [Flexbox, media queries]

# UI Design Inspiration: 
### Source:  https://www.awwwards.com/sites/allies-marketing
### Site: https://allies.marketing/

# Analysis of The Demo:
## Insight: 
In this demo, the developer used many cool animation and effects which are purely made with Js.
The backgrounds are made with animated SVG which moves when the page is being scrolled. 
Navs are beautifully made with hover transition effects and the fonts are made with 3D animations. 
Most of the animations are being rendered in real time which can be noticed in CPU performance monitor 
while being in the page. Even when selecting elements like texts or emails, RGB blink animation is 
done which can be seen after selecting elements.

## Drawbacks: 
Although the demo contains beautiful effects on various elements, there are some issues in the demo regarding the responsiveness and functionalities. For instance,
#### Issue[1]: 
The SVG animated backgrounds used in the demo doesn't always fully load
on mobile devices [even with good internet connections] which creates a lot 
of blank spaces on the page. 
#### Issue[2]: 
The second small navigation menu after the gaming championship images 
doesn't work properly on mobile devices [at least didn't work on my end tbh].
 
# My UI:
## What I tried: 
### **[Desktop]**:
* [1]: Took Desktop First approach. The main UI was actually focussed on Desktop environments.
* [2]: Implemented Card layouts one secondary menus with hover effects and transitions.
* [3]: Stripped secondary svg backgrounds for fast loading.
* [4]: CPU friendly animations with keyframes **[Includes mobile support].**

### **[Mobile]**:
* [1]: Implemented media queries for responsive mobile UI for screen width of 360px minimum.
* [2]: All card layouts customized for mobile UI.
* [3]: Column based Card layouts.

### Drawbacks:
* [1]: 
        Since I still don't know Js that well, I tried to implement everything with pure css :').

* [2]:
        Since This is my first time using media queries, there might be some design flaws on mobile
        devices with wider screen resolutions. For Instance,
        [I]: background-image placement.
        [II]: Stretched Images.
* [3]:
        No Tablet or iPad UI support.
        
* [4]:
        Unimplemented custom mobile UI for landscape orientation.

**[ This note was written during the development process ]**


# Project in Action:
### Link: **https://alliesmarketing.netlify.app/**