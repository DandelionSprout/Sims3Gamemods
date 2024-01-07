As of 6~7 January 2024, severe rash health problems prevent me from writing the entire gamemod description in one go (and certainly not screenshots or a full unabridged changelog) but I'll handle it gradually, as well as upload the actual gamemod to <i>de facto</i> Early Access, at some point in January.<br><br>

(Final name for the mod?:) "Make NPCs Smarter and Less Racist"<br><br>

Working names included "Pyramid Mummy Money" and "Make Sims Smarter".<br>
—————————————————————————————————————<br>
‰Insert flavour intro text here.‰<br>
—————————————————————————————————————<br>
Known file changes:<br>
• FrankensteinReaction_Sim, MummyReaction_Sim, and GhostReaction_Sim have had "AgeSpeciesValue" changed from "C,T,Y,A,E" to the non-existent value "F", ensuring that such hostile species-ist reactions cannot ever happen.<br>
• Sim+BladderFailure_0x252b38f2929d72b0a8 and BuffExhausted+PassOut_0x3cad2a5b7ecfd7cd have had "kDistanceToReact" changed from 10 to 0, because Sims reacting to them would make them run out of rabbitholes (Confirmed for the Vault of Antiquity) just to be scared at it, and then lose track of everything they were doing and later proceed hours later to <i>also</i> wet themselves or faint.<br>
• Some 3 dozen water-related interactions have had their weighting values massively increased or decreased to massively encourage Mermaid Sims and to some extent PlantSims to do water things, while massively discouraging SimBots from using most water things even without being Hydrophobic.<br><br>
• All 12 bathtub types' regular bath interactions have had additional and generally very specific values added to them, on top of any that they may have had in the game normally:<br>
•• "MermaidDermalDehydration": 0 > 900<br>
•• "BuffMermaidFlakey": 0 > 900 (Presuming these kinds of values stack)<br>
•• "BuffMermaidDehydrated": 0 > 2000<br>
•• "BePlantSim": ???? > 130<br>
•• "BuffPlantSimDehydrated": 0 > 300<br>
•• "BeFrankenstein" (i.e. SimBot): 0 > -1000<br>
•• "Hygiene": ???? > 450<br><br>
• For All-in-One Bathrooms (UseAllInOneBathroom_AllInOneBathroom), all of which in the 3 EP's models are treated as the same in the files:<br>
•• "Bladder": ???? > 1500<br>
•• "Hygiene": ???? > 1500<br>
•• "BuffSinged": ???? > 1500<br>
•• "MermaidDermalDehydration": ???? > 400<br>
•• "BuffMermaidFlakey": 0 > 500<br>
•• "BuffMermaidDehydrated": 0 > 1500<br>
•• "BuffPlantSimDehydrated": 0 > 300<br>
•• "BeFrankenstein": ???? > -1000<br><br>
• (ReactToPrecipitation_PutUpUmbrella_Sim)<br>
•• "MermaidDermalDehydration": 0 > -500<br>
•• "BuffMermaidFlakey": 0 > -900<br>
•• "BuffMermaidDehydrated": 0 > -2000<br>
•• "BePlantSim": 0 > 190<br>
•• "BeFrankenstein": 0 > 1000<br><br>

• On top of all other things NPCs on large lots will just stand still without fixing, is their Hunger motives, necessitating a lot of changes:<br>
• (EatHere_EatHere; presumably the diner) "Hunger": ???? > 2000<br>
• (EatOutside_Bistro) "Hunger": ???? > 750<br>
• (Fridge_Have_Frige) and (Fridge_Have_FridgeModerate):<br>
•• "Hunger": ???? > 800<br>
•• "VampireThirst": ???? > 1500<br>
• (HaveJuiceDefinition_Fridge):<br>
•• "Hunger": ???? > 150<br>
•• "VampireThirst": ???? > 2000<br>
• (HaveSnack_MiniFridge; i.e. the University Life fridge):<br>
•• "Hunger": ???? > 600<br>
•• "VampireThirst": ???? > 2000<br>
• (GrabFood_BuffetTable) "Hunger": ???? > 900<br>
• (OrderFood_BarProfessional) "Hunger: ???? > 1500<br>
• (OrderFood_FoodTruck):<br>
•• "Hunger": ???? > 700<br>
•• "VampireThirst": ???? > 800<br>
• (SummonFood_Sim; available to genies) "Hunger": ???? > 1000<br>
• (BuyToEat_VendingMachine) "Hunger": 0 > 400<br>
• (Buy_FoodFromConcessionsStand_ConcessionsStand": "Hunger: 0 > 200<br>
• (BuyFoodWithConcessionsStand_BuyWithRegiste; likely only applies to World Adventures) "Hunger": 0 > 200<br><br>
• (EatKelp_Kelp) "Hunger": ???? > 1300<br>
• (MermaidEat_Fish) "Hunger": ???? > 225<br>
• (SynthesizerOrder_FoodFoodSynthesizer) "Hunger": ???? > 600<br>
• (OrderFavouriteFoodOnWaiter_SocialInteractio) "Hunger": ???? > 600<br>
• (FutureBar_OrderDrinksServo) and (DrinkServoJuice_FutureBarGlass):<br>
•• "Maintenance": 40 > 1000<br>
•• "BuffNeedsRepairs": 0 > 300<br>
•• "BuffEmotionalMalfunction": 0 > 200<br><br>

• (UseToilet_Toilet) "Bladder": ???? > 1500<br>
• (PlayWithSprinkler_Sprinkler):<br>
•• "BePlantSim": ???? > 110<br>
•• "MermaidDermalDehydration": ???? > 300<br>
•• "BuffMermaidFlakey": 0 > 900<br>
•• "BuffMermaidDehydrated": 0 > 2000<br>
• (Slide_SlippySlide):<br>
•• "MermaidDermalDehydration": ???? > 150<br>
•• "BuffMermaidFlakey": 0 > 800<br>
•• "BuffMermaidDehydrated": 0 > 1500<br>
•• "BePlantSim": ???? > 80<br>
•• "BuffPlantSimDehydrated": 0 > 300<br>
•• "BeFrankenstein": ???? > -1000<br><br>

• Sims also often faint apropos of nothing, and generally don't do anything about it before they, well, faint.<br>
• (BedSleep_Bed):<br>
•• "Energy": ???? > 800<br>
•• "BuffTired": 0 > 1500<br>
•• "BuffLethargic": 0 > 1500<br>
•• "BuffExhausted": 0 > 1600<br>
•• "BuffDrained": 0 > 1600<br>
• (BedNap_Bed):<br>
•• "Energy": ???? > 400<br>
•• "BuffExhausted" ???? > 800<br>
•• "BuffDrained": ???? > 800<br>
• (DreamPodSleep_BedDreamPod)<br>
•• "Energy": ???? > 500<br>
•• "BuffTired": 0 > 1500<br>
•• "BuffLethargic": 0 > 1500<br>
•• "BuffExhausted": 0 > 1600<br>
•• "BuffDrained": 0 > 1600<br>
• (Nap_ChairLounge), (Nap_IHasSeatingGroup), and (Nap_RockingChair):<br>
•• "Energy": ???? > 300<br>
•• "BuffTired": 0 > 1100<br>
•• "BuffLethargic": 0 > 1100<br>
•• "BuffExhausted": 0 > 1200<br>
•• "BuffDrained": 0 > 1200<br><br>
• (Sleep_FairyHouse)<br>
•• "Energy": 170.64 > 700<br>
•• "BuffTired": 0 > 1200<br>
•• "BuffExhausted": 0 > 1400<br>
• (Nap_FairyHouse):<br>
•• "Energy": 110 > 300<br>
•• "BuffTired": 0 > 1100<br>
•• "BuffExhausted": 0 > 1200<br>
• (Sleep_ISleepingBag):<br>
•• "Energy": 100 > 300
•• "BuffTired": 0 > 500<br>
•• "BuffLethargic": 0 > 500<br>
•• "BuffExhausted": 0 > 900<br>
•• "BuffDrained": 0 > 900<br><br>
•• "TraitLovesTheOutdoors": 0 > 300<br>
• Vampire altars:<br>
•• "BuffLethargic": 0 > 1500<br>
•• "BuffDrained": 0 > 1600<br>

• Sims with the Inappropriate trait autonomously kept making forum posts too often, and then they couldn't be bothered to actually check the replies afterwards.<br>
• (MakeForumPostingInappropriate_Computer) and (MakeForumPostingInappropriate_HoloComputer)<br>
•• "TraitInappropriate": 200 > 50<br>
•• "TraitMeanSpirited": 200 > 50<br>
• (MakeForumPostingTroll_Computer) and (MakeForumPostingTroll_HoloComputer):<br>
•• "TraitEvil": 200 > 200<br>
•• "TraitMeanSpirited": 200 > 50<br>
• (CheckForResponses_Computer) and (CheckForResponses_HoloComputer):<br>
•• All species except Plumbots: 0 > 250<br>

• Repairing objects that can't possibly lead to electrocution.<br>
•• (RepairSink_Sink), (RepairToilet_Toilet), (RepairShower_Shower), and (Repair_AllInOneBathroom) Every single species in the game, unless listed below: 0 > 300<br>
•• "ServoBotHandiBot": 0 or 200 > 500<br>
•• "CleanerChip": 0 > 300<br>
•• "SentienceChip": 0 > 300<br>
•• "AbilityToLearnChip": 0 > 300<br>
•• "EfficientChip": 0 > 200<br>
• (FairyRepair_IGameObject): "BeFairy": 0 > 900<br>
• (ServoBotRepair_IGameObject): "ServoBot": 15 > 500<br>
• (AlienRepair_IGameObject): "BeAlien": 0 > 500<br><br>

• Repairing quite a large number of objects that can in fact lead to electrocution.<br>
• (Repair_FortuneCookieMaker), (Repair_NectarMaker), (Repair_PetFeedingStation), (Repair_RoutineStation), (Repair_SleepPodFuture), (Repair_TattooChairAdvanced), (Repair_TattoChair), (Repair_Teleporter), (Repair_TimeMachine), (Repair_TrashCompactor), (Repair_WashingMachine), (RepairBrainEnhanceingMachine_BrainEnhancingMachine), (RepairComputer_Computer), (RepairComputer_HoloComputer), (RepairDishwasher_Dishwasher), (RepairEDS_ElectroDanceSphere), (RepairFrankenstein_Sim), (RepairHelm_Helm), (RepairJukebox_Jukebox), (RepairKaraokeMachine_KaraokeMachine), (RepairSpeaker_WallMountSpeaker), (RepairStation_ScienceResearchStation), (RepairStereo_Stereo), (RepairTV_TV), and (RepairVendingMachine_VendingMachine)<br>
•• "ServoBotHandiBot": 0 or 200 > 500<br>
•• "CleanerChip": 0 > 300<br>
•• "SentienceChip": 0 > 300<br>
•• "AbilityToLearnChip": 0 > 300<br>
•• "EfficientChip": 0 > 200<br>
•• "BeFrankenstein": 0 > 750<br>
•• "BeMummy": 0 > 300<br>
•• "BeGhost": 0 > 200<br><br>

• Remarkably, SimBots can in fact swim in at least swimming pools without shorting out, although their Energy motive will plummet. Such situations are listed here.<br>
• (SwimAround_Pool)<br>
•• "MermaidDermalDehydration": ???? > 400<br>
•• "BePlantSim": ???? > 200<br>
•• "BuffPlantSimDehydrated": 0 > 300<br>
•• "BuffMermaidFlakey": 0 > 900<br>
•• "BuffMermaidDehydrated": 0 > 2000<br>
• (SwimAroundInOcean_Sim)<br>
•• "MermaidDermalDehydration": ???? > 300<br>
•• "BePlantSim": ???? > 150<br>
•• "BuffPlantSimDehydrated": 0 > 300<br>
•• "BuffMermaidFlakey": 0 > 900<br>
•• "BuffMermaidDehydrated": 0 > 2000<br>
•• "BuffDivingDeficiency": 0 > 200<br>
•• "BuffAdaptingToLand": 0 > 400<br>
• (Slide_WaterSlide), (Dive_DivingBoard), and (Dive_DiveWell)<br>
•• "MermaidDermalDehydration": ???? or 40 > 400<br>
•• "BePlantSim": ???? > 80<br>
•• "BuffPlantSimDehydrated": 0 > 300<br>
•• "BuffMermaidFlakey": 0 > 900<br>
•• "BuffMermaidDehydrated": 0 > 2000<br><br>

• Showers<br>
•• (TakeShower_Shower):<br>
••• "Hygiene": ???? > 800<br>
••• "TraitSinged": ???? > 1500<br>
••• "MermaidDermalDehydration: ???? > 800<br>
••• "BuffMermaidFlakey": 0 > 900<br>
••• "BuffMermaidDehydrated": 0 > 2000<br>
••• "BePlantSim": ???? > 400<br>
••• "BuffPlantSimDehydrated": 0 > 300<br>
••• "BeFrankenstein": 0 > -1000<br>
•• (TakeShower_ShowerBasic):<br>
••• "Hygiene": ???? > 500<br>
••• "TraitSinged": ???? > 1500<br>
••• "MermaidDermalDehydration: ???? > 600<br>
••• "BuffMermaidFlakey": 0 > 900<br>
••• "BuffMermaidDehydrated": 0 > 2000<br>
••• "BePlantSim": ???? > 200<br>
••• "BuffPlantSimDehydrated": 0 > 300<br>
••• "BeFrankenstein": 0 > -1000<br>
•• (TakeShower_ShowerLoft):<br>
••• "Hygiene": ???? > 600<br>
••• "TraitSinged": ???? > 1500<br>
••• "MermaidDermalDehydration: ???? > 300<br>
••• "BuffMermaidFlakey": 0 > 900<br>
••• "BuffMermaidDehydrated": 0 > 2000<br>
••• "BePlantSim": ???? > 150<br>
••• "BuffPlantSimDehydrated": 0 > 300<br>
••• "BeFrankenstein": 0 > -1000<br>
•• (TakeShower_ShowerTub):<br>
••• "Hygiene": ???? > 800<br>
••• "TraitSinged": ???? > 1500<br>
••• "MermaidDermalDehydration: ???? > 800<br>
••• "BuffMermaidFlakey": 0 > 900<br>
••• "BuffMermaidDehydrated": 0 > 2000<br>
••• "BePlantSim": ???? > 150<br>
••• "BuffPlantSimDehydrated": 0 > 300<br>
••• "BeFrankenstein": 0 > -1000<br><br>

• Object upgrades, provided that only 1 upgrade is possible for a specific object<br>
• Mostly the same principles apply as for object repairs.<br>
•• (UpgradeAutoFill_JuiceKeg), (UpgradeAutoFill_WaterTrough), (UpgradeMakeAutoWater_Sprinkler) and (UpgradeExtinguisher_Sim) Every single species in the game, unless listed below: 0 > 300<br>
••• "ServoBotHandiBot": 0 or 200 > 500<br>
••• "CleanerChip": 0 > 300<br>
••• "SentienceChip": 0 > 300<br>
••• "AbilityToLearnChip": 0 > 300<br>
••• "EfficientChip": 0 > 200<br>
•• Additional for (UpgradeMakeAutoWater_Sprinker): "BeInFirefighterEmergency": 0 > 100<br>
•• (MagicallyUpgrade_GameObject) "BeWitch": 0 > 1000<br>
•• (UpgradeCosmicBowling_BowlingLane), (UpgradeLookGoodMirrors_StylingMirrors), (UpgradeUnbreakable_ScienceResearchStation), (UpgradePowerCleanse_SonicShower), (UpgradeFireAlarm_FireStationAlarm), (UpgradeMakeUnbreakable_PetFeedingStation), (UpgradeAlwaysGoodFortune_FortuneCookieMaker), (UpgradeNeverLoses_Dartboard), (UpgradeFasterCooking_Microwave), (UpgradeToLevelTwo_BrainEnhancingMachineCollege), (UpgradeToLevelThree_BrainEnhancingMachineCollege)<br>
••• "TraitHandy": 0 > 600<br>
••• "SkillHandiness": 0 > 200<br>
••• "ServoBotHandiBot": 0 or 200 > 500<br>
••• "CleanerChip": 0 > 300<br>
••• "SentienceChip": 0 > 300<br>
••• "AbilityToLearnChip": 0 > 300<br>
••• "EfficientChip": 0 > 200<br>
••• "BeFrankenstein": 0 > 750<br>
••• "BeMummy": 0 > 300<br>
••• "BeGhost": 0 > 200<br>
•• (UpgradeWardrobe_Wardrobe)<br>
••• "BeWitch": 0 > 800<br>
••• "SkillSpellcasting": 300 > 500<br><br>

• Social actions to prevent Social motice collapses<br>
•• (CallChat_Phone)<br>
••• "Social": ???? > ????<br>
••• "BuffLonely": 0 > ????<br>
••• "BuffDesolate": 0 > ????<br>
•• (SendChatText_PhoneCell)<br>
••• "Social": ???? > ????<br>
••• "BuffLonely": 0 > ????<br>
••• "BuffDesolate": 0 > ????<br>
•• (CallGeneric_Phone)<br>
••• "Social": ???? > ????<br>
••• "BuffLonely": 0 > ????<br>
••• "BuffDesolate": 0 > ????<br>
•• (BlogApp_PhoneSmart)<br>
••• "Social": ???? > ????<br>
••• "BuffLonely": 0 > ????<br>
••• "BuffDesolate": 0 > ????<br>
•• (SendPictureText_PhoneCell)<br>
••• "Social": ???? > ????<br>
••• "BuffLonely": 0 > ????<br>
••• "BuffDesolate": 0 > ????<br>
•• (ChatRandom_Computer) and (ChatRandom_HoloComputer)<br>
••• "Social": ???? > ????<br>
••• "BuffLonely": 0 > ????<br>
••• "BuffDesolate": 0 > ????<br>
•• (Chat_Sim)<br>
••• "Social": ???? > ????<br>
••• "BuffLonely": 0 > ????<br>
••• "BuffDesolate": 0 > ????<br>
•• (GroupChat_Sim) and (GroupChatB_Sim)<br>
••• "Social": ???? > ????<br>
••• "BuffLonely": 0 > ????<br>
••• "BuffDesolate": 0 > ????<br>
•• (SeatedChat_Sim)<br>
••• "Social": ???? > ????<br>
••• "BuffLonely": 0 > ????<br>
••• "BuffDesolate": 0 > ????<br>
•• (Chat_MagicMirror)<br>
••• "Social": ???? > ????<br>
••• "BuffLonely": 0 > ????<br>
••• "BuffDesolate": 0 > ????<br>
•• (ChatWithBonehilda)<br>
••• "Social": ???? > ????<br>
••• "BuffLonely": 0 > ????<br>
••• "BuffDesolate": 0 > ????<br><br>

• Causes the Sims to no longer run towards a fire and scream for 2 hours, unless it is to actively try to actually extinguish the fire.<br>
• (ReactToFire_IGameObject) ???? > F<br>
• (CastIceBlastTerrain_Fire:<br>
•• "ExtinguishSelf": ???? > 1200<br>
•• "BeInFirefighterEmergency": 200 > 300<br>
•• "BeScenarioFirefighter": 200 > 300<br>
•• "SkillSpellcasting": 0 > 600<br>
•• "BeGhost": 0 > 1000<br>
•• "TraitDaredevil": 0 > 500<br>
•• "TraitImmuneToFire": 0 > 1000<br>
•• "????" ???? > ????<br>
• (Extinguish_Fire):<br>
•• "BeFrankenstein": 0 > 1000<br>
•• "BeGhost": 0 > 1000<br>
•• "TraitDaredevil": 0 > 500<br>
•• "TraitImmuneToFire": 0 > 1000<br>
• (CallFirefighters_Phone) "BeInFirefighterEmergency": 0 > 200<br><br>

• Other:<br>
• (OccultVampire_0x36330d971d54d54d) "PulseRadius": 3 > 0 (The hope is that this will prevent the "Hunted" moodlet)<br>
• (WorkInRabbitHole_RabbitHole)<br>
•• Every single species in the game, alongside Plumbots with the Office Drone chip: ???? > 1500; updateEvenOnFailure: false > true<br>
•• "TraitWorkaholic": ???? > 1000<br>
•• "TraitAmbitious": ???? > 300<br>
•• "TraitSchmoozer": ???? > 300<br>
•• "Work": ???? > 500<br>
• (GetInCarpool_CarNpc):<br>
•• Every single species in the game, alongside Plumbots with the Office Drone chip: ???? > 750; updateEvenOnFailure: false > true<br>
•• "TraitWorkaholic": ???? > 1000<br>
•• "TraitEcoFriendly": 0 > -500<br>
• (SpongeBath_Sink):<br>
•• Detached from the Inappropriate trait requirement.<br>
•• "Hygiene": ???? > 400<br>
•• MermaidDermalHydration: 50 > 400<br>
•• "BeSinged": 0 > 1000<br>
• (Sim+BladderFailure_0x252b38f29d72b0a8) "kDistanceToReact": 10 > 0<br>
• (BuffExhausted+PassOut_0x2cad2a5b7ecfd7cd) "kDistanceToReact": 10 > 0<br>
• (SyphonPower_IgameObject):<br>
•• "BeInBotEmporium": 0 > 250<br>
•• "BeInGalleryShop": 0 > 100<br>
•• "BeInArcade": 0 > 100<br>
•• "BeAtResort": 0 > -50<br>
•• "BeInGym": 0 > -100<br>
•• "BeInSalon": 0 > -100<br>
•• "BeInGalleryShop": 0 > -100<br>
•• "BeInRebelHangout": 0 > -100<br>
•• "BeInLaundromat": 0 > -250<br>
•• "BeInDiveBar": 0 > -250<br>
•• "BeInCocktailLounge": 0 > -250<br>
•• "BeInDanceClub": 0 > -250<br>

—————————————————————————<br>
To-do: Idles info; run DisallowAutonomous, AllowOnCommunityLots, and AllowOnAllLots once again; possibly allow additional traits to Sponge Bath?; triple-check the codenames of traits, and hidden traits, and trait chips (Extremely important); check if SimBots can safely Sponge Bath<br><br>

Skipped due to complete inability to find info: Delay werewolf fullmoon transformation if at work; Allow additional species to use the Weather Stone.
