---
layout: post
title:  "Art Science Hackathon"
date:   2015-01-01 09:07:38 -0800
categories: artsciencehack, outreach, design, visualization
---

# Concept
I have two really good friends that are both professional designers/artists living in Chicago. Every year over the holiday break we would discuss how fun it would be to do a collaborative project, but never got around to doing one because of our busy schedules. This year we planned a few months in advance to have a hackathon style four day work session between Christmas and New Years. We wanted to move as quickly as possible and make as many ideas happen as possible in our short time frame. We discussed all of the different data sets that I had as part of various research projects and the ones that turned out to be most appealing were the high-throughput plant imaging data sets.

# Crew
[Johnny Clark](http://www.john-clark.org/) is an architect and designer currently working for [Jordan Mozer](http://mozer.com/). The Mozer firm's was our home base for creativity, industrial grade internet, and organic shape object art inspiration. [Matt Harlan](http://matthewharlan.com/) is a freelance designer and screen printing guru. Matt also works on this awesome architecture zine called [soiled](http://soiledzine.org/). And myself.

## Examples

#### Arabidopsis thaliana architectural forms
I just learned Rhino about four hours earlier so this was a successful visualization of an Arabidopsis growth time series. This is a mosaic of the steps in constructing this city. As part of another project in the lab I have thousands of Arabidopsis timelapse images. I quicky modified some other code for a quick [python script](https://github.com/rjcmarkelz/AT_CV/blob/master/scripts/arabidopsis_hack.py) to binerize the plant relative to the background and then quantified plant area in each successive image. The height of the buildings correspond to the difference in rosette size from the previous timepoint. Then I got to really have fun and make a skyline and city in the shape of one of the plant outlines. Moving around the city that I had just made was really trippy especially when doing it from a 6 foot tall person perspective. The upper right is a view from the skydeck of a building. Johnny helped me make the surface transparent to give it a glass coffeetable feel. I think overall this project might help me pass Architecture 101.

##### Arabidopsis City visualization using rosette growth data:
![image](/static/img/cityscape.jpg)

#### Brassica rapa architectural forms
For another lab project I am doing some 3D reconstructions of Brassica rapa. I have loads of this kind of data, but thought it would be nice to see what an artist's perspective might use the data for. First things first, it was much too dense to load into memory so we randomly sampled the point cloud and made some wire frames by nearest neighbor searches. The renderings are simple and elegant. Then Johnny took it to the next level with a Rhino plugin called Grasshopper to produce the metaball renderings and octree representations of the data. A free plugin that might make the cost of Rhino worth it.

##### Brassica rapa sparse proximity structure:
![image](/static/img/proximity.jpg)


##### Brassica rapa metaball space structure:
![image](/static/img/METABALL_5.jpg)
