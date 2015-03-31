---
layout: post
title: Databases for artists
cover: /images/dbscreenshot.png
---

![Screen shot of the front end]({{ site.url }}/images/dbscreenshot.png){:.floatright}
We have come back again and again to the problem of how to keep track of such a large number of artworks. 

There are a number of programs out there designed to help with this problem.  Prices range from around $50 through to the thousands of dollars.
<!--more-->

Peter draws regularly.  Each work takes hours and joins a growing stack on a large shelf in his studio.  The converted single garage is not large enough to fit a proper large format filing system.  There needs to be some sort of index, sorted by date and subject.

The two cheap options are [Flick!](http://www.arawak.com.au/flick.html) and [Artist's Butler](http://www.lynnsoft.net/).  They are both about US$30.  They are both based on FileMaker.  So you get to use someone's database template, but customisations are at the discretion of the developer and there is no guarantee that they will keep going.

I would like to have a go at making my own, but FileMaker Pro is US$329 for a single user license.  OpenOffice Base just doesn't cut it so far.

Another avenue is to choose one of the new cloud based services:

[Artwork Archive](https://www.artworkarchive.com) - free for the first ten pieces! Sounds great for keeping track of artworks at different galleries.  It doesn't mention an e-commerce facility, but they are actively developing, so it probably won't be long.

[ARTsala](http://www.artsala.com) is a particularly attractive option as it incorporates generating your own web gallery for public perusal with e-commerce built in.  It looks a little less swish than Artwork Archive, and costs more than twice as much for the unlimited version.

Being a die-hard Linux afficionado, I had to have a go at doing it open source.

The problem with searching for open source database front ends is that "user friendly" means a whole different thing to hard core database gurus.

Right now I have settled on [Xataface](http://xataface.com).  It is fairly technical, but quick to get going.  You need to know a lot about databases to really get it up and running.

You can have a sneak peek at [work.brandt.id.au](http://work.brandt.id.au).  It is set up as a sort of front end, just to show the works themselves.  The back end includes information about sales and things to help with our financial accounting.

I hope to make a cut down template that could give other artists a head start towards making their own self-hosted art database.  Please pester me about it - somehow these grand plans seem to dilute over time.


