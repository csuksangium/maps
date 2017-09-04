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



2. Upon selecting a property pin, property information card appears at selected location, covering up neighbouring properties thus preventing users from conveniently comparing nearby property prices.


Property information appears upon clicked

![img](http://i.imgur.com/B9Ue80n.png?1)

## Steps Taken to Address the Issues
1. Pin redesign: new pin is introduced to contain property price. However, larger pin means that pins would be cluttered and overlapping at lower zoom levels, so this was another problem to consider in the exploration.

2. Implementation of property cards: property cards appear upon selection at the bottom of the screen to not obstruct neighbouring properties.

With those fixes in mind and 10 explorations created, 2 concepts were proposed. 

## Concept 1
Concept 1 is the less farfetched exploration among the two because it maintains most of Agoda's current elements, but addresses the current map issues while also introducing new experimental features to enhance user-experience. The major features and changes introduced to Concept 1 include:
1. Pin redesign to display the prices of the property
2. Clustering/grouping of pins to minimize overlapping due to larger pins introduced
3. Commonly used filters on map for users to display attractions/key locations on map
4. Redesigned swipable property cards that anchor at the bottom to not obstruct properties upon selection
5. Area/district selection at the minimum zoom level
6. Floating filter button


Concept 1 pin clustering &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Concept 1 map filters with property cards and filter cards

![Output sample](https://github.com/csuksangium/maps/blob/master/ezgif.com-resize.gif)&nbsp;&nbsp;![Output sample](https://github.com/csuksangium/maps/blob/master/ezgif.com-resize%20(3).gif)


The video below shows a full demonstration of the Concept 1 map prototype:

[![Alt text](https://img.youtube.com/vi/KRKDliJczms/0.jpg)](https://www.youtube.com/watch?v=KRKDliJczms)


## Concept 2
Concept 2 is more of an experimental exploration with the redesigned pins, but pin overlapping is handled by limiting property on map rather than using clusters like Concept 1; this is done by maintaining a corresponding relationship between list view and some measures taken in the exploration so users do not get lost between view switch include:
1. Numbered property in list view and property card in map view to establish a relationship.
2. Selected property in list or map view will still be selected upon view switch.
3. Larger access to map view for ease of switch and encouragement of usage of map.

From benchmarking various mobile application maps of other online travel agencies that limit properties on the map, 20 seems be the most consistent number (but we experimented with 10 for this prototype). Concept 2 explored limiting properties by showing properties on the map view in sets of 10 from list view (for example, app displays properties 1 to 10 on map, but displays properties 11 to 20 upon scrolling past property 10 in list view. Perhaps concept will be more comprehensible after watching the video of the prototype below)

Additional features introduced into Concept 2 include:
1. Top filter bar
2. Bottom-anchored property cards


Concept 2 Top Filter Bar
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Concept 2 List-Map Corresponding View Switch

![Output sample](https://github.com/csuksangium/maps/blob/master/run7TopFilter.gif)&nbsp;&nbsp;![Output sample](https://github.com/csuksangium/maps/blob/master/2Set.gif)

The video below shows a full demonstration of the Concept 2 map prototype:

[![Alt text](https://img.youtube.com/vi/yHukK8r_hfI/0.jpg)](https://www.youtube.com/watch?v=yHukK8r_hfI)


All prototypes are recorded with Quicktime Player.

Maps Redesign & Exploration - UX Prototyper Intern with Agoda Product & Design Team (Summer 2017)

Chanan (Champ) Suksangium &nbsp;&nbsp; (Presentation date: August 16th 2017)
