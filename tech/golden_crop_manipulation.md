# Golden Crop Manipulation

Golden crop manipulation is a form of RNG manip that allows us to guarantee harvesting golden quality crops by planting on specific tiles. This tech can be done on patch 1.5, or patch 1.6 with legacy RNG enabled.

## Overview

At the start of each in game day, the game picks certain tiles on your farm that will yield a golden quality crop depending on your farming level. The tiles that it picks are "random", but in reality actually follow a predictable pattern. Therefore, once we have harvested a single golden quality crop (typically a parsnip), we can use that to predict the future dates and locations of golden quality crop tiles.

For example, if you harvest a golden quality crop then:
- 1 day later, the tile 3 right and 2 up from the original crop will be golden quality
- 7 days later, the tile 1 left from the original crop will be golden quality
- 11 days later, the tile 1 up from the original crop will be golden quality

Extrapolating from this, we can set up future planting spots and dates to harvest that guarantee golden quality crops, which makes for better gifting.

## Example

In the [2 player Emily/Maru route](../routes/multiplayer/2p_emily_maru_intermediate/stardew_marriage_2p_intermediate_maru.md), the notes on Spring 6, Y1 say:
> - Harvest parsnips
> - Mark gold spot
> - Reset if no golden parsnip was found
> - Prepare planting spots for day 7
>   ![Cauliflower planting spots](../img/multi_2p_emily_maru_crop_manip.png)
>   ```
>   ~~~6~~6~~~~
>   ~7~~@~~~~~~
>   ~~~~~~7~~7~
>   ~~~~~~~~~~~
>   ~~~6~~6~~~~
>   ~~~~~~~~~~~
>   ~~~7~~7~~~~
>   
>   Legend:
>     @: Gold quality parsnip spot
>     6: Plant cauliflower here here, harvest on 26th
>     7: Plant cauliflower here, harvest on 27th
>   ```

What this means is that you should harvest all of the parsnips, and then mark the spot where a golden parsnip was found, typically using a piece of house furniture or crafted path. Then, you will plant Cauliflower seeds relative to the golden parsnip spot and harvest them on specific days. This will guarantee that all of the cauliflower will be gold quality, making for better Maru gifts. If no golden quality parsnip was found, we cannot do the prediction and will need to reset the run.

## Do it yourself

Golden quality crop patterns can be figured out yourself using [BlaDe's Predictor](https://www.nexusmods.com/stardewvalley/mods/6614).
