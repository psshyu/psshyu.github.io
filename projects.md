---
layout: default
---

## Projects

### Final Fantasy XIV Cross-World Hunt App
* [http://crossworld-hunts-xiv.herokuapp.com](http://crossworld-hunts-xiv.herokuapp.com/)
* [Git Repo](https://github.com/psshyu/crossworld-hunt-xiv)


This application aims to bring the information from the following three sites together:
* [Ariyala's Hunt Tracker](https://ffxiv.ariyala.com/HuntTracker/Gilgamesh)
* [FFXIV the Hunt](https://ffxiv-the-hunt.net/gilgamesh)
* [Garland Tools' Bell](https://garlandtools.org/bell/)

It will include tools to backtrack environmental conditions surrounding a mob's time of death (namely weather, in-game time, and moon phase). Additional statistics will be gathered to generate data visualizations to assist the FFXIV hunt community in narrowing down the requirements and conditions for a hunt mob.

##### Future Plans
- [ ] Implement conditional spawn conditions 
  - [X] Weather
  - [X] Time
  - [ ] Moon phase
- [ ] Overall UI facelift
- [ ] UI for the back tracking tool
- [ ] Compact view alternative
- [ ] Ability to filter mobs by:
  - [ ] Open/Closed
  - [ ] Time into window
  - [ ] World
- [ ] Convert a lot of redundant code into ReactJS components (I'm looking at you, mob cells)
- [ ] Automated reset of timers for post-maintenance windows
- [ ] AJAX refresh of mob cells at selectable intervals (60s, 30s, 15s)
- [ ] Spawn location narrowing tool using web sockets 
- [ ] Data Visualization for all mobs. Actual metrics TBD
- [ ] A tool to record spawn attempts
- [ ] OAuth via FFXIV Hunt Community's Discord... gotta keep those trolls and edge-lords at bay somehow :/



### U.S. Source Rock Geochemical Data Visualization
* [https://psshyu.github.io/dataviscourse-GeochemOilandGas/](https://psshyu.github.io/dataviscourse-GeochemOilandGas/)
* [Git Repo](https://github.com/psshyu/dataviscourse-GeochemOilandGas)
* [Screencast](https://youtu.be/4HY0Ihaf76M)

This project visualizes U.S. source rocks geochemical data (TOC, S1, S2, etc.) by displaying the data interactively, facilitating the analysis/exploration of the data at different scales: data point, oil well and basin-wise. As the audience and information are quite niche, there are a few terms of art that you might want to familiarize yourself with in the 'About' page of the site before diving into the data.

Or, you know, if you're here to poke around and play with the data viz, you just go ahead and do that :D


### Course Watcher
A quick and dirty script that periodically polls University of Utah classes to see if someone has dropped a class. Some of the classes don't have waitlists, so this app pushes a notification to me when there is a seat in a class I am watching. 