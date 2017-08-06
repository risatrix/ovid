#Ovid Content Engineering(pre-API steps)

Inspired by the [Aeneid API](http://aeneid.eu/api/), I wanted to make an API
for my favorite Roman poet, Ovid.

##Contents
Tl;DR: this is a repo for Ovid-related JSON and the notebooks I use to create it.

It started as a collection of JSON files I made based on the [XML
file I downloaded from Perseus](http://www.perseus.tufts.edu/hopper/dltext?doc=Perseus%3Atext%3A1999.02.0068).

The goal of this step was twofold:
1) To create JSON that was less complex than the original XML structure
2) To create a more conistent data structure that could support multiple works.

You can read a little more about that [here](http://techintranslation.com/if-you-want-something-done-part-1-getting-ovid-into-json/).

I'm now adding JSON files for tranlsations, too.

##Job to be done

I used this structured data for an [Ovid API](https://ovid-api.herokuapp.com/), which I built with Django. I'll keep playing with it as time allows.

##Archival Use

I haven't yet gotten around to putting up a license. Everyone is welcome to use the JSON etc.  When I get a moment, I'm going to try to organize this in a proper way
so the JSON URLs don't change too much.
