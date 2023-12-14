Seems to be there to stay at https://modthesims.info/d/670511/greatly-extend-lot-opening-hours-the-city-that-never-sleeps.html (*Hopefully*. Who knows by now. I certainly don't.), but the mod is popular and important enough for Sims 3 culture that I'm backing up this mod too.
# Original description
Is your Sim known to head outdoors around 5 in the morning to experience the town life, only to find that pretty much only the diner, gym, and library were open? Fear no more. Now your towns will experience the true metropolitan around-the-clock life.<br>
<br>
I am new to S3PE XML stuff (Learned about it on 30th of August 2022, 3 days before I submitted this for upload), and completely new to XML tuning mods, such that I had to look at other such mods to figure out what the package filetree should look like.<br>
<br>
Times below are given in 24-hour notation.<br>
<br>
———This mod's custom values———<br>
Open 24/7: Bistro, Sports bar, Local watering hole, Dive bar, Fusion lounge, Vampire lounge, Exclusive lounge, Dance club, Disco club, Poolside club, Pet store NPC, Festival food stand NPC, Supernatural hangout, Rebel hangout, Nerd shop, Arcade, Java hut, Student union, Future bar, Gallery shop, Late Night bartender<br>
07:00 - 06:00 (23/7): Coffeehouse<br>
09:00 - 08:00 (23/7): Live show venue<br>
12:00 - 11:00 (23/7): Private venue<br>
01:00 - 23:00 (22/7): Ice cream truck<br>
05:00 - 03:00 (22/7): Festival ground, Consignment register NPC<br>
06:00 - 23:00 (17/7): Stylist NPC, Tattoo artist NPC<br>
08:00 - 00:00 (16/7): Showtime venue proprietor NPC<br>
12:00 - 03:00 (15/7): Plumbot competition arena<br>
Weekdays 17:00 - 03:00 (10/7), weekends 12:00 - 03:00 (15/7): Theater<br>
Thursdays 12:00 - 03:00 (15/1): Late Night movie set screenings<br>
<br>
———Default values———<br>
05:00 - 01:00 (20/7): Java hut<br>
06:00 - 01:00 (19/7): Rebel hangout, Student union<br>
06:00 - 24:00 (18/7): Coffeehouse<br>
07:00 - 01:00 (18/7): Gallery shop<br>
08:00 - 02:00 (18/7): Nerd shop<br>
09:00 - 03:00 (18/7): Future bar<br>
10:00 - 04:00 (18/7): Arcade<br>
10:00 - 03:00 (17/7): Supernatural hangout, Live show venue<br>
11:00 - 03:00 (16/7): Local watering hole, Sports bar, Dive bar<br>
12:00 - 04:00 (16/7): Late Night bartender<br>
08:00 - 21:00 (13/7): Festival ground<br>
12:00 - 01:00 (13/7): Private venue<br>
11:00 - 23:00 (12/7): Bistro<br>
14:00 - 02:00 (12/7): Fusion lounge, Vampire lounge, Exclusive lounge<br>
08:00 - 19:00 (11/7): Stylist NPC, Tattoo artist NPC<br>
10:00 - 21:00 (11/7): Showtime venue proprietor NPC<br>
17:00 - 04:00 (11/7): Poolside club, Disco club, Dance club<br>
09:00 - 18:00 (9/7): Consignment register NPC, Pet store NPC<br>
12:00 - 21:00 (9/7): Plumbot competition arena<br>
10:00 - 18:00 (8/7), summer 10:00 - 21:00 (11/7): Ice cream truck<br>
Weekdays 17:00 - 21:00, weekends 12:00 - 16:00 (4/7): Theater<br>
Thursdays 12:00 - 16:00 (4/1): Late Night movie set screenings<br>
<br>
———Files in GameplayData.package that have been changed———<br>
• Bars<br>
• Bistro_0xedc49f7547539dd4<br>
• IceCreamTruckManager_0xa86cf4492539f402<br>
• NpcRoles<br>
• ShowVenue_0xc08b72ec427dfeff<br>
• Venues<br>
• ServoBotArena_0xf5c574250d3bcbfe<br>
• Bartending_0x548c92b27a7193d4<br>
<br>
Conflicts could occur with other override mods who also edit any of the same files. This includes, but are not limited to, *[BlackCat007's Cooking & Ingredients Overhaul](https://modthesims.info/d/479345/13-04-blackcat007-s-cooking-amp-ingredients-overhaul-compatible-with-patch-1-63-1-67.html)*, *[What's on the menu?](https://modthesims.info/d/498764/what-s-on-the-menu.html)*, *[All Bars Serve All Drinks](https://modthesims.info/d/469239/all-bars-serve-all-drinks.html)*, and *[Longer Equestrian Center Hours](https://modthesims.info/d/460162/longer-equestrian-center-hours.html)*.<br>
<br>
———Notes———<br>
• The theater was very, very tricky to figure out. If the weekday start time was set to 16:00 or earlier, it would instantly close again at that time. Tickets could not be ordered later than 03:00 even if the show duration was set to more than 12 hours (17 on weekends). And despite what the "ShowVenue" XML file claims, weekends only have the matinée, and does not have both matinée and evening shows.<br>
• Showtime benches and tables are replaced with standing areas when a SimFest or Showtime concert begins, and are only added back when a venue is closed. As such, lot types where it was probable that a Showtime stage would be, could not be open 24/7.<br>
• It was very tempting to add a 3rd stadium matchday on Fridays, but I was worried it'd be seen as unwanted interference in the Professional Sports career.<br>
• It did not seem possible to choose more than 1 day for the Late Night movie set screenings. They do however seem to apply theaters' weekend hours.<br>
• From what I can determine, all new times are the same for Bridgeport and for other worlds.<br>
• The NPC staff of some cash registers, most often the comic book register, does not freeze most needs for the NPC cashier, and they have been known to faint and to wet themselves during prolonged cashiering.<br>
• Starting with v1.4, there will not be further separate non-Bars gamemod versions. Instead, concerned players can open the downloaded mod in S3PE, delete the Bars file with the Del key, and then save the .package file. Easier than it may sound.<br>
<br>
———Changelog———<br>
• 9th of November 2023: Extremely major hotfix for festivals, with the times now being the correct 05:00-03:00 instead of the accidental 03:00-05:00.<br>
• 31st of October 2023: Major hotfix for festivals, as I realised a couple years late that the season changes are done at 04:00 and that Sims on the lot at that time gets sent instantly back home. As such 07:00-06:00 have been changed to 03:00-05:00. Also fixed an oversight where Future Lounge was 10:00-08:00 instead of 24/7, and fixed an old report by reducing the amount of ice cream vans (when not using NRaas Traffic) from 2 to 1.<br>
• 23rd of February 2023: Applying the "Changelog" tab on the Mod the Sims page. The mod itself is unchanged.<br>
• 28th of January 2023: After finally having found the correct tuning value for bartender hours, they are now bartending considerably longer in v1.2.<br>
• 8th of January 2023: Extended the plumbot competition arena opening times in v1.1.<br>
• 8th of September 2022: Initial release.
