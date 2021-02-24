# moss_pole

### Description:
This is something to do with botany. I don't know much more about it. A botany enthusiast I know bought something similar to this at a farmers market. It seemed sturdy but kept falling over and was too small. So, I made a version where all the parameters could be dialed in.

I fond these links which I think explain the idea pretty well.
- [Ohio Tropics](https://www.ohiotropics.com/2020/05/03/diy-moss-pole-how-to-make/)
- [Garden.org](https://garden.org/ideas/view/threegardeners/881/Make-Your-Own-Moss-Pole/)

### Contribute:
Yes. Do your thing. If you see a better way to achieve the results then let me know. Also, if you end up printing this thing send me pictures to include here.

### TODO:
- ~~fix the math on unit height~~
  - ~~after exporting several examples I found some cases that broke the formula~~
- ~~rename files. turns out these are not for x. so, rename them.~~
  - ~~figure out what this thing is so I can rename it correctly~~
- ~~move to appropriately named repo~~
  - ~~with a readme~~
  - ~~and a license~~
    - ~~checkout those new open design license~~
	  - ~~CERN OHL?~~
- ~~add images of this thing in use~~
  - ~~[one](https://www.ohiotropics.com/2020/05/03/diy-moss-pole-how-to-make/)~~
  - ~~[two](https://garden.org/ideas/view/threegardeners/881/Make-Your-Own-Moss-Pole/)~~
- moss_pole_v2.FCStd
  - ~~remove unnecessary formulas from spreadsheet~~
  - ~~format spreadsheet~~
  - ~~add instructions/descriptions to spreadsheet~~
    - ~~disclaimer about how certain values can cause issues~~
  - ~~boolean fuse hex_tube, hat, and boots~~
  - ~~var for isBottom, isMid, or isTop~~
    - ~~it may be okay to have them all be mids~~
  - ~~re-add several more examples~~
- moss_pole_stake.FCStd
  -  need to produce
- moss_pole_conn.FCStd
  - need to produce
- go through tm and try to find the copy that used diamonds instead of hexagons
### Notes:
- moss_pole_v1.FCStd is garbage. It was just a test of how to achieve certain things. I kept it included because sometimes it is neat to see the progression.

### Why:
The project is extremely simple which was a perfect candidate for further learning freeCAD my new 3d modeling software of choice. I immediately made the project open because I had the freeCAD community help. There were several iterations of the design with different ways to achieve the final result.
 - There were different hole shapes but, obviously beehive is good for a reason. Although, the diamonds did look neat.
 - There were versions where the final tube was faceted instead of being a cylinder.
 - There was also a version where the hexangular tooling was tapered to produce a uniform wall thickness on the front and back of the cylinder. This proved to be unnecessary and overly complicated.