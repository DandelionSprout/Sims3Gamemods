Decided name: "Triple Duty Music Star"<br>
————————————————————————————————<br>
Have your Sims ever dreamed of being a true music superstar, who wanted to excel in multiple music fields, but who felt discouraged from doing so due to severely conflicting concert times? This mod will give your Sim the chance to finally excel and become a double-duty or even triple-duty superstar! A Sim that few people may have noticed even at autograph signings, will now the entire town want a piece of them, almost 24/7.

Want to combine the cinema Music career with Late Night band gigs? Now you can!

To combine any of the Showtime performer careers with Late Night band gigs? You're on.

Combining any of the above with countless musician skill opportunities, and even DJ gigs resulting from having practiced at DJ booths for days on end? Game on.

The mod primarily works by:
• [b][i]Massively[/i][/b] increasing the chances for Late Night gigs to be offered by phone.
• Drastically extending the timeslots where one 2-hour gig can be performed.
• Significantly expanding the amount of lot assignments where Late Night gigs and to some extent Showtime gigs can take place.
• Made Late Night gigs have less stringent requirements for how many other gigs a band must or may have performed before.
• Any Late Night gigs that were previously once-in-a-lifetime only, can now be offered multiple times.
• The timeslots of music-related skill opportunities across base game, Late Night, Showtime, and Into the Future, have been extended to varying extents, some by quite a lot.
• Late Night gigs now take place the day after getting the phone call, instead of 2 days after.
• [i]Partially[/i] reduced some bugs that led Scuba Diving and Laser Rhythm-a-Con opportunities to be offered more often than they probably should.

The mod was a solid 4 months in the making (The full changelog alone took 3 weeks to write), but now it's here and ready for, literally speaking, showtime!

The mod is by far most useful for players with Late Night installed, and even more so if both Late Night and Showtime are installed, but the mod itself is technically base game compatible, and would in a "Base game only" setting still provide some improvements to Guitar skill opportunities and to the Music career opportunities.

## All changes
Times are given in 12-hour format, as that's what is used as pre-existing Maxis values in the gamefiles.

### Opportunities_EP6
#### Gig performances
• (EP6_CareerSinger_PerformedForTips), (EP6_Magician_PerformForTips), (EP6_PerformanceArtist_PerformForTips), (EP6_CareerSinger_CompletedGig_Park), (EP6_Magician_CompletedGig_Park), (EP6_PerformanceArtist_CompletedGig_Park), (EP6_DJTurntable_CompletedMiniShow_Park), (EP6_Passport_Host_Park) "TargetData": BigPark > PigPark,SmallPark,FishingVenue,Graveyard<br>
• (EP6_CareerSinger_CompletedGig_Bistro), (EP6_Magician_CompletedGig_Bistro), (EP6_PerformanceArtist_CompletedGig_Bistro), (EP6_DJTurntable_CompletedMiniShow_Bistro), (EP6_Passport_Host_Bistro) "TargetData": Bistro > Bistro,Gym,Library,Pool,Arcade,CoffeeShop<br>
• (EP6_CareerSinger_CompletedGig_Hangout), (EP6_Magician_CompletedGig_PerformanceClub), (EP6_PerformanceArtist_CompletedGig_PerformanceClub), (EP6_DJTurntable_CompletedMiniShow_Hangout), (EP6_Passport_Host_PerformanceClub) "TargetData": PerformanceClub > PerformanceClub,Hangout,UniversityHangout,RebelHangout,NerdShop<br>
• (EP6_CareerSinger_CompletedGig_Private), (EP6_Magician_CompletedGig_Hangout), (EP6_PerformanceArtist_CompletedGig_Private), (EP6_DJTurntable_CompletedMiniShow_Private), (EP6_Passport_Host_Private) "TargetData": PrivateVenue > PrivateVenue,HorseRanch
#### Multi-career opportunities
• (EP6_Career_Singer_ParticipateInExperiment_Science), (EP6_Career_Magician_ParticipateInExperiment_Science), and (EP6_PerformanceArtist_ParticipateInExperiment_Science)<br>
•• "TargetData": ScienceLab > ScienceLab,StellarObservatory
#### Singer opportunities
• (EP6_CareerSinger_SingForSupper_Restaurant)<br>
•• "TargetInteractionStartTime": 2:00PM > 6:00PM<br>
•• "TargetInteractionEndTime": 00:30AM > 10:00PM<br>
•• "EventStartTime": 2:00PM > 1:00PM<br>
•• "EventEndTime": 00:30AM > 9:00PM<br>
• (EP6_CareerSinger_SingTeamBuilding):<br>
•• "TargetInteractionEndTime: 5:00PM > 10:00PM<br>
•• "EventEndTime": 6:00PM > 11:00PM<br>
• (EP6_CareerSinger_RecordDemoCD_Theatre):<br>
•• "TargetData": Theatre > Theatre,MovieSet<br>
•• "TargetInteractionEndTime": 2:00PM > 11:00PM<br>
•• "EventEndTime": 9:00PM > 11:00PM<br>
• (EP6_Interaction_RelaxVocalChords)<br>
•• "TargetInteractionStartTime": 10:00AM > 09:00AM<br>
•• "TargetInteractionEndTime": 4:00PM > 09:30PM<br>
•• "EventStartTime": 10:00AM > 09:00AM<br>
•• "EventEndTime": 9:00PM > 11:30PM<br>
• (EP6_Interaction_SingAtBigBossBirthday)<br>
•• "TargetInteractionStartTime": 7:00PM > 4:00PM<br>
•• "TargetInteractionEndTime": 11:00PM > 1:00AM<br>
•• "EventStartTime": 7:00PM > 4:00PM<br>
•• "EventEndTime": 11:00PM > 1:00AM<br>
• (EP6_Interaction_SingNationalAnthem)<br>
•• "TargetInteractionEndTime": 9:00AM > 9:00PM<br>
•• "EventEndTime": 10:00AM > 10:00PM<br>
• (EP6_Interaction_SingNationalAnthem_Stadium)<br>
•• "TargetData": Stadium > Stadium,EquestrianCenter,ServoBotArena<br>
•• "TargetInteractionStartTime": 5:00PM > 3:00PM<br>
•• "TargetInteractionEndTime": 7:00PM > 00:30AM<br>
•• "EventStartTime": 5:00PM > 3:30PM<br>
•• "EventEndTime": 7:00PM > 00:30AM<br>
#### Magician opportunities
• (EP6_Magician_TeachPickPocket_Criminal)<br>
•• "TargetInteractionStartTime": 7:00PM > 4:00PM<br>
•• "TargetInteractionEndTime": 11:00PM > 02:00AM<br>
• (EP6_Magician_PromoteFilmRelease_Theatre)<br>
•• "TargetInteractionStartTime": 5:00PM > 2:00PM<br>
•• "TargetInteractionEndTime": 11:00PM > 1:00AM<br>
•• "EventStartTime": 7:00PM > 2:30PM<br>
•• "EventEndTime": 11:00PM > 1:00AM<br>
• (EP6_Magician_TeachMindControl_CityHall)<br>
•• "TargetInteractionStartTime": 6:00PM > 6:00AM<br>
• (EP6_Magician_EntertainTroops_MilitaryBase)<br>
•• "TargetInteractionStartTime": 4:00PM > 10:00AM<br>
•• "TargetInteractionEndTime": 8:00PM > 9:00PM<br>
•• "EventEndTime": 9:00PM > 10:00PM<br>
#### Acrobat opportunities
• (EP6_PerformanceArtist_AttendSeminar_BusinessCenter)<br>
•• "TargetInteractionEndTime": 5:00PM > 10:00PM<br>
•• "EventEndTime": 6:00PM > 11:00PM<br>
• (EP6_PerformanceArtist_PoseAsStatue_Restaurant)<br>
•• "TargetInteractionStartTime": 6:00PM > 1:00PM<br>
•• "TargetInteractionEndTime": 9:00PM > 10:00PM<br>
•• "EventStartTime": 10:00AM > 1:00PM<br>
•• "EventEndTime": 6:00PM > 10:00PM<br>
• (EP6_PerformanceArtist_PerformForSale_GroceryStore)<br>
•• "TargetInteractionStartTime": 12:00PM > 10:30AM<br>
•• "TargetInteractionEndTime": 4:00PM > 08:30PM<br>
•• "EventEndTime": 10:00PM > 11:30PM<br>
• (EP6_PerformanceArtist_SoakSoreMuscles)<br>
•• "TargetInteractionEndTime": 4:00PM > 11:45PM<br>
•• "EventEndTime": 9:00PM > 02:00AM<br>
• (EP6_PerformanceArtist_EscapeArtist_Criminal)<br>
•• "TargetInteractionStartTime": 7:00PM > 2:00PM<br>
• (EP6_PerformanceArtist_PromoteFilmRelease_Theatre)<br>
•• "TargetInteractionStartTime": 5:00PM > 3:00PM<br>
•• "EventStartTime": 7:00PM > 3:00PM<br>
• (EP6_PerformanceArtist_FillInForMascot_Stadium)<br>
•• "TargetData": Stadium > Stadium,EquestrianCenter,ServoBotArena<br>
•• "TargetInteractionStartTime": 5:00PM > 3:00PM<br>
•• "EventStartTime": 5:00PM > 3:00PM<br>
•• "EventEndTime": 10:00PM > 11:00PM
#### Other changes for improved convenience
• (EP6_ReleaseGenie_TakeUnderground) "TargetData": Mausoleum > Mausoleum,VaultOfAntiquity

### Opportunities_EP3
All gigs and band opportunities are now set to «"RepeatLevel": Always» no matter what.<br><br>
All gigs have «"Timeout": 1» changed to «"Timeout": 0», so that gigs happen the day after the phone call, instead of 2 days.
#### Dive Bar-type gigs
• All Dive Bar band opportunities:<br>
•• "Chance to Get on Phone": 30 or 50 > 300 (450 for DiveBarLow1 and DiveBarLow2)<br>
•• "EventStartTime": Between 12:00PM and 8:00PM > 11:15AM<br>
•• "EventEndTime": Between 14:00PM and 11:00PM > 00:15AM<br>
• (EP3_SkillBand_DiveBarLow1):<br>
•• "TargetData": DiveBarCriminal > DiveBarCriminal,CatJungle,Pool,DogPark,Gym,PerformanceClub,Hangout<br>
•• "Requirement3": HasCompletedNGigs,0,1 > HasCompletedNGigs,0,4<br>
• (EP3_SkillBand_DiveBarMid1):<br>
•• "TargetData": DiveBarIrish > DiveBarIrish,GroupSciencePark,NerdShop,ArtGallery,PrivateVenue,BigPark<br>
•• "Requirement3": HasCompletedNGigs,3,4 > HasCompletedNGigs,0,500<br>
• (EP3_SkillBand_DiveBarHigh1):<br>
•• "TargetData": DiveBarSports > DiveBarSports,RebelHangout,Graveyard,BeachVenue,StudentUnion,UniversityHangout,Hangout<br>
•• "Requirement3": HasCompletedNGigs,6,7 > HasCompletedNGigs,2,500<br>
• (EP3_SkillBand_RandomDiveA1):<br>
•• "TargetData": DiveBarCriminal > DiveBarCriminal,DiveBarSports,DiveBarIrish,FestivalGrounds,Library<br>
•• "Requirement3": HasCompletedNGigs,1,3 > HasCompletedNGigs,0,500<br>
• (EP3_SkillBand_RandomDiveB1):<br>
•• "TargetData": DiveBarCriminal,DiveBarIrish > DiveBarCriminal,DiveBarIrish,HorseRanch,PrivateVenue,NerdShop,Library,DogPark,Hangout<br>
•• "Requirement3": HasCompletedNGigs,1,3 > HasCompletedNGigs,0,500<br>
• (EP3_SkillBand_RandomDiveC1):<br>
•• "TargetData": DiveBarCriminal,DiveBarIrish > DiveBarCriminal,DiveBarIrish,BeachVenue,StudentUnion,Salon,Arcade,GroupSciencePark,Hangout<br>
•• "Requirement3": HasCompletedNGigs,2,6 > HasCompletedNGigs,0,500<br>
• (EP3_SkillBand_RandomDiveD1):<br>
•• "TargetData": DiveBarSports,DiveBarIrish > DiveBarSports,DiveBarIrish,FishingVenue,Pool,ArtGallery,CoffeeShop,UniversityHangout<br>
•• "Requirement3": HasCompletedNGigs,3,7 > HasCompletedNGigs,3,500<br>
• (EP3_SkillBand_RandomDiveE1):<br>
•• "TargetData": DiveBarSports,DiveBarIrish > DiveBarSports,DiveBarIrish,PerformanceClub,Gym,RebelHangout,BigPark,CatJungle,Graveyard<br>
•• "Requirement3": HasCompletedNGigs,3,7 > HasCompletedNGigs,3,500<br>
#### Lounge-type gigs<br>
• All Dive Bar band opportunities:<br>
•• "Chance to Get on Phone": 30 or 50 > 300<br>
•• "EventStartTime": Between 3:00PM and 8:00PM > 02:15PM<br>
•• "EventEndTime": Between 7:00PM and 12:00AM > 1:15AM<br>
• (EP3_SkillBand_LoungeLow1):<br>
•• "TargetData": CocktailLoungeAsian > CocktailLoungeAsian,GroupSciencePark,Gym,StudentUnion,PerformanceClub,Pool,Hangout<br>
•• "Requirement3": HasCompletedNGigs,7,8 > HasCompletedNGigs,5,500<br>
• (EP3_SkillBand_LoungeMid1):<br>
•• "TargetData": CocktailLoungeVampire > CocktailLoungeVampire,CatJungle,NerdShop,FishingVenue,DogPark,UniversityHangout<br>
•• "Requirement3": HasCompletedNGigs,9,10 > HasCompletedNGigs,7,500<br>
• (EP3_SkillBand_LoungeHigh1):<br>
•• "TargetData": CocktailLoungeCelebrity > CocktailLoungeCelebrity,Graveyard,Salon,BigPark,HorseRanch,Arcade,Hangout<br>
•• "Requirement3": HasCompletedNGigs,11,12 > HasCompletedNGigs,8,500<br>
• (EP3_SkillBand_RandomLoungeA1):<br>
•• "TargetData": CocktailLoungeAsian > CocktailLoungeAsian,Library,RebelHangout,PrivateVenue,ArtGallery,CoffeeShop,BeachVenue<br>
• (EP3_SkillBand_RandomLoungeB1):<br>
•• "TargetData": CocktailLoungeAsian,CocktailLoungeVampire > CocktailLoungeAsian,CocktailLoungeVampire,Library,Graveyard,NerdShop,BeachVenue,CoffeeShop,PrivateVenue,Hangout<br>
• (EP3_SkillBand_RandomLoungeC1):<br>
•• "TargetData": CocktailLoungeAsian,CocktailLoungeVampire > CocktailLoungeAsian,CocktailLoungeVampire,Gym,DogPark,FishingVenue,Pool,BigPark,ArtGallery,Hangout<br>
• (EP3_SkillBand_RandomLoungeD1):<br>
•• "TargetData": CocktailLoungeCelebrity,CocktailLoungeVampire > CocktailLoungeCelebrity,CocktailLoungeVampire,CatJungle,RebelHangout,HorseRanch,Arcade,Salon,UniversityHangout,PerformanceClub<br>
#### Band opportunities
•• All band opportunities: 30 > 300<br>
• (EP3_SkillBand_VarietyShow)<br>
•• "TargetData": MovieSet > MovieSet,Theatre<br>
•• "TargetInteractionStartTime:" 5:00PM > 7:45AM<br>
•• "TargetInteractionEndTime:" 11:00PM > 1:00AM<br>
•• "Requirement3": HasCompletedNGigs,10,20 > HasCompletedNGigs,10,500<br>
• (EP3_SkillBand_Stadium)<br>
•• "TargetData": Stadium > Stadium,EquestrianCenter,ServoBotArena<br>
•• "TargetInteractionEndTime:" 11:00PM > 1:00AM<br>
•• "Requirement3": HasCompletedNGigs,15,500 > HasCompletedNGigs,11,500<br>
• (EP3_SkillBand_Concert)<br>
•• "TargetData": Theatre > Theatre,MovieSet<br>
•• "TargetInteractionEndTime:" 11:00PM > 1:00AM<br>
•• "Requirement3": HasCompletedNGigs,0,7 > HasCompletedNGigs,0,500<br>
#### Bass skill opportunities
• (EP3_SkillBass_MovieScore) "TargetInteractionEndTime:" 6:00PM > 9:00PM<br>
• (EP3_SkillBass_OrganizeSheetMusic) "TargetInteractionEndTime:" 5:00PM > 9:00PM<br>
• (EP3_SkillBass_SingAlong) "TargetInteractionStartTime:" 5:00PM > 1:00PM<br>
• (EP3_SkillBass_Alien) "TargetInteractionEndTime:" 08:00 > 10:00PM<br>
• (EP3_SkillBass_FillIn)<br>
•• "TargetInteractionStartTime:" 5:00PM > 2:00PM<br>
•• "TargetInteractionEndTime:" 11:00PM > 1:00PM<br>
• (EP3_SkillBass_Marathon)<br>
•• "TargetData": Stadium > Stadium,EquestrianCenter,ServoBotArena<br>
•• "TargetInteractionStartTime:" 10:00 > 7:00AM<br>
•• "TargetInteractionEndTime:" 8:00PM > 9:00PM<br>
•• "Requirement1": Skill,Bass,3,6 > Skill,Bass,3,10<br>
• (EP3_SkillBass_Sitcom)<br>
•• "TargetInteractionStartTime:" 12:00PM > 11:00AM<br>
•• "TargetInteractionEndTime:" 4:00PM > 9:00PM<br>
• (EP3_SkillBass_SeeMasterClass)<br>
•• "TargetInteractionStartTime:" 5:00PM > 2:00PM<br>
•• "TargetInteractionEndTime:" 9:00PM > 11:00PM<br>
• (EP3_SkillBass_CorporateParty)<br>
•• "TargetInteractionStartTime:" 5:00PM > 1:00PM<br>
•• "TargetInteractionEndTime:" 10:00PM > 11:00PM<br>
• (EP3_SkillBass_PoliticalDebate)<br>
•• "TargetInteractionStartTime:" 1:00PM > 9:00AM<br>
•• "TargetInteractionEndTime:" 6:00PM > 10:00PM
### Drums skill opportunities
• (EP3_SkillDrums_RobotScience) and (EP3_SkillDrums_DrummingScience)<br>
•• "TargetData": ScienceLab > ScienceLab,StellarObservatory<br>
• (EP3_SkillDrums_LateNight)<br>
•• "TargetData": MovieSet > MovieSet,Theatre<br>
•• "TargetInteractionStartTime:" 5:00PM > 4:00PM<br>
•• "Requirement1": Skill,Drums,6,8 > Skill,Drums,6,10<br>
• (EP3_SkillDrums_Landmarks)<br>
•• "TargetInteractionEndTime:" 4:00PM > 10:00PM<br>
• (EP3_SkillDrums_ComedyRimshots)<br>
•• "TargetInteractionEndTime:" 10:00PM > 10:30PM<br>
• (EP3_SkillDrums_FillIn)<br>
•• "TargetInteractionStartTime:" 7:00PM > 3:00PM<br>
•• "TargetInteractionEndTime:" 11:00PM > 1:00AM<br>
• (EP3_SkillDrums_SpaParty)<br>
•• "TargetInteractionEndTime:" 4:00PM > 10:00PM<br>
• (EP3_SkillDrums_UndergroundParty)<br>
•• "TargetInteractionStartTime:" 3:00PM > 2:00PM<br>
•• "TargetInteractionEndTime:" 7:00PM > 1:00PM<br>
•• "TargetData": Skill,Drums,2,4 > Skill,Drums,2,5<br>
### Piano skill opportunities
• (EP3_SkillPiano_SchoolMusical) "Requirement1": Skill,Piano,3,6 > Skill,Piano,3,8<br>
• (EP3_SkillPiano_Hospital) "Requirement1": Skill,Piano,2,4 > Skill,Piano,2,5<br>
• (EP3_SkillPiano_Gala)<br>
•• "TargetData": MovieSet > MovieSet,Theatre<br>
•• "TargetInteractionEndTime:" 11:59PM > 1:00AM<br>
•• "Requirement1": Skill,Piano,6,8 > Skill,Piano,6,10<br>
• (EP3_SkillPiano_SeeMasterClass)<br>
•• "TargetInteractionStartTime:" 5:00PM > 3:00PM<br>
•• "TargetInteractionEndTime:" 9:00PM > 10:00PM<br>
• (EP3_SkillPiano_Competition)<br>
•• "TargetInteractionStartTime:" 5:00PM > 3:00PM<br>
•• "TargetInteractionEndTime:" 10:00PM > 1:00PM<br>
• (EP3_SkillPiano_GiveMasterClass)<br>
•• "TargetInteractionStartTime:" 5:00PM > 1:00PM<br>
•• "TargetInteractionEndTime:" 9:00PM > 11:00PM<br>
• (EP3_SkillPiano_SportsEvent) "TargetInteractionEndTime:" 11:00PM > 1:00AM<br>
• (EP3_SkillPiano_FilmComposer_1) "TargetInteractionEndTime:" 7:00PM > 11:00PM<br>
• (EP3_SkillPiano_FilmComposer_2) "TargetInteractionEndTime:" 7:00 > 11:00PM<br>

△ Find the strings that determine that Late Night gigs take place 1 day after instead of 2 days.

### Opportunities_BaseGame
#### Music career opportunities
• (MusicCareer_LegendaryRockConcert):<br>
•• "TargetData": Stadium > Stadium,EquestrianCenter,ServoBotArena<br>
•• "TargetInteractionStartTime": 5:00PM > 4:00PM<br>
•• "TargetInteractionEndTime": 11:00PM > 1:00AM<br>
• (MusicCareer_LegendarySymphony):<br>
•• "TargetInteractionStartTime": 6:00PM > 4:00PM<br>
•• "TargetInteractionEndTime": 10:00PM > 1:00AM<br>
• (MusicCareer_TeachClass):<br>
•• "TargetInteractionStartTime": 4:00PM > 3:00PM<br>
•• "TargetInteractionEndTime": 6:00PM > 11:30PM
#### Guitar skill opportunities
• (GuitarSkill_AmateurContest):<br>
•• "TargetInteractionStartTime": 5:00PM > 11:00AM<br>
•• "TargetInteractionEndTime": 9:00PM > 11:00PM<br>
•• "Requirement1": Skill,Guitar,10,10 > Skill,Guitar,8,10<br>
• (GuitarSkill_Backup)<br>
•• "TargetInteractionStartTime: 5:00PM > 11:00PM<br>
•• "Requirement1": Skill,Guitar,5,9 > Skill,Guitar,5,10<br>
• (GuitarSkill_BusinessParty):<br>
•• "TargetInteractionStartTime": 6:00PM > 1:00PM<br>
•• "TargetInteractionEndTime": 10:00PM > 11:00PM<br>
•• "Requirement1": Skill,Guitar,5,9 > Skill,Guitar,5,10<br>
• (GuitarSkill_FundraiserParty) "TargetInteractionStartTime": 7:00PM > 11:00AM<br>
• (GuitarSkill_GainSkill) "TargetInteractionEndTime": 7:00PM > 11:00PM<br>
• (GuitarSkill_OrganizeMusic) "TargetInteractionEndTime": 5:00PM > 11:30PM<br>
• (GuitarSkill_ProGuitar):<br>
•• "TargetInteractionStartTime": 3:00PM > 8:00PM<br>
•• "TargetInteractionEndTime": 5:00PM > 11:30PM<br>
• (GuitarSkill_SchoolShow):<br>
•• "TargetInteractionStartTime": 12:00PM > 9:00AM<br>
•• "TargetInteractionEndTime": 4:00PM > 4:30PM<br>
•• "Requirement1": Skill,Guitar,2,6 > Skill,Guitar,2,10
#### Town community events
• (Location_MusicAppreciationDay):<br>
•• "EventStartTime": 11:00AM > 9:00AM<br>
•• "EventEndTime": 7:00PM > 10:00PM<br>
#### Non-music opportunities hopefully being given more rabbithole variation, as they too are stadiums
• (BusinessCareer_HoldMeeting), (PoliticalCareer_Stunt): "TargetData": Stadium > Stadium,EquestrianCenter,ServoBotArena<br>
• (Location_AmateurOlympics):<br>
•• "TargetData": Stadium > Stadium,EquestrianCenter,ServoBotArena<br>
•• "TargetInteractionEndTime": 5:00PM > 11:00 PM<br>
•• "EventEndTime": 7:00PM > 11:00 PM<br>

### Opportunities_EP10
• (All opportunities) "ChanceToGetOnPhone": 0 > 20 (Trying to fix a strange bug where Island Paradise opportunities are given far, far more often than any other opportunities. It's anyone's guess if the bugfix works.)

### Opportunities_EP11
• (EP11_Skill_Harp01-05) and (EP11_Misc_Future02-07) "ChanceToGetOnPhone": 500 > 125<br>
• (EP11_Skill_Harp01) Removed the "IsInFuture" requirement.<br>
• (EP11_Skill_Harp02) "TargetData": Restaurant > Restaurant,Bistro<br>
• (EP11_Skill_Harp03) "TargetData": ServoBotArena > ServoBotArena,Stadium,EquestrianCenter

### Gig_0x5645eab71079badc
• "kHoursBeforeGigToPullAudence": 2.00 > 0.30

### GigOpportunity_0x5e0966d3a36349a5
• "kTnsReminderLeadTime": 4 > 1<br><br>

## Notes
• The mod is unlikely to conflict with other mods that I'm currently aware of. If there are conflicts, players can open this mod in S3PE, delete the conflicting rows with the Del key, and then save the mod. Note however that "Opportunities_EP3" and "Opportunities_EP6" are very important parts of this mod, and that this mod would be borderline useless without those files.
• During testing, a minor bug in the game itself was discovered wherein the game would only offer 3 Late Night gigs in each play session, requiring saving and restarting the game to get additional ones. As players without the mod have been known to struggle to get gigs for weeks or even months in in-game time, very few players would ever have encountered that bug before.
• The mod was made with and tested with Patch 67, as it is indeed the most common patch version on Windows by far. Later patches should not have any problems with it in any way, but Patch 57 and earlier are anyone's guess.
