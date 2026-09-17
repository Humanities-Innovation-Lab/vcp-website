---
layout: post
title: "Well that’s that. Solving (?) the VC model and workflow"
author: "Daniel Paul O'Donnell"
date: 2015-12-01
source: "http://visionarycross.org/well-thats-that-solving-the-vc-model-and-workflow/"
archived: "20180922163022"
archive_source: "Common Crawl CC-MAIN-2018-39"
---
Yesterday, Dot Porter, one of the leads on the Visionary Cross project visited Lethbridge for a project meeting (and to speak to my DH class). The main purpose of her meeting was to plan the work that needs to happen on the Digital Library side of the project.



This is a core issue for us. As we say on the front page:


> The Visionary Cross project is an international, multidisciplinary research project whose principle objective is the development of a new kind of digital archive and edition of texts and objects associated with the Visionary Cross tradition in Anglo-Saxon England.
>
> Taking its cue from recent developments in digital editorial theory and practice, the project takes a  data-centric, distributed, and generalisable approach to the representation of cultural heritage texts, objects, and contexts in order to encourage broad scholarly and popular engagement with its material.



The important things here are that it is an *archive*-edition: it is data-centric, distributed, and (supposed to) be designed to encourage broad scholarly reuse and popular engagement. In our thinking on this, we have been very influenced by the work of Peter Boot and Joris van Zundert on "Just in Time editing" or, especially, [the edition as service](http://www.harrassowitz-verlag.de/dzo/artikel/201/004/4051_201.pdf). In other words, we have understood our work to be *not* primarily an interface, but rather a service: a source of mediated primary material. This is in keeping with the philosophy of my [edition of Caedmon's Hymn](http://www.boydellandbrewer.com/store/viewItem.asp?idProduct=7316), where the emphasis was on exploiting the power of existing web protocols, infrastructure, standards, and services, rather than custom programming.



In practice, however, this has proved to be something of a block in our progress. Since the very beginning, the Visionary Cross project has approached the problem of editing its objects as an intellectual market place. We've had several teams in place who have been working with our common material in different ways: as a Serious Game, as a student-centred resource, as raw material for humanities research, as part of a different edition of a related collection. In each case, the participants have been working alongside each other, rather than directly in collaboration or cooperation, in part because the thing the project has been leveraging has been the overlap in their enthusiasm and their interest in the common dataset. We've wanted people to *want* to share resources because they see how this sharing allows them to do their own research in the directions that appeal to them, rather than to try and bend their interests towards a common, lowest-common-denominator consensus-focussed single interface.



We began this way initially for funding reasons: we didn't have enough (our first grant awarded us only 25% of our ask) and the only way of getting any work done was to tie our project to the interests of its participants as they worked on other things.



But over the years we began to see this as a virtue as well. By the time we did get all the funding we asked for, this [百花齊放，百家爭鳴 (Let a hundred flowers bloom, let a hundred schools of thought contend)](https://en.wiktionary.org/wiki/let_a_thousand_flowers_bloom) approach had become a part of the goal of the project: we now wanted to exemplify the way we thought our project should be used by others in our internal workings (and, of course, byt the time the funding arrived, we were committed to our different streams anyway).



The downside to this approach, however, has been that it has proved to be difficult to manage: the sub-projects are themselves quite different from each other (though with at times considerable overlap in some aspects) and the result has been that it has been difficult to do the common work. It has also, in some cases, led to minor friction: overlap can, after all, look a bit like competition. As individual projects work on their interfaces, navigation, content, and the like, there's been little incentive to pay attention to the common aspects of our work; and more importantly, preparing content (objects, annotation, approaches, etc.) has generally involved customised work for specific sub-projects: instead of developing a core set of intellectual objects (metadata, annotation, etc.), we've basically had different groups adding custom intellectual objects to a limited set of common core facsimiles (i.e. the 3D models, photography, and, to a limited extent transcriptions.



This is both why we were having the meeting yesterday and why its results were so important. The goal of the meeting was to lay down the ground work for building the central Digital Library that would allow us to build an appropriate place for projects to feed back into the common body of objects and to provide a place where generalisable scholarship and mediation could be done: i.e. a place where we could develop common metadata, commentary, annotation, and the like that could be then used to distribute to the sub-projects



The result was the following diagram:



[![blackboard](http://visionarycross.org/wp-content/uploads/2015/12/blackboard-300x168.jpg)](http://visionarycross.org/wp-content/uploads/2015/12/blackboard.jpg)



![20151130_163341-2](http://visionarycross.org/wp-content/uploads/2015/12/20151130_163341-2.jpg)



The way to read this is that we currently have the situation at the far left and far right. I.e. as at the left, we have a lot of use-cases for our data--a Serious Game, a student-focussed reader, some work on a scholarly edition. And as at the far right, we have a collection of files: raw files, processed files, working copies, etc., all organised by origin (i.e. a dump of the different drives, cameras, scanners, and so on). What we don't have, is the middle: an object-organised collection of objects, metadata, and intellectual objects that can serve as an engine for the projects at the left. And this is where our problems are coming from: since we are missing that engine, the sub-projects are developing their own collections of intellectual objects and processed files.



Initially, it was as a middle that I thought we needed a digital library application. I.e. that the solution would be to set up an Omeka or DSpace, or ContentDM installation and put our stuff in it. But we were hanging up on the choice of software: was Omeka better or worse than Greenstone for this? how would the interface look? and so on.



What we realised yesterday, however, was that these were actually implementation (i.e. left-hand) issues, more or less the same as the questions about our various viewers and environments. That if we really saw the core of the edition as a curated collection of intellectual objects that were intended primarily for reuse by others, then we needed to focus entirely on the data--providing a simple, easily understood, open, and extremely robust collection that could be then used by others for any sort of other purpose, including putting in a Digital Library Application.



A model for this is [OPenn](http://openn.library.upenn.edu/). This is an example of the "digital library" in its most simple form: as a well thought out and curated and minimally skinned series of directories with predictable content and naming conventions... and nothing else. As Dot has shown in her own subsequent work, this approach is in fact extremely powerful: it is easy to add to (I was in Penn for the launch of OPenn this Spring, and it has already grown rapidly in the intervening months to include collections from other collections in the Philadelphia area); and it is easy to use for added-value projects: Dot has used this system to build eBooks, page-turning software, a searchable digital library, and so on.



Moreover, as Dot showed in [one of her two lectures yesterday](https://www.uleth.ca/notice/events/library-brown-bag-session-importance-open-access-schoenberg-institute-manuscript-studies), OPenn originated from what was actually a similar problem: a collection that existed in what we are describing here as a "left-hand" format without a corresponding "middle" (she also indicated that they might have had a similar "right hand" problem as well, but that's not important for us at the moment). The Schoenberg Institute at the University of Pennsylvania was created to "to bring manuscript culture, modern technology and people together to bring access to and understanding of our cultural heritage locally and around the world." Penn itself began a digitisation programme as early as the late 1990s, and, I believe, has now fully digitised and released its manuscript collection under a Creative Commons licence (CC-0, in fact). Like many libraries, it then released this material to the public using a "page turning" interface that allows users to "read" the manuscripts online in much the same way they would the actual codex (this is an interface design loved by museum and library directors, and, reportedly, the general public, but hated by most scholars who work with manuscripts).



[![Penn-in-Hand-Interface](http://visionarycross.org/wp-content/uploads/2015/12/Penn-in-Hand-Interface-300x168.png)](http://visionarycross.org/wp-content/uploads/2015/12/Penn-in-Hand-Interface.png)



The problem, however, was that apart from reading online, there was not much one could do with the material. It was possible to download individual manuscript leaves (and, if you worked at it, all the leaves in a given manuscript, page by page). There was also largely untyped output from the library MARC records for each manuscript that could, as far as I can see, be scraped, if you wanted to use it. But there was no easy way of accessing the resource for other reasons or to repurpose the material for other applications.



The solution to this was to develop OPenn. This is, in essence, a refactoring of Penn-in-hand in its absolutely most simple form: as a directory structure in which objects and associated metadata are grouped together. Each level in the directory can be browsed by a human as a web-page with links and images (a system so simple that, apart from the browser-side XLST processing that is going on, there is nothing that couldn't be accessed via [Netscape Navigator](https://en.wikipedia.org/wiki/Netscape_Navigator) or maybe even [Lynx](https://en.wikipedia.org/wiki/Lynx_%28web_browser%29)). But more importantly, each level can also be accessed by utilities like [wget](https://en.wikipedia.org/wiki/Wget) (allowing you to download entirely collections programmatically) or by URL (allowing you to address inidividual files externally). There are *no* bells and whistles here (there's not even a search function, though as Dot showed, you can build one in [viewshare](http://viewshare.org/)). There is *nothing* to maintain, other than paying for the server and your ISP. Directories and files are not even core Internet architecture, they are core *computing* architecture and not going anywhere any time soon.



But the important thing is that, by reducing their DL to its absolute most simple form, OPenn makes it easier to design almost everything else a user might want. In addition to the search interface, Dot showed us how she had then used external systems and libraries to build different ways of accessing the Schoenberg material--as eBooks, for example, or even through a page turning interface library. In other words, by massively--you're tempted to think almost irresponsibly--simplifying the core service of their project, OPenn is able to do everything Penn-in-Hand does, and much much more easily.



So this, I think, is where we have to go with the Visionary Cross. To focus on the core aspects of our content--metadata, curation, content, and high quality objects--and present this to potential users (and our various subprojects) in as simple a fashion as possible: in a way that focusses *purely* on making the data available in a responsible fashion and ignores all questions of interface, tools, and other things we commonly consider when we think of "digital editions," in order to do a good job of delivering the data in a form that others can use more easily for their own projects.
