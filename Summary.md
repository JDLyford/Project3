Create a RPG using Google Maps API

The user will create an account to start off with in order to track progress
-The account will require a Username and Password along with a Postal Code
--Postal Code will be used as the starting point for the User's character

##############################################################################################################################################
Basic RPG Elements and Ideas
##############################################################################################################################################

Being in a typical roaming RPG format the user's character starts at level 0 with all skills set at 0 experience
The goal is to level up skills in order to be more effective at exploring and expanding
-Exploring is done by moving a set amount, based on Scouting skill, on the map
-As the user explores the gain experience in Scouting and based on their location they can access different features
--Features based on the map may include: Fishing at lakes, Study at Schools, Research at Libraries, and many more
--By leveling various skills the user can access unique items and locations
---The items gained from skills can be used for Status aliments, Trading, or other Skills
---The locations unlocked can offer special interactions, trades, and guilds

After the user persues a path they can choose to join a guild or party to interact with
-Guilds can have a unique area to communicate and build on
--Buildings can give members boosts or offer unique items when levels or goals are met
--Members can help one another to level through bonuses

Inventory and Equipment management will be a key part of gameplay
-Users have a limited backpack that can be accessed from anywhere
-Users will also have access to a external storage source such as a bank and/or house
-Users will also have a shared storage if part of a guild to add, donate, or pull from/to

While Exploring Users can engage in Combat
-Combat is optional but is required in order to use certain equipment
--Combat can be done between players either privately or in designated zones/ arenas
--There may be various forms of combat styles such as ranged, magic, melee

##############################################################################################################################################
Possible Page Layout and Features
##############################################################################################################################################

Main Page will be the Sign-on/up with basic information about the game

First Page will be the Exploration Page
-Small summary of main stats and status on the side
-Map with possible actions in the middle or opposite side
--Explore/Move, Investigate/Use, Information
-Brief Inventory Display that can be expanded and interacted with
--Displays Usable Items in a single line table
-Tabs/Buttons along the top to redirect to other Pages
--Tabs: Current Page, Guild Page, Profile Page, Information/Event Page

##############################################################################################################################################
The Map and Actions
##############################################################################################################################################

The user can Explore using the Google Map and access features based on nearby buildings and areas
-If the user is within an area with a/an:
--Shop a button will apear to create an area where they can Trade items with NPC
---Differents shops can offer different items based on location
--School a button will allow them to Study Active Skills
---Depending on Grade Level the user will level differently
--Library a button will allow them to Research Passive Skills
--Normal Building a button will appear letting them investigate farther
---Random special encounters or events can occur here

##############################################################################################################################################
The API Usage
##############################################################################################################################################

When using the Map to explore and generate loactions to interact with they should be different while also allowing users all over the world to have and equal opportunity
-The API will show information such as: Name, Location, Rating, Type
--The Name will be pulled into the interaction as the Name of the Location or Building
--Location can determine various limitations or changes to make areas more unique
--Ratings can influence quality and limitations 
--Type will be used to identify what the user can do

##############################################################################################################################################
Possible Addition Technologies to Use
##############################################################################################################################################

Frontend:
-Handlebars: Templating/HTML generation
-Bootstrap: Basic CSS styling

Backend:
-Firebase: Authentication
-Sequalize/MySQL: Creating Tables for information Storage 

