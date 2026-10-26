idea #1 Fitness Progress Tracker & Workout Planner
idea #2 Fantasy RPG Shop Simulator
idea #3 Smart Home Energy & Bill Estimator

i chose Idea 2: The Fantasy RPG Shop Simulator. It is highly customizable, scales well, and separates logic cleanly between the player's choices and the shopkeeper's rules.

• What will your program do?
The program simulates an interactive market stall in a fantasy video game. The user interacts with an NPC shopkeeper to purchase gear. The program validates whether the user can afford the item and whether their character 
class is allowed to wield it.

• Who might use it or enjoy it?
Text-based gaming enthusiasts, RPG fans, and programmers looking to understand how inventory and economy systems function behind the scenes in game development.

• What information will the user enter?
	1. heroClass (e.g., "Mage", "Warrior", or "Rogue" to determine item compatibility.
	2. startingGold (e.g., 150) to set the user's budget.
	3. itemChoice e.g., 1, 2, or 3 selected from a displayed shopping menu.

• Which variables and data types will you need?
	• String heroClass To store the user's RPG class role
	• int startingGold To track user's purchasing power
	• int itemChoice To capture the menu selection
	• double taxRate or double discount To introduce a second data type for calculating final transactional costs
	• String itemName and int itemCost Fields managed inside the secondary ShopKeeper or Item class
