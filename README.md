Download Link: https://assignmentchef.com/product/solved-cop2335-final-project
<br>
You have been hired by a Magic Gaming company to create a game called “Riders of Fortune”, which will be a text-based fantasy style board game. The game plays as follows:

You play Yarra, a young horseman in search of the of the illustrious Chalice of Knowledge, an artifact that will bring you everlasting wisdom.  The Chalice can only be found in a dragon dungeon after defeating the dragon.

Yarra, will have Experience Points (XP) that start at 0. He starts up with a knife (deals 2 damage to any monster) but can upgrade his weapon. He can also attack monsters and if he beats them, they will provide XP.

<strong><u>The Game Board:</u></strong> The game board will always be displayed on the screen as an array of characters.

Onscreen Map to Be Displayed:

P * * * * * * * * * * * * * * * * * * * * * * * * * * * * D




Mapping of spaces:

P 2 3 4 5 6 7 8 9 10 11 12 13 14 15 16 17 18 19 20 21 22 23 24 25 26 27 D

P: Corresponds to where the player is currently located (The player starts on space 1)

D: Corresponds to the last space, where the Dragon is

There are 28 positions on the board and the player starts in space 1. The player can only travel forward (higher numbers). The dungeon dragon is on space 28 marked with a D. The player obtains the Chalice if he can slay the dragon. You must keep track of the player’s current position and mark it on the onscreen map with P.

<strong><u>Player Movement:</u></strong>

You will provide the player with the following menu:

<ul>

 <li>Travel to another space on the board</li>

 <li>Dismount and explore the current space</li>

</ul>

If the player chooses option 1, a six-sided die will be rolled, and the player must move to that space(for an example, if the player is on space 2 and rolls a 5, the player would move to space 7).

If the player dismounts and explores the space, the following can happen:

<ul>

 <li>The player encounters a monster and must battle</li>

 <li>The player finds a new weapon</li>

 <li>The area is empty, no change.</li>

</ul>

<strong><u>Outcome 1: Fights a monster</u></strong>

During initialization, randomly choose 14 spaces that will have a monster. The monsters will have an HP of 3 to 7 (You can decide when defining the monsters).

The attack amount will be calculated by rolling a six-sided die plus the extra damage of the weapon being carried. If Yarra <u>fails to destroy the monster on the first attack he will die</u>.

If Yarra destroys the monster, he will gain XP of 2 per defeat.

<strong><u>Outcome 2:  Finds a new weapon:</u></strong>

There will be 5 weapons that can be found in the game. Each weapon will be allocated to a space. The weapon will give a modifier (an amount added to the result of the die roll).

<ul>

 <li>Crossbow: +3 on attack</li>

 <li>Flail: +4 on attack</li>

 <li>Broad Sword: +5 on attack</li>

 <li>Dragon Slayer: +6 on attack</li>

 <li>Spell of The Gods: +7 on attack</li>

</ul>

Have the program choose 5 random spaces that will contain the weapons <u>instead of</u> monsters (except for space 1, and 28).

If you find a weapon which has an attack higher than the weapon you are carrying, equip the new weapon. Otherwise keep the weapon you previously had.

<strong><u>Outcome 3: Area is empty:</u></strong>

Have the program choose 7 random spaces that will be empty (will no contain a weapon or a monster)

Display the following message:

<em>“There is nothing for you to do, so you reflect upon your adventures thus far. You take the time to train and enhance your reflexes”</em>

Your XP increases by 1.

<strong><u>Encounter: </u></strong>

If the player encounters a monster, the player must roll the die to obtain an attack value. The player’s weapon provides an additional attack value to the to the value of the die. If the player fails to kill the monster with the attack, the monster will destroy the player.

For example, if player rolls a 4 but they have a Broad Sword (+4), their total attack is 4 + 4 = 8

<strong><u>End Game:</u></strong>

If the player reaches spot 28 (by either rolling enough to get to 28 or rolling more than 28, the player will face the dragon only if his XP is equal to or higher than 8.

If he doesn’t have the XP required, the following message will display and end the game.

<em>“Alas, the dragon’s eyes stare at you and places you under his spell. You try to move but fail to do so and find yourself torched by the dragon’s fire. If only you had more experience, you could have seen it coming.”</em>

If the player does have the XP required, he will attack the dragon. The dragon will have an HP of 10. If he can kill the dragon, the following message will display:

<em>“Due to your cunning and experience, you have defeated the deadly dragon. Your quest has ended good sir. You’ve obtained the Chalice of knowledge and all of earth’s mysteries are revealed.”</em>

<strong><u>Additional Requirements:</u></strong>

<ol>

 <li><em>Make sure you always display the player stats ((XP) and Current Weapon).</em></li>

 <li><em>Make sure you display the result of the die roll</em></li>

 <li><em>Make sure you display the total attack.</em></li>

 <li><em>Make sure you display the HP of the monster you encounter.</em></li>

</ol>

<em> </em>