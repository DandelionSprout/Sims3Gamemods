Arguably the most severe glitch in The Sims 3 that had not yet been consistently fixed in gamemods, is when an active household all of a sudden has their Sims be reset almost every time they choose "Get Mail" from their mailboxes, and the mailboxes would get continuously stuffed with unusable and unpayable gifts and Omniplant boxes, which are also very difficult to get rid off without e.g. NRaas Debug Enabler.

The "No Bills" lifetime reward doesn't fix it, replacing the mailbox with Buydebug doesn't fix it, and NRaas Overwatch has not been a guaranteed fix either (Even more so if "Affect Active Lot" hasn't been turned on manually on that savefile).

This overall situation left the glitch as a nightmare that made long-running savefiles near-unplayable... [b]until now![/b]

———————————————————————————————————————————————————————

This gamemod aims to prevent love letters from spawning in the household's mailbox at all, which in turn seems to prevent and for the most part even revert the [i]de facto[/i] savefile corruptions that are affected by the glitch.

And even for non-corrupted savefiles, it also prevents the notifications getting filled with all sorts of love letters from maybe a fifth of the town in the mailbox every day. By intention, the gamemod does however not prevent player Sims from manually sending love letters to NPC households.

The gamemod modifies the following files in GameplayData.package:
• LoveLetter_0x98d77ba1404ef0b1
•• kChanceOfLoveLetterNormal: __ > 0
•• kChanceOfLoveLetterInSpring: __ > 0
•• kChanceOfLoveLetterOnSpringHoliday: __ > 0
•• kLTRForHighRomanceTNS: __ > 50000
• AttractionGift_0xa0de798497f159e1
•• GiftBuyCategories: ____ > F
•• GiftBuySubCategories: ____ > F
•• GiftBuySubCategories2: ____ > F
•• GiftBuyRoomSubCategories: ____ > F
•• CanGiveRepeats: True > False
• AttractionNPCBehaviorController_0xc192d24b58f73168
•• kAttractionGiftLetterMaxChancePerDay: __ > 0
•• kAttractionLTRThresholds: "____, ____" > "99.9, 100.0"

——— Notes: ———
• It seems to remain possible to receive empty gift boxes, but they will not reset the Sim nor cause inventory spam.






(Requires: Seasons, I think?)

(Gods know how I'm supposed to get good screenshots for this to appease the ever strange MTS requirements.)
