<iframe style="max-width: 100%;" width="560" height="315" src="https://www.youtube.com/embed/h86ThpCNkKk?si=DEH5rMjIcu1X1iix" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

The Nintendo DSi systems can bypass time travel protections in the Generation 4 Pokémon games. By formatting system memory, you can modify the system’s RTC offset and skip any amount of days.

When you format system memory, the current system date is used as the basis for your new RTC offset. The DSi subtracts your newly set system date and time from midnight on the date the formatting was initiated. For example, let’s say you initiated a format on 1/1/2008 at 7:59 PM and set the new date and time as 1/2/2008 at 12:00 PM. The DSi would calculate the difference between 1/2/2008 12:00 PM and 1/1/2008 at 12:00 AM in seconds and set it as the new RTC offset. We can use this knowledge to trick the Generation 4 Pokémon games.

### Approach #1: Offset 0

This approach ensures our offset is always 0.

Example: 110 Day Bagon Skip

1. Set system date 1/1/2008
2. Format system memory to 1/1/2008 at 00:00 (RTC offset is now 0 seconds)
3. Save in game. Time travel protections are now in effect for 24 hours, unless your previous save’s RTC offset was also 0
4. Set system date to 1/3/2008
5. Format system memory to 1/3/2008 at 00:00. At this point, time travel protections have worn off
6. Make sure the proper area(s) are in place in the Safari Zone and save
7. Set system date to 4/22/2008
8. Format system memory to 4/22/2008 at 00:00 (110 days traveled while RTC offset remains 0)
9. Go back in game and save to lock in the upgrades

### Approach #2: Offset Equals Days Skipped

This approach sets our offset to the amount of days we want to skip.

Example: 110 Day Bagon Skip

1. Set system date to 1/1/2008
2. Format system memory to 4/20/2008 at 00:00 (RTC offset is now 9504000 seconds, or 110 days)
3. Save in game. Time travel protections are now in effect for 24 hours, unless your previous save’s RTC offset was also 9504000
4. Format system memory to 8/8/2008 at 00:00. At this point, time travel protections have worn off
5. Make sure the proper area(s) are in place in the Safari Zone and save
6. Format system memory to 11/26/2008 at 00:00 (110 days traveled while RTC offset remains 9504000)
7. Go back in game and save to lock in the upgrades

## Honey Trees

While Honey Tree encounters expire 24 hours after slathering, we can still speed them up with the DSi by waiting a bit before time traveling. Note that Honey Trees can still progress under the time travel penalty. Here’s an example with Approach #2:

1. Format system memory to the current system date at 23:59
2. Load the game, wait 2 minutes, slather the honey tree, and save
3. Format system memory to the new current system date (one day later than previous date) at 23:59
4. Load the game quickly and mash A to get the honey tree encounter

By doing this, we are traveling slightly less than 24 hours while keeping the RTC offset the same. Video example:

<iframe style="max-width: 100%;" width="560" height="315" src="https://www.youtube.com/embed/giRse4LPSEw?si=Dhh7hSEHdqiq_oh4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

---

Support me on [Patreon](https://www.patreon.com/c/Etchy) and [YouTube](https://youtube.com/etch) ❤️
