---
title: "World indicators"
date: 2023-02-10T21:33:52+02:00
draft: true
tags: [""]

---

__[Data visualization handbook](https://datavizhandbook.info/)__
![Text](/images/22-10_analysing_sizes.jpeg)

# Word Data Visualization
Exploring data at the world level always looks like a challenge for me: How can you identify and show interesting patterns? Hence my interest in participating in the World Data Visualization Prize organized this year.
After discarding my first idea of looking at past national energy mix (I had already explored it, and the available data were incomplete, and it was difficult to work with shares of total that didn't add up to 100%), I settled for present indicators, and I was drawn to the proportion of seats held by women in national parliaments.
My aim was to work on the UX/UI aspects of a dashboards, and explore similarities and singularities in indicators at country level.

# Choice of visuals
Tile grid maps allow to explore geographic similiarities and singularities, while taking aside surface areas of countries, since each country is represented by a square, or a dot. You could argue that real borders are not accurate. Here, the purpose is more to have a global sense of similarities and singularities.
My first intention as to also use a waffle chart for each square representing a country. The idea was to display a hundred dots (ten by ten), each dot representing one percent. I had colored each dot according to the share of seats held by women in parliaments for each country.
In further iterations I changed the color coding to highlight the missing share of seats that should have been held by women to reach parity. I had chosen a color to represent the share of seats above parity.


# Data modelling


# UX

# Legend

# Further development
This data visualization was intended to be more of a prototype. What could be considered in future iterations are:
* displaying countries with null data: Add another tile grid map underneath showing country names
* add other indicators, especially from other "types" (absolute values such as GDP, indexes such as Happy Planet Index): Review data modelling, as number formatting will differ from one type to another
* create categories of indicators, such as

# Take away
