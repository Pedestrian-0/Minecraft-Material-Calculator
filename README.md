# Minecraft-Material-Calculator
A Minecraft material calculator that turns a Litematica schematic into a full shopping list: raw resources, every crafting and smelting step, and the fuel you’ll burn.

# Short description
Minecraft Material Calculator takes the material list of a build (for example, 3,000 chiseled bookshelves) and works backward through the whole recipe chain. It tells you exactly how many raw materials to gather, in what order to craft and smelt the intermediate items, and how much coal, charcoal or other fuel the furnaces need.

# Key features
Imports Litematica material lists (CSV/TXT), with an option to use only the missing blocks
Resolves multi-level recipes (logs → planks → slabs → final block) with leftovers tracked
Smelting support with fuel estimates for coal, charcoal, lava buckets and more, plus smelt time across multiple furnaces
Inventory deduction: items you already own are subtracted, including intermediates
Options for wood type, blast furnace, stonecutter recipes, safety margin and build multiplier
Collection tracker and step checklist to follow your progress while gathering and crafting
Quantities shown in items, stacks, shulker boxes or double chests
Saves and loads projects, and exports reports as TXT or CSV

# Available as:
A Python command-line tool
A themed desktop GUI (dark and light) built with tkinter, no extra dependencies
A mobile-friendly web app for Android, installable from the browser
