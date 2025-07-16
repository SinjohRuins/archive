<iframe style="max-width: 100%;" width="560" height="315" src="https://www.youtube.com/embed/hN-unKIkA8g?si=qfaRpcsTqa5umy8C" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

In Pokémon Diamond, Pearl, and Platinum, many factors are taken into consideration when the game determines if it should generate a wild Pokémon encounter. In order to generate an encounter, (both of) two randomly generated integers from 0–99 must be lower than their respective “encounter success rates” (ESRs), which correspond to percentage chances.

For instance, if the randomly generated numbers are 20 and 50, but the ESRs were 30 and 40, respectively, an encounter would not be generated because, although 20<30, 50>40. If, instead, the second value was 35, an encounter would be generated because both 20<30 and 35<40.

In this example, the game had an effective 12% chance of generating an encounter: the chance that both randomly generated numbers were lower than their respective ESRs was 30% × 40%.

When ESRs are modified, any would-be non-integer value is rounded down. For example, if White Smoke is active, the first ESR is halved; if the first ESR was 35, instead of performing further modifications on 17.5, the ESR becomes 17.
## First Encounter Success Rate

The first ESR is derived from the location at which your character is currently (then modified, if necessary; see below). Typically, tall grass has an encounter rate of 30, while caves and surfing have an encounter rate of 10. Below are the base encounter rates for Diamond, Pearl, and Platinum for locations that deviate from this typicality:
### Diamond and Pearl Encounter Rates

|Location|Rate|
|---|---|
|Great Marsh|35|
|Great Marsh (Surfing)|15|
|Lost Tower|10|
|Mt Coronet (4F Floor 3, 5F, and 6F)|15|
|Old Chateau|10|
|Old Chateau (Gengar Room)|15|
|Route 219, 220, 223, 226, 230 (Surfing)|20|
|Snowpoint Temple (First Room)|15|
|Solaceon Ruins (Dead End Rooms, B1F)|15|
|Solaceon Ruins (Dead End Rooms, B2F)|20|
|Solaceon Ruins (Dead End Rooms, B3F)|25|
|Solaceon Ruins (Dead End Rooms, B4F)|30|
|Turnback Cave|15|
|Victory Road|15|
### Platinum Encounter Rates

|Location|Rate|
|---|---|
|Great Marsh|35|
|Lost Tower|10|
|Mt Coronet (4F Floor 3, 5F, and 6F)|15|
|Old Chateau|10|
|Route 227 and 228|10|
|Snowpoint Temple|5|
|Trophy Garden|10|
|Turnback Cave|15|
|Victory Road (Cave and Surfing)|15|
## First ESR Modifiers, Abilities

|Ability|Modifier|
|---|---|
|No Guard, Arena Trap, Illuminate|x2|
|White Smoke, Quick Feet, Stench|x0.5|
|Sand Veil (In Sandstorm)|x0.5|
|Snow Cloak (In Snow)|x0.5|
## First ESR Modifiers, Flutes

|Flute|Modifier|
|---|---|
|White|x1.5|
|Black|x0.5|
## First ESR Modifiers, Held Items

If the Pokémon in the first slot of the party is holding the Pure Incense or Cleanse Tag, the ESR will be multiplied by two-thirds.
## Low Encounter Rate Tiles

Before calculating the second ESR, the game checks the number of combined steps and turns the player commits on tiles that can generate encounters. If this number is less than 8, the game generates a number between 0 and 99, then checks if the result is lower than 5. If it is greater than five, the game will not generate an encounter. If the result is lower than 5, or if you’ve taken 8 or more steps and turns on tiles that can generate encounters, the second ESR is calculated. This step/turn counter is reset when loading into an area.
## Second Encounter Success Rate

The second ESR is always set to 40, then modified accordingly:
## Second ESR Modifiers, Long Grass and Bicycle

If your character is in long grass or if your character is riding a bicycle, the second ESR is increased by 30.
## Second ESR Modifiers, Date

If you are playing on one of the following dates, the second ESR is modified accordingly:
### Diamond and Pearl

|Date|Modifier|
|---|---|
|January 1 \| March 21 \| August 6, 9 \| September 11 (JPN Only), 23|-10|
|August 13, 14, 16 \| November 3 \| December 25, 31|-5|
|January 6, 11 \| February 3, 11, 12 \| March 3, 17, 25 \| April 1, 25, 29 \| May 3, 5, 8, 29 \| June 2, 21 \| July 4, 14, 24 \| August 15, 28 \| September 15, 20 \| October 3, 12 ,30 \| November 1, 11, 16 \| December 6, 8, 23, 24|+5|
|January 12 \| July 7|+10|
### Platinum

|Date|Modifier|
|---|---|
|January 1 \| March 21 \| September 23|-10|
|April 26 \| August 13, 14, 16 \| November 3 \| December 31|-5|
|January 11, 29 \| February 3, 11 \| March 3, 18 \| April 1, 25, 29 \| May 3, 5 \| June 21 \| July 18, 24 \| August 15 \| September 7, 12, 15, 20, 28 \| October 5, 15, 30 \| November 12, 21 \| December 14, 23|+5|
|January 12 \| February 27 \| July 7|+10|

---

Support me on [Patreon](https://www.patreon.com/c/Etchy) and [YouTube](https://youtube.com/etch) ❤️
