<iframe style="max-width: 100%;" width="560" height="315" src="https://www.youtube.com/embed/hmS6VVGXCYM?si=Crqf8Z5Mw_e0BoSx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

Honey Trees and Berry Trees in Pokémon Diamond, Pearl, Platinum, Brilliant Diamond, and Shining Pearl are impacted by a bug/glitch/oversight that can create seemingly random delays to your Honey Tree encounters spawning or Berry Trees sprouting.

Note that other features in Generation 4 also use this same sort of timer (ex: the time travel penalty timer), but I'm still doing more research to thoroughly check all timing systems.

Normally, a Honey Tree encounter will spawn between 21,541 seconds (5 hours, 59 minutes, and 1 second) and 21,600 seconds (6 hours, 0 minutes, and 0 seconds). This is due to the way this sort of timer works. This timer is constantly running in the background, and typically performs an update every minute. Since you do not know where this timer is currently at when you slather a honey tree, you'll automatically save anywhere from 0 to 59 seconds on it's overall run time.

When a timer update happens, all of these timers decrease by one, as they are an integer representing minutes remaining. This timer update cannot happen in battle, during loading screens/loading a save, and in menus.

Let’s say the game updates the timers and you immediately enter a battle. It takes you 1 minute and 30 seconds to complete this battle. As the battle ends, the game checks how much time has passed since the last update. Since at least a minute has passed, it updates the timers, then it will update them again after 1 minute passes. At some point in this timer update process, the seconds get dropped. As a result, the only thing that gets subtracted from our timers is the number of minutes that have passed. This means that it's very easy to accidentally create a seemingly random delay on this type of timer.

You can minimize this delay by forcing a timer update, then making sure you aren't in battle, in a menu, or loading another area during the next timer update (on exact minute intervals). For example, let’s say I start an encounter after the 2 minute 10 second mark on my stopwatch, then finish it around the 2 minute and 46 second mark. I cannot start another encounter, as the minute will roll over in the battle and seconds will potentially be lost. Instead, I wait until the stopwatch hits 3 minutes, then begin doing encounters again until we get close to the next minute. If done this way, you shouldn’t lose any time except for the time lost in the initial 1 minute encounter.

Thank you to TheMasterZelda for investigating this.

---

Support me on [Patreon](https://www.patreon.com/c/Etchy) and [YouTube](https://youtube.com/etch) ❤️
