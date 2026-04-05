<iframe style="max-width: 100%;" width="560" height="315" src="https://www.youtube.com/embed/lbTG2NYnzPQ?si=t-wcpn5rBrQHlrW_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

The Pokéwalker is a pedometer accessory for Pokémon HeartGold and SoulSilver. See [Dmitry Grinberg's article](https://dmitry.gr/?r=05.Projects&proj=28.%20pokewalker)  for information on data stored on the Pokéwalker.

### Pokéwalker Data
Observations from looking at my own Pokéwalker data dumps:
1. Held item data is not showing as anything other than 0 (no held item). This means one of the following is true:
	1. The Pokéwalker EEPROM Editor doesn't show held item correctly
	2. That data isn't saved correctly to the Pokéwalker
	3. The Pokéwalker only cares to save some specific held items
2. Spinda data isn't stored in the PokemonSummary struct under variantAndFlags.

### Pokéwalker Connectivity
In order to connect a HeartGold or SoulSilver game to a Pokéwalker, the following must match between the game trying to connect, and the game that previously successfully connected to the Pokéwalker:
1. Version
2. Region
3. Trainer ID and Secret ID
4. Pokémon Species sent off to the Pokéwalker
5. Pokémon Form sent off to the Pokéwalker
If any of these do not match, the game will fail to connect to the Pokéwalker.

### Pokéwalker Save Structure
The data related to the Pokéwalker is stored at 0xE5DC/0x4E5DC in the game's save data. The Pokémon that is sent to the Pokéwalker is stored at 0xE5E0/0x4E5E0. The game also stores a unique Pokéwalker ID stored at 0xE6D8/0x4E6D8 that is generated on game start, however this ID is not used to verify Pokéwalker ownership and seems to get accidentally deleted at some point. Thank you to Mow for helping me find this data.