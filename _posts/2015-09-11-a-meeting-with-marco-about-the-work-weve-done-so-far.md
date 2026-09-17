---
layout: post
title: "A meeting with Marco about the work we’ve done so far"
author: "Yan Fan"
date: 2015-09-11
source: "http://visionarycross.org/a-meeting-with-marco-about-the-work-weve-done-so-far/"
archived: "20180723080302"
archive_source: "Common Crawl CC-MAIN-2018-30"
---
Last Friday, we had a meeting with Marco about the work done so far and the future work of mapping the point from one to another.

Three important questions which need to be answered are:

- How to find the point of interest?

- How to duplicate the view?

- How to map the point from one to another?

The difference between how Unreal and 3DHOP works matters a lot to the first question. Because Unreal works with the principle “camera in hand”, which is different from “object in hand” in 3DHOP, the camera is not always focused on the object (the Cross) and it makes us think what is a good way to find the point of interest when the camera travels around the whole scene.

For duplicating the view, the key is to find the information about camera position used in Unreal to describe the viewing point. Knowing what parameters Unreal will give us about the camera position, we will be able to write a converter in 3DHOP to duplicate the view from one to another.

The answers to those two questions above are the first – phase preparations of the work, what should we do to really map the point of interest from Unreal to 3DHOP? First, two models use different coordinate system, which is easy to solve. We’re also facing the problem that the models are not the same size because people who work with Unreal need to resize the Cross to cooperate with gaming environment. We put two models in Blender and it turned out that the model used in Unreal is scaled down by the one in 3DHOP, which is good for us. The main issue, however, is that the origins of models are not the same. The origin of the model in Unreal is at the top right corner of the bottom, while the one in 3DHOP is at the center of the bottom. If the (0,0,0) is not at the same position in two models, it would be much more difficult to deal with the coordinates.

[![](http://visionarycross.org/wp-content/uploads/2015/09/Picture2-300x188.png)](http://visionarycross.org/wp-content/uploads/2015/09/Picture2.png) [![](http://visionarycross.org/wp-content/uploads/2015/09/Picture1-300x202.png)](http://visionarycross.org/wp-content/uploads/2015/09/Picture1.png)

So now the question is, which position would be better to put the origin on and how do we fix it? We can’t take an arbitrary point as the origin, and there has to be a protocol/standard that is convenient as well as useful. We can either fix the origin of the Cross or rebuild one to make sure the origins of two models are at the same point.

We were all pleased to see this project is really on the right track and we will continue to work on it.

Here is the link to presentation by me in google drive: [https://drive.google.com/file/d/0B4-K1GZHwphnN0x3TXYxUTU0dlE/view](https://drive.google.com/file/d/0B4-K1GZHwphnN0x3TXYxUTU0dlE/view)
