# Infinite Resources

This is a mod for the game [Factorio](https://www.factorio.com/). It can be downloaded from the [Factorio Mod Portal](https://mods.factorio.com/mod/sonaxaton-nuclear-fuel-krastorio-compat).

## Description

A small mod to re-balance GotLag's [Nuclear Fuel](https://mods.factorio.com/mod/Nuclear%20Fuel) mod when used with the overhaul mod [Krastorio 2](https://mods.factorio.com/mod/Krastorio2). Both mods make changes to nuclear processing recipes and so without this mod you end up with a completely imbalanced fuel reprocessing cycle. K2 also changes the fuel values of uranium fuel cells, so this mod updates the breeder fuel cells from NF to have the correct relative energy capacity.

Full list of changes:

* Re-balances Nuclear Fuel Reprocessing to consume/produce the same relative number of uranium fuel cells and uranium-238 as NF does with vanilla, based on the fuel cycle setting. For the Classic cycle, this multiplies the K2 recipe's fuel cells and uranium-238 by 4. For the Alternative cycle, this multiplies fuel cells by 2 and uranium-238 by 4/3. The byproducts added by K2 (stone and tritium) and NF (plutonium) are not adjusted.
* Updates MOX fuel to produce 5x fewer uranium fuel cells since in K2 fuel cells are much more energy-rich. This aligns with the fact that K2 divides the vanilla number of fuel cells in Nuclear Fuel Reprocessing by 5.
* Updates the breeder fuel cell recipe to produce 5x fewer cells as well.
* Updates the breeder fuel cell reprocessing recipe to consume 5x fewer cells as well as produce more uranium-235. Without K2, this recipe produces enough uranium-235 to make the same number of uranium fuel cells as breeder cells that were reprocessed. With K2 and this mod, the amount is adjusted to maintain this ratio. The updated recipe will consume 2 used breeder cells and produce 4 uranium-235, which is enough to make 2 uranium fuel cells. If [Schall Uranium Processing](https://mods.factorio.com/mod/SchallUraniumProcessing) is installed, this amount is adjusted for the changes it makes to be 8 low-enriched uranium.
* Updates the NF recipe to make nuclear fuel from rocket fuel and plutonium to use less plutonium since plutonium is harder to make. With the change you get 4x more nuclear fuel for the same amount of plutonium.
* Updates the energy capacity of breeder fuel cells to be the same ratio to K2's uranium cells as they are in vanilla (half).
* Updates the stack sizes of the items added by NF (plutonium, breeder fuel cells, used breeder fuel cells) with the same updates to similar items made by K2.
* Removes the Kovarex Enrichment Process technology as a prerequisite from any other technology since NF disables it. For K2 this includes the Fusion Energy technology, but it will work for any other technologies added by other mods as well.
