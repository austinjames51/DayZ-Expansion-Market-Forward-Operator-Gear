# DayZ-Expansion-Market-Forward-Operating-Gear
Market files for DayZ Expansion Market using Forward Operator Gear

You need the following mods for this to work: DayZ-Expansion-Market or DayZ-Expansion-Bundle which includes DayZ-Expansion-Market. 

STEPS: 
  1. Drop the Market JSON files into your \profiles\ExpansionMod\Market folder. The JSON files are Categories that appear on each Trader.
  2. You will want to go in and change the prices of these items as they do not reflect the quality of each item. They are just there for reference. 
  3. This your preference on which traders you want these categories to appear. But if you wanted them to appear on your Clothing Trader:
      A. Navigate to \profiles\ExpansionMod\Traders folder. 
      B. Open the Clothing.json file and add the following lines under the "Categories" section:
      
      "FOG_Bags",
      "FOG_Belts",
      "FOG_Gloves",
      "FOG_Helmets",
      "FOG_Masks",
      "FOG_Misc",
      "FOG_NVG",
      "FOG_Pants",
      "FOG_Patches",
      "FOG_Pouches_and_Accessories",
      "FOG_Shirts",
      "FOG_Shoes",
      "FOG_Vests"
      
It could look something like this:
      
"Categories": [
        "Blouses_And_Suits",
        "Boots_And_Shoes",
        "Coats_And_Jackets",
        "Pants_And_Shorts",
        "Shirts_And_TShirts",
        "Skirts_And_Dresses",
        "Sweaters_And_Hoodies",
        "FOG_Bags",
        "FOG_Belts",
        "FOG_Gloves",
        "FOG_Helmets",
        "FOG_Masks",
        "FOG_Misc",
        "FOG_NVG",
        "FOG_Pants",
        "FOG_Patches",
        "FOG_Pouches_and_Accessories",
        "FOG_Shirts",
        "FOG_Shoes",
        "FOG_Vests"
],

