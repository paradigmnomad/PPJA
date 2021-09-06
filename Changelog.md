# Changelog

This list is not comprehensive of every change made, especially towards gift tastes. 
Items that have been added that were dependencies from other content packs have been implemented with context tags to support flexibility.

## All Packs (Except Tailor Mouse & BAGI)
* Added Leo likes/dislikes to some items;
* Added `UniversalGiftTastes`. Most items will now either be `Like` or `Neutral` by NPCs;
* Changed letter background;
* Items gated behind receiving the Island letter have been moved to Island shops;
* Migrated over to DGA;

## BAGI
* Coming soon...

## Artisan Valley
* Added 2 new coffee items;
	* Cafe au Lait
	* Dark Coffee
* Added `peanut_butter_item` tag to Smooth Peanut Butter	
* Migrated basic machines over to DGA - PFM is still required for more advanced machines;
* Previously unimplemented pepper extracts are now implemented;
* Rebalanced gift taste values;
	* After seeing Shane & Pam's respective events talking about sobriety changes the gift preference of alcohol to dislike/hate;
	* Leo now hates alcoholic beverages;
* You can now purchase the ice creams & orange sherbet from the Ice Cream Stand;

## Cannabis Kit
* Migrated basic machines over to DGA - PFM is still required for more advanced machines;
* Rebalanced gift taste values;
	* After seeing Shane & Pam's respective events talking about sobriety changes the gift preference of alcohol to dislike/hate;
	* Leo now hates alcoholic beverages;
* Updated HCE, JA component to DGA (requires HCE update);

## Christmas Sweets
* Added Christmas Pudding
* Rebalanced gift taste values;
	* After seeing Shane & Pam's respective events talking about sobriety changes the gift preference of alcohol to dislike/hate;
	* Leo now hates alcoholic beverages;
	* Harvey now likes some cookies - he doesn't think they all will rot your teeth;

## Even More Recipes
* Added a bunch of new recipes;
* If an item is also a concession (ie Popcorn) then you must have the movie theater unlocked before you can purchase the recipe;

## Fantasy Crops
* Fixes typo in the crop descriptions;
* Rebalanced gift taste values;
	* Everyone likes `Doubloons` now;

## Farmer to Florist
* Rebalanced gift taste values;
	* You can no longer gift `Dried Posion`. Why would you want to do that?

## Fresh Meat
* Added additional drops to `Chicken` - `Chicken Wing` & `Drumstick`;
* Added additional drops to `Turkey` - `Drumstick`;
* Added `Cooked Mutton` item (I don't know why this wasn't in there but it wasn't)
* Added context tags `cooked_critter_meat_item`, `critter_meat_item`, `raw_meat_item`
* Added some new recipes;
	* Beef Taco
	* Cooked Chicken Wing
	* Cooked Drumstick
* Changed some sprites;
	* Remade the `Coconut Curry` sprite as at some point I overwrote the sprite and didn't have a backup
* Migrated basic machines over to DGA - PFM is still required for more advanced machines;
* Rebalanced gift taste values;
	* Shane now really hates anything with chicken in it (-80 friendship points);
	* Wizard now hates any raw, cooked, or by-product of Dragon & Phoenix;
	* Linus now likes raw meat and loves cooked meat;
	* Willy loves most seafood products;
	* Leo dislikes bird related meat & meat products (chicken, fowl, bird, ostrich, duck)
* Removed CPA component (migrated into DGA);
* Removed MYC component (migrated into DGA);

## Fruits and Veggies
* Added `bell_pepper_item` context tag;
* Added 5 new peppers;
	* California Reaper	
	* Ghost Pepper	
	* Poblano Chilie	
	* Scotch Bonnet	
	* Serrano Chile
* Added `Campagne Grape` to remove dependency;
	* Champagne Grape item has a `champage grape_item` tag
* Added `Catnip` & `Bay`
* Changed a few sprites;
	* Lettuce
	* Onion
	* Red Onion
* Changed how the `Bell Pepper` crop produces - if harvested early it will produce a green bell pepper. If harvested on time it can produce either a red, yellow, or orange bell pepper;
* Changed the name of `Bell Pepper` to `Red Bell Pepper`;
* Rebalanced gift taste values;
	* Leo has similar gift tastes to Jas and Vincent;
	* Made Emily feel more positive about items related to clothing/sewing
	
## Legacy Sprites
* Removed. Migrated legacy sprites into their respective DGA packs

## Mizu's Flowers
* Added color support for `rose` and regrowth as DGA supports that feature now;
* Dropped support for `Color Mania`
* Removed `spring, summer, fall` rose. This is now a config option to change between `seasonal` and `standard` rose appearance. There is only one rose crop now instead of four;

## More Recipes
* Added `peanut_butter_item` tag to Peanut Butter

## More Trees
* Added Bitter Orange Tree to remove dependency;
	* Bitter Orange item has a `bitter orange_item` tag
* Added Pistachio Tree to remove dependency on `Boarding House`;
	* Pistachio item has a `pistachio_item` tag
* Added Poison Apple (major friendship loss if gifted)
* Changed a few sprites;
	* Asian Pear	
	* Granny Smith Apple	
	* Ume	
	* Yuzu
* Redid some fruit trees with stock assets to be more unique;
	* Avocado	
	* Camphor	
	* Cinnamon	
	* Fig	
	* Pear	
	* Persimmon

## Starbrew Valley
* Rebalanced gift taste values;
	* After seeing Shane & Pam's respective events talking about sobriety changes the gift preference of alcohol to dislike/hate;	
	* Items such a `Tonic Water` and `Seltzer Water` are now universally disliked	
	* Leo now hates alcoholic beverages;	
	* Lewis now really hates `The Mayor's Shorts` drink (-80 friendship points);	
	* Marie dislikes `The Mayor's Shorts` drink;	
	* Penny dislikes alcoholic beverages;

## Tailor Mouse
* Added a letter background for the MFM component

<details>
<summary> Planned Features</summary>

If I ever get motivation to come back or have to fix a major bug these are planned things I have to remove for this release:

#### All Packs (Excluding BAGI & Tailor Mouse)
* Add in BAGI icons for new items;
* Continue working on gift tastes to balance them and make them more diverse;
* Unique dialogue for certain gifts

#### Artisan Valley
* 3 New Items
* New Machine w/Items

#### Christmas Sweets
* Festive winter letter background

#### Even More Recipes
* 10 New Recipes

#### Fresh Meat
* 2 New Recipes

#### Fruits and Veggies
* New Crops

</details>

<details>
<summary> This happened at some point in the past...</summary>

## Artisan Valley
* Adds Turkish translation;
* Updates French translation;

## Christmas Sweets
* Adds Turkish translation;
* Updates French translation;

## Even More Recipes
* Adds Turkish translation;
* Fixes error in Strawberry Cheesecake recipe;
* Updates French translation;

## Fantasy Crops
* Adds Turkish translation;
* Updates French translation;

## Farmer to Florist
* Adds Turkish translation;
* Adds French translation;

## Fresh Meat
* Adds Turkish translation;
* Adds Russian translation;
* Adds new items obtained with MYC;
* Fixes error with Ostrich Seeds unlock requirement;
* Updates French translation;

## Fruits and Veggies
* Adds Turkish translation;
* Updates French translation;

## Mizus Flowers
* Adds Turkish translation;
* Updates French translation;

## Mizus Flowers - Color Mania
* Adds Turkish translation;

## More Recipes
* Adds Turkish translation;
* Updates French translation;

## More Trees
* Adds Turkish translation;
* Updates French translation;

## Starbrew Valley
* Adds Turkish translation;
* Adds Russian translation;
* Adds French translation;

## Tailor Mouse
* Adds Turkish translation;

</details>

<details>
<summary> Inital 1.5 Commit - Spoilers</summary>

The following contains spoilers for 1.5 content. Read at your own risk.

## BAGI PPJA - Default Icon Pack
* Adds sprites for mango, pineapple, taro, banana, and Qi fruit;

## BAGI PPJA Icon Pack
* Removes sprites for mango, pineapple, paddy taro, banana, and ginger;

## Artisan Valley
* Removes Ginger Ale;
* Removes producer rule for wheat flour from the grinder;
* Tweaks the input for Umeshu;
* Sprites updated;
* New recipes;

## Christmas Sweets
* Adds mail flag requirement to Gingerbread House & Decorated Gingerbread Man;

## Even More Recipes
* Adds mail flag to recipes requiring pineapple, mango, taro, banana, and/or ginger;
* Sprites updated;
* New recipes;

## Fantasy Crops
* Updates Hungarian translation;

## Farmer to Florist
* Adds Hungarian translation;

## Fresh Meat
* Removes Dragon Tooth;
* Adds Ostrich crop & associated objects;
* Support for new critters added to PFM Fresh Meat for Bug Net;
* Adds mail flag to recipes requiring pineapple, mango, taro, banana, and/or ginger;
* Sprites updated;
* New recipes;

## Fruits and Veggies
* Removed paddy taro & pineapple;
* Ginger is still able to be grown but produces the forage item;
* Ginger seed cost reduced to 35g & changes it to a summer crop;
* Mail flag added to ginger crop;
* Changes the kiwi product sprite;

## More Recipes
* Removed Banana Pudding & MFM entry;
* Adds mail flag to recipes requiring pineapple, mango, taro, banana, and/or ginger;

## More Trees
* Removes Banana and Mango;
* Fixed minor sprite errors on the Ume Tree sprite

## Starbrew Valley
* Removes Pina Colada & MFM entry;
* Adjusted MFM letters based on new item unlock requirements;
* Adds mail flag to recipes requiring pineapple, mango, taro, banana, and/or ginger;

## Tailor Mouse
* Tailor Mouse got a face lift;

## General Changes (applies to all packs)
* Added support for Expanded Preconditions Utility: This should help clean up menus slightly if not using something else to redistribute things;
* Added French and Hungarian translations;
* Removes `PurchaseRequirements: null` for items where it applied;

Assets used/used as a base have been purchased from the following:
- https://artoftic.itch.io/pixelart-16x16-fooddrinks
- https://pixeltier.itch.io/pixeltiers-food-rpg-icon-set
- https://cyangmou.itch.io/pixel-art-food-cooking-1616

</details>