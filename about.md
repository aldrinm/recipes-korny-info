---
layout: page
title: About
permalink: /about/
---

This is Korny's personal recipe site - it should be hosted at <http://recipes.korny.info>

Initially most recipes are just photos from books, or links to sites.  I do intend
to transcribe the ones that are just photos, but this will do as a minimum viable way to
get some of my favourites on the site.

## Use cases

I have two main reasons to build this site:

1. So I can get inspiration when thinking up food plans - I have a fuzzy toddler-impaired memory, and
I work better by viewing a list of options than by trying to remember stuff.  So I want my favourite
recipes, or those that look really interesting that I haven't tried yet, on a page to inspire me.
Otherwise I'll end up just cooking Spag Bol again as it's the only thing I can think of.

2. So I can see ingredients while shopping.  When I get to the store and want to make a bechamel,
it's nice to know roughly what ingredients I need!

There are lots of things that recipe sites do that I don't care much about:

* I don't want to cook from my phone/tablet! Mostly I cook from books / memory.  I have a handful of
internet-based recipes here, which might be exceptions, but generally I will use this for research not
for cooking

* I don't need an automatic shopping list, that's techno overkill, paper works just fine, or Trello if it's complex

* I don't need to store a million recipes.  I can always google, or go to a big recipe site, or a big book.
I just want to store the most common, most useful, or things I want to do more of like baking bread.

* I don't need magic ingredient calculators, or snippet organisers, or a pile of other bloated features that
most tools offer.  I generally prefer simple open text formats like markdown and maybe some YAML.

## Tags

I'm trying to grow tags as I need them. Some specific tag explanations:

#### incomplete
These are recipes that need transcribing from images or sources into proper text

#### untested
These are recipes I've never actually tested - use with caution.

#### external
Recipes that are links to someone else's site - I'm not going to bother copying web-based recipes here!

#### pressure-cooker
I have a shiny new Instant Pot pressure cooker - these recipes are generally specific to the IP, but probably can
be used on any pressure cooker.

#### toddler
Well, we follow baby-led weaning, so in theory everything is toddler friendly.  But I'm tagging with 'toddler' anything
that is especially popular (or has been at some stage)

## Technical

You can find the source code on Github at <https://github.com/kornysietsma/recipes-korny-info>

It is based on a very basic Jekyll site, plus some clever recipe metadata management I copied from [chowdown](https://github.com/clarklab/chowdown)

Recipe metadata should match the [recipe schema](https://schema.org/Recipe)

I used to know more about CSS than I do now - but I have no time and don't keep up to date,
so I'll probably just stick to out-of-the-box themes for styling.

(I'm not using the chowdown theme as it is in a bit of flux at the moment, and
I care more about content than style!)

## TODO

- fix the recipe.html template with actual styling - the chowdown styles do no harm, but they don't add much but confusion
- consider moving the "untested" recipes into a separate category or something? It's a bit messy to just use tags for everything
