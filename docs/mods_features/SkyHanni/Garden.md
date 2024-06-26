# Garden Features
## General Garden Features
### SkyMart
Shows Copper Prices inside SkyMart by the coin to copper ratio
- Higher Number is better for Profit
### Numbers
#### Crop Milestones
- Shows Crop Milestones in the Stack Size in the Desk Menu
#### Average Milestone
- Shows Average Crop Milestone level, Adds all, of them together then divides by the number of them, Max Average Crop Milestone is 46
- Unlike the other Features in this category, this does not have anything to do with stack size
#### Crop Upgrades
- Shows Crop Upgrades in the stack size of the Desk Menu
#### Composter Upgrades
- Shows Upgrades in the Stack Size of the Composter
### Custom Keybinds

Allows you to set different keybinds for most keys while holding a Farming Tool

- Allows rebinding the following controls

    Attack, Use Item, Move Left, Move Right, Move Forward, Move Back, Jump, and Sneak

    - Multiple keys on the same action are not allowed
### Farming Lane
<details>
<summary>How to Configure</summary>
- Go to the Start of your Farming Lane<br>

- Type /shlanedetection<br>

- Continue Farming until you pass two ends of the lane<br> 

- It should now be fully configured and notify you when you finish each lane<br>

</details>

#### Lane Switch Notification
- Displays a Sound when you're  X (customizable) seconds away from the end of the current lane
    - Supports Customizing Sound, Text, Repeat Duration (How often it repeats), and Pitch
#### Distance Display
- Displays a HUD element of how far away you are from the end of the lane
#### Corner Waypointss
- Shows the corner of the Lane as a waypoint of the current lane you're farming
### Garden Level
#### Display
- Displays a HUD Element for your Garden Level in the format<br>
     "Garden Level X (XP/XP To Level)" 
#### Overflow
- Changes various Garden Level Displays to show past the SkyBlock max level in the same scaling (10,000 per level past 15)
#### Overflow Chat
- Shows Messages for the previous feature each time you pass a milestone, 
### Farming Weight
- Farming Weight is a Calculation from "Elite Farmers" More info can be found on<br>
[Elitebots Website](https://elitebot.dev/info)
#### Display
- Adds a Display for your current Farming Weight
#### Leaderboard Ranking
- Shows your Leaderboard placement if you are in the top 10,000 Farmers on EliteBot
#### Overtake ETA
- Shows how long until you'll pass the next player , If you're below 10,000 it will show how long until you're tracked on the leaderboard 
#### Show LB Change
- Shows if you've lost positions upon entering garden while offline after entering the Garden, 
#### Always ETA
- Always show Overtake ETA even when not Farming in Garden
#### ETA Goal
- Allows you to Set a custo mnumber of position you want to track
#### Show below 200
- Shows your weight even if you're below position 200, by default it does not display.
#### Show Outside Garden
- Shows the Farming Weight display /outside the Garden

### Dicer RNG Drop Tracker
- Displays What Drops you've gotten with the Melon/Pumpkin Dicer, Like other Trackers it can be customized more from inventories, such as displaying only this Session or Total since mod install
#### Compact Format
- Changes the Display from Seperate rows for each Drops to a Colored X/X/X/X Format, taking less Vertical Space
#### Hide Chat
- Hides the messages from Dicers
### Money per Hour
- Shows the Money per hour of various Crops
#### Only Show Top
- Customizes how many crops on the list you see
#### Extend Top List
- Adds the current crop for the tool you're holding into the list, even if it's not in the top threshold set above
#### Always On
- Displays it even if you're not farming in Garden, this does not enable it outside Garden
#### Compact Mode 
- Hides the position and name of the crop (Still shows the Icon) to take up less Horizontal Space
#### Compact Price
- Compacts the price by rounding, EG 11,423,132 to 11.4M
#### Use Custom
- Allows you to set what the Money/H Defaults to (Eg: Sell Offer, NPC, Instasell)
#### Merge Seeds
- Merges the Wheat and Seed price together 
#### Include X
- Various Toggles to add profit from Bountiful, Mooshroom Cow, Armor Drops, Dicer Drops
#### Hide Title
- Hides the first line of the Money/H Display to compact it even further
### Next Jacob's Contest
#### Show Jacob's Contest
- Adds a HUD Element with what the next Jacob's Contest is
#### Outside Garden
- Shows the HUD Element outside garden
#### In Other GUIs 
- Shows the Jacob's Contest Display in other Farming GUIs
#### Fetch Contests
- If you haven't opened calendar, fetch the Contests from Elitebots API
#### Share Contests
- Allows you to share Contests to the Elitebots API so other people can use the previous feature without opening
#### Warning
- Displays a Warning for Upcoming Jacob's Contest
#### Warning Time
- Customize the amount of seconds before a Contest you're notified
#### Popup Warning
- Pops up with a window when the game is out of focus
#### Warn For
- Allows you to Customize which crops you want to look forward to
### Armor Drop Tracker
#### Enabled
- Tracks all drops you get from Armor
#### Hide Chat
- Hides the messages from farming armor drops
### Anita Shop
#### Medal Prices
- Shows the Price per Gold Medal in Anita's Shop (Higher is Better)
#### Extra Farming Fortune
- Adds Price and Current tier to the Anita Farming Forunte Upgrade
- Since the Anita Menu item disappears when it's maxed, it is not visible after that
### Farming Fortune Display
#### FF Display 
- Shows your Farming Fortune and Crop Fortune combined for the tool you're holding as a HUD Element
#### Farming Fortune Guide
- Shows possible farming fortune, and breaks down the ways you can get it for a specific crop, or global buffs, sorted by lowest price to highest
- Also visible by typing /ff
### Tooltip Tweaks
#### Compact Descriptions
- Compacts a lot of parts of the descriptions of tools, Shrinks T3 Hoes Description by ~20%
#### Breakdown Hotkey
- Allows to set a hotkey for a more detailed breakdown of the ways the tool gives you farming fortune
#### Tooltip Format
- Shows Crop-Specific farming fortune in the tooltip
- Unsure if this actually does anything since they added crop specific fortune as a stat
#### Total Crop Milestone
- Adds a progress bar to Max Milestone in the Crop Milestone Inventory
- Hypixel implemented this feature if you are past Milestone 20
### Yaw And Pitch
#### Enable
- Adds a HUD Element to show yaw and pitch, fades out without mouse movement
#### Precision
- Adds Precision to the Yaw/Pitch to allow you to get the exact position for farming
#### Show Without Tool
- Does not require a tool in your hand for the HUD Element
#### Show Outside Garden
- Allows it to be shown outside Garden
#### Ignore Timeout
- Stops it from timing out after not moving your mouse
### Sensitivity Reducer
#### Mode
- Lets you switch between off, holding keybind, or holding any farming tool
#### Reducing Factor
- Divides your Sensitivity by the amount Specified
#### Show GUI
- Adds a HUD Element to show if the feature is currently working
#### Only in Ground
- If you are not on the ground disable Sensitivity Reducer to allow mouse movement to behave as Normal
#### Disable in Barn
- If you're in the barn, disable Sensitivity Reducer to allow movement to behave as normal
### Crop Start Location
#### Enable
- Shows the waypoint for the start of the farming location if you're holding a farming tool
#### Crop Location Mode
- Allows selecting where the Waypoint will Display
- Choose between Last Farmed, and where it's set to start 
- "/shcropstartlocation" sets the starting location
### Plot Menu Highlighting
#### Enabled
- Highlights Plots based on their Status set below
#### Statuses 
- Select which status to display
- Options are "Pasting, Current Plot, Pests, Sprays, and Locked"
### Garden Plot Icon
- Allows you to select an item in your inventory to replace the Plot item for
- This is why you see the axe in the Bottom Right corner of the Plot Menu
- Also has a Reset Button
### Garden Commands
#### Warp Commands
- Adds secondary commands for hypixel commands for: "/home" for "/warp garden", "/barn" for "/plottp barn", and "/tp plot" for /plottp plot"
#### Hotkeys
- Allows you to set hotkeys for the previous warps stated that only work in garden
### Atomspheric Filter Display
#### Enabled
- Adds a display to show the currently active Atomspheric Filter Display
#### Only Show Buff
- Compacts it by not showing the current season, instead only showing the buff from the season
#### Abbreviate Season
- Abbreviates the season to compact it
#### Abbreviate Perk
- Abbreviate the perk it gives to compact it
#### Outside Garden
- Enables the Feature outside the Garden
### Plot Price
- Shows the Unlock price for plots in coins if the compost was bought from bazaar
### Fungi Cutter Warning
- Adds a title to warn you if you're breaking the wrong mushroom with the Fungi Cutter
### Burrowing Spores
- Displays when you drop a Burrowing Spore while farming mushrooms
### Wild Strawberry
- Displays a notification when you drop Wild Strawberry Dye
### FF for Contest
- Shows the Lowest farming fortune with your BPS rate that you need to get a medal
### Contest Time Needed
- Shows how long with your current farming fortune and BPS rate you need to farm for a medal
### Custom BPS
- Override BPS rate to the one set below
### Contest Summary
- Summarizes various stats on how you did during the Farming Contest
### Enable Plot Borders
- Shows Plot Borders when doing F3+G
### Copy Milestone Data
- Allows you to copy incorrect crop milestone data
### Logbook Stats
- Shows Stats on your Visitor Logbook

## Visitor Garden Features
### Visitor Timer

#### Visitor Timer
- Adds a HUD Element for how many visitors you currently have, and how long until the next one
#### Sixth Visitor Estimate
- Estimates when the "Sixth visitor" will be available, because the counter for the next visitor counts down even when it's full
#### Sixth Visitor Warning
- Adds a Title for when the Sixth Visitor is available
#### New Visitor Ping
- Adds a Title for when you are less than 10 seconds away from a New Visitor
- Useful for speedruns sucha s the Epheremal Gratitude Item

### Visitor Shopping List
#### Enable
- Shows the items that Visitors request
#### Only When Close
- Only show the Shopping List when you are near Visitors
#### Bazaar Alley
- Also show the Shopping List while in Bazaar Alley
- Useful for when you don't have a Booster Cookie
#### Farming Areas
- Shows the Shopping List while inside Farming Areas on public islands
- Useful for Early Game players, although since you can paste items with compacted forms, it might be better to farm on garden
#### Show Price
- Shows the price for the items on the Shopping List
#### Show Sack Count
- Shows how many items you already have in your Sack
#### Show Super Craft
- Shows a button to super craft items if you have a lower tier in your sacks
#### Item Preview
- Shows the items they could possibly request before talking to the visitor
### Visitor Reward Warning
#### Notify in Chat
- Sends a chat message of a detected special drop 
#### Show over Name
- Shows the special drop they're offering
#### Block Refusing Reward
- Prevents hitting the Decline Button unless you are holding the Bypass Key
#### Bypass Key
- Allows you to configure a key to press while declining/accepting the visitor to bypass the above setting
#### Items
- Allows you to select what items are prevented from being declined
#### Coins Per Copper
- With the Below options on, set a Coins Per Copper threshold
#### Block Refusing Copper
- Blocks refusing copper if it costs less than the threshold
#### Block Accepting Copper
- Blocks accepting copper if it's costs more than the threshold
#### Acceptable Coin Loss
- Allows you to set a max coin loss per visitor, settings above take precedent before this
#### Block Refusing Low Loss
- Stops you from declining a visitor with a lower loss than the threshold set above
#### Block Accepting High Loss
- Stops you from accepting a visitor with a higher loss than the theshold set above
#### Block refusing New Visitors
- Stops you from declining visitors you haven't served before
- Useful for the Green Thumb Enchantment
#### Opacity
- How strong of a grey the offer buttons show if they are blocked
#### Outline
- Adds a Red/Green outline around the option you should set according to the set features above
### Notification Chat
- Show in chat when a Visitor is visiting your Garden
### Notification Title
- Shows a Title when a Visitor is visiting your Garden
### Highlight Status
- Highlights or adds a Line under the name based on the Status of Visitors<br>
- Statuses are Waiting, New, Accepted, Declined. 
### Hypixel Message
- Hides the chat message that Hypixel sends when a new visitor arrives
### Hide Chat
- Hides the chat message responses from the garden
- Does not remove Beth and Spaceman messages\
### Visitor Drop Statistic Counter
#### Enabled
- Counts the rewardss from visitors and displays them as a HUD element
#### Text Formats
- Adds or removes Elements from the Visitor Drop Statistic Counter HUD element
#### Display Numbers First
- Choose if you want to display the amount obtained before or after the drop 
#### Display Icons
- Replaces the drop names with icons of the obtained item, also compacts the HUD element by taking less horizontal space
### Accept Hotkey
- Accepts a visitor when hitting the set key
### Highlight Visitors in SkyBlock
- Highlights NPC's that can be visitors outside of the Garden
### Block Interacting with Visitors
- Allows you to block clicking on certain visitors for Visitor Cycling
- Supports only blocking on Bingo

## Crop Milestone Garden Features

### Progress Display
- Shows a HUD for the Progress and ETA to the next Crop Milestone
- For full accuracy you need a Mathematical Hoe or the Cultivating Enchantment
### Overflow
#### Crop Milestone Display
- Shows Overflow levels in the Crop Milestone HUD Element
#### Best Crop Time
- Shows overflow Levels in the Best Crop Time Display (for overflow Average Crop Milestone)
#### Inventory
- Shows overflow levels as the stack size in the Crop Milestone Menu
- Also changes the Crop Milestone Average display to average overflow
#### Tooltip
- Shows overflow level progress in the tooltip in the Crop Milestone Menu
#### Discord RPC
- Shows overflow levels in the Discord Rich Presence feature
#### Chat
- Sends messages upon gaining an Overflow crop milestone level
### Warn When Close
- Warns 5 seconds before when the next Crop Milestone level will happen
### Time Format
- Changes the Highest time unit to show for the Crop Milestone Display
### Maxed Milestone
- Calculate progress to 46 instead of the next milestone
### Milestone Text
- Menu that allows Customizing the Crop Milestone HUD Element
### Block Broken Precision
- Adjust the decimals and precision shown by your Blocks per second Display
### Seconds Before Reset
- Adjusts the time before the Blocks per second reset
### Best Crop 
#### Best Crop Time
- Lists all the crops you have farming data with and sorts it by Skyblock XP or Garden XP
#### Sort Type
- Adjust between sorting between Garden and Skyblock XP
#### Only Show Top
- Shows the top amount of crops for the above setting
#### Extend Top List
- Adds the crop for the held tool to the List even if it's not in the top X
#### Always On
- Always show the Best XP Display while in the garden
#### Compact Display
- Compacts the Best Crop XP HUD display
#### Hide Title
- Hides the Title for the top Garden/Skyblock XP Display to compact it further
### Mushroom Pet Perk
#### Display Enabled
- Shows a HUD element for Mushroom while using Mushroom Cow Pet
#### Mushroom Text
- Allows adjustment of the Mushroom Pet Perk HUD Element
## Optimal Speed Garden Features
### Show On HUD
- Adds a HUD Element for the Optimal speed for your held tool
### Warning Title
- Warn via title when you are not using the set speed
### Rancher Boots
- Allows you to set the optimal speed in the Rancher Boots menu by clicking the preset
### Custom Speed
- Drop-down menu to customize the Optimal Speed for crops

## Composter Garden Features
### Composter Overlay
- Adds an overlay while in the Composter to show organic matter, fuel, profit, and 
### Overlay Price
- Select in between Instant Buy and Buy Order for the composter Overlay
### Retrieve from
- Chooses whether to retrieve materials from Sacks or the Bazaar by default
### Composter Display
- Displays Composter Data as a HUD Element
### Outside Garden
- Show the time until composter is empty outside the garden
### Composter Warning
- Warns when the composter is close to empty/is empty
### Upgrade Price
- Shows the price to upgrade the Composter in the tooltip
### Round Amount Needed
- Rounds the amount needed down so that you don't waste organic material/fuel due to the composter cap
### Highlight Upgrade
- Highlights upgrades that can be Currently bought
### Inventory Numbers
- Shows the amount of Organic Matter, Fuel, and Compost available
### Notification when Low Composter
#### Enable
- Shows a Notification when you are going to run low on  Composter supplies
#### Show Title
- Also show a title to notify the player
#### Min Organic Matter
- Adjusts the Organic Matter amount to notify on
#### Min Fuel
- Adjusts the Fuel amount to notify on
## Pests Garden Features
### Pest Spawn
#### Chat Message Format
- Changes how the Pest Spawn chat message is formatted
#### Show Title
- Shows a Title when a pest spawns
### Pest Finder
#### Display
- Shows a display with the pest locations known from tab/spawn messages
#### Show Plot in World
- Marks infested plot names in the world with a border around the plot
#### Plot Visibility Type
- Choose between showing the Name, or plot border, or both
#### Only With Vacuum
- Only show the Pest Display while holding a vacuum
#### Show For Seconds
- Adjust the timeout period for X seconds after no longer holding vacuum
#### Teleport Hotkey
- Allows a hotkey to instantly teleport to the nearest infected plot
#### Always Teleport
- Teleport even if you're currently in an infected plot
#### Back To Garden
- If you've vacuumed all pests, teleport to warp garden, or where your home is set
### Pest Waypoint
#### Enabled
- Shows the waypoint of where a pest should be
- Due to hypixel changing the logic, this is no longer an exact placement and just outlines where the particles point
#### Hide Particles
- Hides the particles the vacuum ability has
#### Draw Line
- Draws a line from the center of your screen to the Waypointn
#### Show For Seconds
- Make the waypoint disappear after X seconds
### Pest Timer
#### Enabled
- Adds a HUD Element for the time since last pest spawn
#### Only With Vacuum
- Only show the time since last pest spawn when you're holding a vacuum
### Pest Profit Tracker
#### Enabled
- Adds a HUD element for tracking the items you get while killing pests
#### Hide messages
- Hides the regular pest drop messages
#### Time Displayed
- Adjusts the time the Profit Counter is displayed after killing a pest
### Spray
#### Pest Spray Selector
- Adds a HUD Element to display what the pests are attracted to while holding a Sprayonator
#### Draw Plot Border
- Draw plot borders while holding the Sprayonator to show what you've sprayed already
#### Spray Display
- Adds a HUD Element to show the active spray and duration left of the plot you're currently in
#### Show If Not Sprayed
- Also make the HUD Element show if your current plot is not sprayed
#### Spray Expiration Notice
- Sends a notification when your spray is about to run out while in The Garden
### Stereo Harmony
#### Enabled
- Adds a HUD Element for what pest currently has increased odds from your Vinyl
#### Always Show
- Shows the display mentioned previously even when not farming
#### Show Pest Head
- Show a head on the HUD Element for the current pest being boosted
#### Show Crop Icon
- Shows the icons of the token crops from the boosted pest
#### Hide when None
- Hides the HUD Element when you do not currently have any vinyl selected