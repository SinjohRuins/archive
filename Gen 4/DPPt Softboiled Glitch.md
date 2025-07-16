The Softboiled Glitch in Pokémon Diamond, Pearl, and Platinum involves using Softboiled or Milk Drink on an injured Pokémon, then performing a frame perfect directional input immediately after pressing A. This allows you to perform one of the following actions, all centered on healing something you otherwise would not be able to:

- Revive a fainted Pokémon (normally not possible)
- Overheal a Pokémon (basically cosmetic, as it gets fixed when the Pokémon takes damage in battle)
- Heal an egg
- Crash the game by trying to heal the Back button

While overhealing a Pokémon, sometimes the game will cause an HP overflow, entering you into a seemingly endless heal loop that prevents you from performing any inputs.

![Screenshot of CasualPokePlayer posting in the Glitch City Research Institute Discord](https://publish-01.obsidian.md/access/7487b06ae9fdb09362ba4a44119d13a7/overflow.png)
> CasualPokePlayer: so say you overflowed your HP by 1, it will try to heal 65535 HP. it will eventually heal it (in around 73 minutes)

RETIRE found the cause of this glitch:
![Screenshot of RETIRE posting in the Glitch City Research Institute Discord](https://publish-01.obsidian.md/access/7487b06ae9fdb09362ba4a44119d13a7/softboiled-explanation.png)
> RETIRE: Except they did break. The issue is they had a switch case inside a switch case. Case 0 handles the initial selection. If you press A, it then has another switch case to check the state of the pokémon, and it breaks out of that one, but not the outer switch case so then it also ends up going through the check for holding a different button to select a different pokémon. so this is frameperfect

Thanks to [RETIRE](https://twitter.com/RETIREglitch) and CasualPokePlayer for your investigations.

Thank you also to YouTube commenter @nazberry6281 for bringing this to my attention!

---

Support me on [Patreon](https://www.patreon.com/c/Etchy) and [YouTube](https://youtube.com/etch) ❤️
