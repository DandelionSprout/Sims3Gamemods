As of 6 January 2024, severe rash health problems prevent me from writing the entire gamemod description in one go (and certainly not screenshots or a full unabridged changelog) but I'll handle it gradually, as well as upload the actual gamemod to <i>de facto</i> Early Access, at some point in January.<br>

—————————————————————————————————————

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
•• (ReactToPrecipitation_PutUpUmbrella_Sim)<br><br>
• "MermaidDermalDehydration": 0 > -500<br>
• "BuffMermaidFlakey": 0 > -900<br>
• "BuffMermaidDehydrated": 0 > -2000<br>
• "BePlantSim": 0 > 190<br>
• "BeFrankenstein": 0 > 1000<br><br>
• (UseToilet_Toilet) "Bladder": ???? > 1500
