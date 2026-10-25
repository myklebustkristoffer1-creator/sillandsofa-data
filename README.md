# Robot vacuum height and door-sill data

Each maker's published height, door-sill (threshold) rating, rug figure and maximum suction rating for 30 robot
vacuums sold in the US, with the maker's source page and the date we read it. Collected by
[Sill & Sofa](https://sillandsofa.com), a site that matches robot vacuums to real homes.

- Table and notes: https://sillandsofa.com/data
- This file: `data.csv` (one row per robot; inches first, the maker's millimetres beside them where given)
- How the figures are read, and why makers' numbers aren't comparable: https://sillandsofa.com/door-sills and
  https://sillandsofa.com/robot-height

## Columns

`id`, `name`, `brand`, `height_in`, `height_mm`, `height_raised_in`, `height_note`, `door_sill_in`, `door_sill_mm`,
`door_sill_note`, `two_step_in`, `two_step_note`, `rug`, `mop_on_carpet`, `suction_pa`, `in_finder`, `page`,
`sources`, `read`. An empty cell means the maker publishes no figure. A door-sill note that says "obstacle" is the
maker's obstacle-crossing figure, not a door-sill rating.

## Use

Free to use with a link to https://sillandsofa.com/data. Every figure is the maker's own, from the source in the
`sources` column, read on the date in `read`; we don't test robots. Corrections and missing makers' figures:
contact@sillandsofa.com.

Sill & Sofa is written with AI and run by Kristoffer Myklebust ENK (Norway). Some of its store links pay a commission.
