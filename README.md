# Ovid, Now With More Structure!

Tl;DR: this is a repo for Ovid-related JSON and the Python notebooks I use to create it.

Inspired by the [Aeneid API](http://aeneid.eu/api/), I wanted to make an API
for my favorite Roman poet, Ovid. Before I could do that, I had to sort out
the Ovid content, which lives in many different places, and many different forms,
online.

## Contents
This repo started as a collection of JSON files I made from the Ovid [XML
file I downloaded from Perseus](http://www.perseus.tufts.edu/hopper/dltext?doc=Perseus%3Atext%3A1999.02.0068).

The goal of creating the JSON files was twofold:
1) To create JSON that was less complex than the original XML structure
2) To create a more consistent data structure that could support multiple works.

You can read a little more about why I did that [here](http://techintranslation.com/if-you-want-something-done-part-1-getting-ovid-into-json/).

I'm now in the process of adding JSON files for tranlsations, too.

## User story
As an structured content enthusiast, I want Ovid's poetry to be available in propery structured digital form, so other people can use it without wading through tons of weird data structures.

Edge case, you say? Maybe. But then again, how are tech-literate people ever going to do anything
interesting with Ovid, if he's not in the proper format? It's kind of like public transportation, of Field of Dreams: if you build the infrastructure,
they will come.

Anyway, I use this structured data for an [Ovid API](https://ovid-api.herokuapp.com/), which I [built with Django](https://github.com/risatrix/ovid_api). I'll keep playing with it as time allows.

## Use
I haven't yet gotten around to putting up a license. Everyone is welcome to use the JSON etc. I've put the notebooks in their own folder, along
with the requirements you should need to load in your env to use them.
