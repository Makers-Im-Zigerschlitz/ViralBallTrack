# ViralBallTrack
Simple and cheap set for a modular ball track to sweeten up life in quarantine in times of COVID-19

## Goal
- Create a Hacker- and Maker-Challenge in times of COVID-19 isolation.
- Give families a fun way of spending time together during quarantine, brainstorm ideas, invent mechanisms, learn by trial and error and admire their own builds and the works of other participants.
- Hackerspaces / Makerspaces / Schools / Libraries can prefabricate kits and sell them with a small margin to support their institution.

As soon as the storm passes by and we get to meet in person again we'll be able to daisy-chain our tracks and admire all the creativity coming from several weeks of isolation

## What are the specs?

### Baseplate / Dimensions
To make ends meet the top of your baseplate needs to be at **25mm above ground level** - bonus points for adjustable feet for leveling.

![Level of baseplate](documentation/images/TopBaseplate.png?raw=true "Top of baseplate needs to be 25mm above ground")

There are no limits to the dimensions of your ball track module - you'll have to move it on your own!

### How to connect your ViralBallTrack to the others
It is absolutely critical to plan your entry and exitpoints as described here. We don't want those ball bearings to fall of the edge of your board or get stuck!

You can find the required STLs in the [hardware](hardware/entry-exit) folder of this repository. 

- The arrow of the exit-part needs to be aligned to the right upper edge of your baseplate. 
- The wings of the entry-part need to be aligned to the left upper edge of your baseplate

![Alignment of connector](documentation/images/Connector-top.png?raw=true "Alignment of connector")

![Alignment of connector 3D](documentation/images/Connector-Projection.png?raw=true "Alignment of connector oblique")

### Connections / Power
- 5V DC
- You can use battery packs, power banks or lab power supplies or other regulated power sources of your choice.
- Want to harvest the power of the wind or the sun? Cool! But please don't output more than 5V to the power rails.
- We suggest preparing wires to externally power your contraption (mostly the lift mechanisms). Use red wire for positive (+) leads and black wire for negative (-) leads - we don't want your motors to run backward.
- Think about your neighbor: plan for the option to pass along that current @ 5V DC to your right.

### Marbles / Balls
We have decided on 10mm steel ball bearings - this allows for conductive mechanisms or magnetic elements

### Lift mechanism
Build your own contraption! We'll provide files to fabricate simple lift mechanisms in the next few weeks.

For inspiration: Search for "marble lift" "lift mechanism" or similar keywords.

### Other requirements
- Your ball track needs to be able to handle several ball bearings coming after another (avoid one-way mechanisms).
- Keep it safe and fun to watch: don't use high voltage / high current electricity, don't eject parts out of your ball track, don't use fireworks... - you get the idea.

## Promote your work
Share your masterpieces on social media by the hashtag of #ViralBallTrack. 

## Join the discussion
Find our mattermost channel at https://chat.coredump.ch/coredump/channels/viralballtrack (registration is open) or via Matrix at `#viralballtrack:matrix.coredump.ch`.

## Improve the design
That's what this git is for!
