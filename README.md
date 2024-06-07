## Thank you Svelte Society!

- I am so proud, thank you so much Svelte Society!
- I'll now fix the bugs i've been catching and keep developing the project, since the hackathon is done!
- Pull requests, contributions or thoughts are all welcome!



## Starting Screen

<img src="https://wjfywtvnvjbposklgxzj.supabase.co/storage/v1/object/public/readme/entry.jpg" alt="UI of the Game" width="600">

- Game planning screen can be seen on top.
- There is just 1 stable world type to play for now, but other starting conditions and world types will be added with time.

## Play Your Own Story | A simple storytelling footage from the game:

<img src="https://wjfywtvnvjbposklgxzj.supabase.co/storage/v1/object/public/readme/main.jpg" alt="UI of the Game" width="600">

- "Chad-Rpg" is an interactive role playing game, where you are the player and Artificial Intelligence is the storyteller of the game.
- You'll give your own choices to events throughout the game, and then, AI will shape the story based on your choices (and combat success).
- Possibilities are endless; player can fight with creatures, wonder around the world, or just chill and meet a great friend at the tavern without choosing combat in his/her play time.

### Interactivity At Its Finest!

- Player can write his/her own answer into input too. Input box can be seen at the top, with a placeholder.
- This only works if player got any interactive chat points left. They can be bought from potion shops or some merchants. (I changed placeholder after this implementation, so the above images do not have that.)
- Note: Game can get buggy if player writes something so out of context.

## Combat UI

<img src="https://wjfywtvnvjbposklgxzj.supabase.co/storage/v1/object/public/readme/combatui.jpg" alt="UI of the Game" width="600">

- When enemies are ahead, choice ui will change, and player will be asked to select an action item or spell from the inventory/spells.
- Then, player will throw a dice. Dice will be between 1 and 20 if the choosen item is a weapon, but will be between 1 and 23 if the choosen item is a spell; and combat story will be calculated based on the damage/healing of the selected item and the dice number, plus, some element of surprise sometimes.

<div style="display:flex; justify-content:space-around;">
<img src="https://wjfywtvnvjbposklgxzj.supabase.co/storage/v1/object/public/readme/combat2.jpg" alt="UI of the Game" width="400">
<img src="https://wjfywtvnvjbposklgxzj.supabase.co/storage/v1/object/public/readme/combat3.jpg" alt="UI of the Game" width="400">
</div>

- Player threw 9/20 on the top left image, and the response came from server (so chatGPT) in a moment, based on the damage and the dice score.
- At the picture on the right, combat outcome (server response) can be seen in story box & hp/mp differences.

## Shop UI

<img src="https://wjfywtvnvjbposklgxzj.supabase.co/storage/v1/object/public/readme/shopui.jpg" alt="UI of the Game" width="600">

- Player can buy items, spells and potions from seller npcs using earned gold.

## Loot UI

<img src="https://wjfywtvnvjbposklgxzj.supabase.co/storage/v1/object/public/readme/lootui.jpg" alt="UI of the Game" width="600">

- There can be lootables after a successful combat, an example can be seen on top.

## Technologies Used

- Sveltekit as the fullstack framework
- gemini-pro as the LLM
- Supabase as the database
- Midjourney for the background generations

## Miscellaneous

- Backgrounds are changing automatically according to characters places to give more of the ambiance.
- A tavern/medieval vibish song can be played with a click, it uses html5 audio for now so it does not seemlessly looping but it will be seemlessly looping itself with the power of the web audio api when i implement it. The song is "Tavern Loop One" from Alexander Nakarada.

