# Steam-Data-Analysis


## Introduction

Steam has been the household name for PC gaming since it was released. It has very few successful competitors, and those that have been a threat to its hegemony have done so at great cost. Epic Games Store is one such, which has attracted many publishers through paid timed exclusives and taking lower cuts on sales. The only other storefronts of note are Humble Bundle and GOG, both with particular niche selling points. The former sells combined packs of game and software while the latter prides itself on DRM free games.

In the face of these competitors, Steam has released various new features and programs to develop its platform. In this document, we'll be looking at the general health of Steam since its first partnership with other publishers in 2005, as well as the growth of a few of its programs such Early Access, Achievements, Cloud, Workshop, Trading Cards and more.

## Data

The data is extracted from https://www.gamedatacrunch.com/ using a python web scraping tool called selenium. Data is then processed and aggregated to have a unified form. There is a total of around 59000 games. However because so many games do not have any reviews, or very few, we only look at games that have 10 or more reviews. This brings us down to considering 29000 games for our analysis. This means there is approximately 30000 games with less than 10 reviews. A good name for this would be the Steam No Man's Land, where games come to be unplayed and unreviewed. It is also a proof of how far steam has come, from Valve only storefront, through select third party publisher only deals, and finally to any third party publisher. 

## I. Releases and Reviews

Let us begin by looking at general statistics of the games that are actually played on Steam. 
