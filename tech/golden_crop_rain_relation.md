# Golden Crop/Rain Relation

An advanced version of [Golden Crop Manipulation](./golden_crop_manipulation.md) and [Rain Prediction](./rain_prediction.md). Golden crop/rain relation is a form of RNG manipulation which uses rain patterns to predict golden quality crops, or golden quality crop locations to predict rain.

## Overview

[Golden Crop Manipulation](./golden_crop_manipulation.md) allows us to use golden quality crop locations to predict future golden quality crop locations.

[Rain Prediction](./rain_prediction.md) allows us to use rainy days to predict future rainy days.

It turns out that these two RNG things are actually somewhat linked. We can use rain patterns to somewhat predict where golden quality crops are more likely to spawn, and vice versa. Typically marriage speedruns will only ever use rain to predict golden quality crops and not the other way around.

## Example

In the [Intermediate Abigail route](../routes/abigail/stardew_marriage_abigail_intermediate.md), the notes for Spring, Y1 say:

> ### Spring 1, Y1
> - Plant parsnips
>   ![Parsnip planting spots](../img/abigail_crop_manip_parsnips.png)
>   ```
>   ~HHHHSSSHHM~~~P~~~
>   ~~~~~~P~~~P~~~PPPP
>   T@~~@~PPPPPPPPP~~~
>   @~~@~~~~~~~~~~~~~~
>   ~~~~~@~~@~~@~~@~~~
>   ~~~~~~~~~~~~~~~~~~
>   ~@~~~~~~~~~~~~~~~~
>   @~~T~~@~~@~~@~~~~~
>   ~~~~~~~~@~~@~~~~~~
>   
>   Legend:
>   H: House
>   S: House Step
>   M: Mailbox
>   P: Path
>   T: Tree
>   @: Parsnip planting spot
>   ```
> - Sleep
> 
> ### Early Spring, Y1
> - Reset on rainy 6th
> - Reset on rainy 8th
> - Reset on sunny 9th
> 
> ### Spring 27, Y1
> - Harvest parsnips
> - Mark Gold parsnip location
> - Reset if no gold parsnip
> - Sleep

Why plant the parsnips on spring 1st on those particular spots? Because of the rain manip that we do immediately afterward. We are resetting any run where it is sunny on Spring 9th, or in other words, it is guaranteed to rain on Spring 9th. Given that we *know* it is going to rain on Spring 9th, we know that these particular parsnip spots are more likely to be golden quality on Spring 27th. It isn't guaranteed, but it is much more likely than just planting the parsnips on random squares.

## Do it yourself

The relationship between rain RNG and golden crop patterns can be figured out yourself using a combination of the [Rain Prediction Google Sheet](https://docs.google.com/spreadsheets/d/1R90dxVwzGcXk8GhsX7YkZoHOP7fFpuYS1qaht02M4iw) and the [Crop Quality Google Sheet](https://docs.google.com/spreadsheets/d/1e-LjO3NYIbTSGyx3bQraWZ5-7fjeyvWlBEyqaXPuiI8).
