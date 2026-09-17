---
layout: post
title: "Time to say goodbye"
author: "Yan Fan"
date: 2015-10-01
source: "http://visionarycross.org/time-to-say-goodbye/"
archived: "20180922170625"
archive_source: "Common Crawl CC-MAIN-2018-39"
---
I can't really believe my three-month adventure in Canada is coming to an end. I found it hard to summarize everything happened to me during my stay, but I had so much fun with people here and the days I spent in Lethbridge will be in my memory forever.



 



**Part 1 My Research Work **



I  felt so lucky that I had the chance to come to University of Lethbridge and joined the Visionary Cross Project to work as Mitacs Global Link Fellow, under the supervision of Daniel O’Donnell in July. My work was to map a point from Unreal to 3DHOP or vice-versa, which was not my area of expertise but it turned out to be interesting and I could really work something out in the end.



Here's what I've done following the timeline:





- Looked into the difference of left-hand (Unreal) and right-hand (3DHOP) referencing system and found out the matrix to convert one to another. An object has world, local, camera coordinate system to display its position from a different perspective. To map the point from one to another, we need to know what kind of referencing system they're using and how to convert it.


- Converted.ply (3DHOP) to.fbx (Unreal) or vice-versa by 3D tools. I got two models and used 3D graphics softwares like 3DX MAX, MeshLab and Blender to easily convert the  models. Blender could import both.ply and.fbx file format, while MeshLab supports.ply and 3DS MAX supports.fbx only.


- Built a basic scene based on the third person template in Unreal, displayed the cursor and printed the coordinates of the point which the camera was looking at. I didn't use the whole gaming environment the team had already done because I just wanted it to be a simple demo, so I made a scene by my own according to the Unreal documentation and community.


- Built a simple 3DHOP viewer based on the hot spot example following the how-to tutorial. I improved the hot spot function so that it was not preset but dynamically changed according to the coordinates passed by URL. It was also useful to set up the initial angle by a function called presenter.animateToTrackballPosition(), which could somehow duplicate the view from Unreal to 3DHOP.


- Put two models in Blender, measured the length, width, height of the models and calculated the ratio. I found that.fbx model is scaled down approximately 20 times compared with.ply, and the origins of two models were not at the same position, which led us to find out how to reset the origin, where to put the origin and what kind of tool is better to do it.


- Integrated what I've done so far, made a summary and wrote a documentation so that people could catch up to continue the project. Based on the problems encountered in the project, I also wrote a standardization with some advice to improve the process.




Here're some issues we still need to figure out:





- Find out the camera information in Unreal.


- Solve the problem that the size of the exported model will be bigger than expected in Blender, which couldn't be loaded in 3DHOP.


- Decide where to put the origin.


- Write a converter to duplicate the view from Unreal to 3DHOP.




Looking back my research work in University of Lethbridge, I really want to thank everyone who helped me from the bottom of my heart: Thank you for making this three months so meaningful and worthwhile!



 



**Part 2 My Colorful Life**



I have to say, this is the best summer I have ever had! I had many firsts: first time on the trail, first time camping, first time shooting... These are all my precious memories!



I love mountains, lakes, all those beautiful landscapes in Canada: Maligne Canyon in Jasper, Peyto Lake in Banff, Bear's Hump in Waterton... I had seen the pictures of these famous scenic spots in Canadian nation parks, but I didn't believe those because I thought they were photoshoped. Only when I was really in the beautiful scenery then I realized that the photos were real. It was just amazing!!! I also went to the Head-Smashed-In Buffalo Jump and Frank Slide, which really got me into the history and culture of Canada.



I also did a lot of outdoor activities with Mitacs friends and some Chinese friends I met here. We went to play mini golf and go karts, which was really exciting! Then my friend drove me to the Park Lake at midnight to watch meteors, and I even got a picture of it! A couple of weeks ago, we decided to go camping in Waterton and go hiking to the Crypt Lake the next day. That hike was fantastic! In 2014 National Geographic, it was rated as one of the World's 20 Most Thrilling Trails! Another exciting thing I did was shooting. My supervisor Dan took me and Gurpreet there yesterday and it felt so good when you really hit that target paper, so cool!



Another thing needs to be mentioned that, although I came to Canada alone three months ago, I wasn't really lonely because I had so many friends here! Especially for the last month, I moved to a new place, staying with a family who treated me like a family member. They invited me to dinner, taught me how to play the piano, baked a cake with me... I was afraid of dogs because I was bitten by a dog when I was young. But because of the dog in their house, Kala, which is such a friendly dog, I no longer feel afraid anymore! They even took me to a Canadian citizenship ceremony to let me feel the culture deeply, and I really wanna say thank you to them.



![](http://visionarycross.org/wp-content/uploads/2015/10/IMG_4736-225x300.jpg)



I love this beautiful country and I love these friendly people living here. Hope one day I will be back!
