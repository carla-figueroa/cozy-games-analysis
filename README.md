# cozy-games-analysis
Exploring the characteristics and recurring design profiles of Cozy-tagged Steam games using Python, data visualization, and K-means clustering.
# What Makes a Cozy Game? 🎮

An exploratory analysis of Steam game tags examining what
distinguishes Cozy-tagged games and whether "cozy" represents
a single type of game or multiple design profiles.

## Research Questions

1. What characteristics distinguish Cozy-tagged games from
   the broader Steam catalog?

2. Are Cozy games a single type of game, or do distinct
   profiles exist within the category?

## Tools

Python · pandas · Matplotlib · scikit-learn · Jupyter Notebook

## Dataset

Steam game metadata including titles, genres, user-defined
tags, reviews, pricing, and engagement measures.

737 games in the dataset were explicitly tagged "Cozy."

## Approach

I analyzed the prevalence of Steam tags among Cozy-tagged
games and compared them with the broader Steam catalog.

I then represented selected characteristics as binary features
and used K-means clustering to explore recurring profiles
within the Cozy category.

## Key Findings

Cozy games were characterized by a combination of emotional
tone, visual style, and gameplay mechanics rather than one
traditional genre.

Five recurring profiles emerged:

- Cute & Colorful Comfort — 35.0%
- Cozy-Adjacent Adventures — 22.4%
- Builders & Life Sims — 20.2%
- Wholesome Puzzle & Point-and-Click — 13.7%
- Creature Collectors & Hidden Objects — 8.7%

## Takeaway

The findings suggest that "cozy" functions more like an
umbrella design identity than a conventional genre.

Different combinations of relaxing aesthetics, exploration,
collecting, simulation, puzzles, and other mechanics can
produce a cozy experience.

## Limitations

Steam tags reflect user and developer categorization rather
than objective measures of game design. The clustering
analysis also relies on selected binary tag features, and
cluster names are descriptive interpretations rather than
official categories.

## View the Analysis

See the full Jupyter notebook for the analysis, visualizations,
clustering methodology, and interpretation.
