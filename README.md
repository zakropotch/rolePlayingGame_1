*Simple RPG game with locations, battles, shops, inventory, and win/lose conditions.*

**Breakdown**

xp, health, gold, currentWeapon - Track the player stats

fighting - Tracks if player is in combat

monsterHealth - Tracks current enemy health

inventory - Tracks player inventory

buttons 1-3 - Get button DOM elements

text - Get main text DOM element

xpText, healthText, etc - Get player stat DOM elements

monsterStats, monsterName, monsterHealthText - Get enemy stat DOM elements

weapons - Defines possible weapons

monsters - Defines possible enemies

locations - Defines locations, text, buttons


update() - Updates current location UI

goTown(), goStore(), goCave() - Change locations

buyHealth(), buyWeapon() - Shop functions

sellWeapon() - Sell weapons

fightSlime(), etc - Start battles

goFight() - Transition to fight scene

attack() - Player attack logic

getMonsterAttackValue() - Enemy attack logic

dodge() - Player dodge

defeatMonster() - Monster defeat logic

lose() and winGame() - Win/lose logic

restart() - Reset game state

easterEgg(), pickTwo(), pickEight() - Easter egg game
