# Agoda Maps Exploration and Redesign
My works and contributions in Agoda's mobile-application map redesign and exploration as a UX Prototyper Intern in collaboration with UX Designers, UX Researchers, and Product Owners during summer 2017.

Agoda's current state of map in mobile applications (Android and iOS) demands redesign, so I was tasked as the UX Prototyper for this project to aid UX Designers in the concepts exploration. These prototypes are built using Framer (CoffeeScript) with the integration of MapboxGl JS to best simulate maps in a prototype, alongside Sketch and Adobe Illustrator for visual assets.

This redesign exploration aims to improve the map's functionality and user-experience, so the icons and visuals are rough concepts and by no means finalized.

## Current Key Issues with Agoda's Mobile Application Map
1. Property pins show insufficient information; this forces the user to zoom-in or click on pins to reveal more information, most importantly, pricing.

Minimum zoom level pins &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Middle zoom level pins 

![img](http://i.imgur.com/UHR6lF0.png?1)  ![img](http://i.imgur.com/EHLtXm0.png?1)


Maximum zoom level pins (displays pricing)

![img](http://i.imgur.com/2ZqdOjl.png?1)



2. Upon selecting a property pin, property information card appears at selected location, covering up neigbouring properties thus preventing users from conveniently comparing nearby property prices.


Property information appears upon clicked

![img](http://i.imgur.com/B9Ue80n.png?1)

## Steps Taken to Address the Issues
1. Pin redesign: new pin is introduced to contain property price. However, larger pin means that pins would be cluttered and overlapping at lower zoom levels, so this was another problem to consider in the exploration.

2. Implementation of property cards: property cards appear upon selection at the bottom of the screen to not obstruct neighbouring properties.

With those fixes in mind and 10 explorations created, 2 concepts were proposed. 

## Concept 1
Concept 1 is the less farfetched exploration among the two because it maintains most of Agoda's current elements, but addresses the current map issues while also introducing new experimental features to enhance user-experience. The idea behind this concept is

The following prototypes shown below are recorded with Quicktime Player.

Addresses issues by...

Concept 1 pin clustering

![Output sample](https://github.com/csuksangium/maps/blob/master/ezgif.com-resize.gif)

[![Alt text](https://img.youtube.com/vi/KRKDliJczms/0.jpg)](https://www.youtube.com/watch?v=KRKDliJczms)
