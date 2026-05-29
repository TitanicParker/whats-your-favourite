# What's Your Favourite?

A small visual theorem reader for Theorem Zero.

This repository holds a single-page HTML theatre. It does not behave like a rich application. It opens one plate at a time, lets that plate compose itself, lets it decompose itself, and then repeats. The only navigation is previous plate and next plate.

The current build is an exploratory set of 100 generated visual plates. They are deliberately varied: some sparse, some mechanical, some chromatic, some nearly monochrome, some cellular, some circular, some chaotic. The purpose is selection. Good plates can be identified by number and family, then refined into authored visual relations later.

## Open the reader

Open `index.html` in a browser.

If GitHub Pages is enabled for this repository, the same file will serve as the site entry point.

## Product logic

One plate is open.

That plate composes itself.

That plate decomposes itself.

That cycle repeats.

The viewer does not scrub, configure, toggle, or operate the geometry. The viewer watches the relation recur.

## Controls

Use the left and right arrows on the screen, or the keyboard arrow keys, to move between plates.

## Current status

This is a prototype plate reader. The HTML runtime is intentionally homogeneous: the stage, renderer, timing loop, and navigation remain the same. Variation comes from plate definitions only.

The next useful work is to review the 100 plates, identify strong visual families, and use those discoveries to author stricter theorem plates.