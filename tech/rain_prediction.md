# Rain Prediction

Rain prediction is tech which allows the weather to be predicted years in advance. This tech can be done on patch 1.6 with legacy RNG enabled only.

## Overview

Rain prediction is very straightforward. On patch 1.6 sunny and rainy days are determined entirely by your game seed. That is to say, as soon as you create a new farm, the game has already determined which days will be sunny or rainy for the entire lifetime of your farm and nothing that you do in game can affect this (besides rain totems). On patch 1.5 and below, rain RNG is affected by the number of steps that you take, so simply moving around will change future rain patterns, making it unfeasible to predict rain in a speedrun setting.

On patch 1.6, if we can narrow down our game seed enough by observing RNG phenomenons on our farm, we can predict future rain patterns *very* accurately. This allows us to set up proposal days that suit our needs (since the mermaid's pendant can only be purchased in rain). It turns out that this can typically be done very early in runs by simply observing the rain patterns that occur in early Spring.

## Example

In the [Abigail Intermediate Route](../routes/abigail/stardew_marriage_abigail_intermediate.md), the notes on Spring 1, Y1 say:
> - Reset on rainy 6th
> - Reset on rainy 8th
> - Reset on sunny 9th

This is because if it rains on Spring 9th, Y1, it is guaranteed to rain on the 19th or 21st of Fall, Y2. If it rains on the 6th or 8th or Spring, it is impossible for it to rain on Spring 9th.
By resetting any run that does not have rain on Spring 9th, we guarantee it to rain right when we want to propose.

## Do it yourself

Rain prediction patterns can be figured out yourself using the [Rain Prediction Google Sheet](https://docs.google.com/spreadsheets/d/1R90dxVwzGcXk8GhsX7YkZoHOP7fFpuYS1qaht02M4iw)
