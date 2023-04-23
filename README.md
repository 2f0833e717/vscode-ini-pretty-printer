# Todo 
1. ini file ver

sample:

;This is how many AP points a soldier gains per level (on standard Combat Intelligence), you can change this to whatever you like! heroes gain 10)
+BaseAbilityPointsPerPromotion=10		
+AbilityPointsIncrementPerPromotion=2	
+RandomAbilityDecks=(DeckName="SkirmisherXComAbilities",          Abilities=((AbilityName="LightningReflexes"),               (AbilityName="TacticalRigging"),               (AbilityName="VolatileMix",  ApplyToWeaponSlot=eInvSlot_Unknown),               (AbilityName="SaturationFire",  ApplyToWeaponSlot=eInvSlot_PrimaryWeapon),               (AbilityName="SkirmisherReturnFire", ApplyToWeaponSlot=eInvSlot_PrimaryWeapon),               (),               ()))
+SoldierRanks=(AbilitySlots=((AbilityType=(AbilityName="SkirmisherStrike")),            (AbilityType=(AbilityName="SkirmisherTraining")),            (AbilityType=(AbilityName="SkirmisherGrapple", ApplyToWeaponSlot=eInvSlot_Unknown)),            ()),          aStatProgression=((StatType=eStat_Offense,StatAmount=3), (StatType=eStat_HP,StatAmount=1), (StatType=eStat_Strength,StatAmount=0), (StatType=eStat_Hacking,StatAmount=0), (StatType=eStat_CombatSims,StatAmount=1), (StatType=eStat_Will,StatAmount=5)))
+SoldierRanks=(AbilitySlots=((AbilityType=(AbilityName="SkirmisherReflex")),            (AbilityType=(AbilityName="Justice"),            (AbilityType=(AbilityName="TotalCombat")),            (RandomDeckName="SkirmisherXComAbilities")),          aStatProgression=((StatType=eStat_Offense,StatAmount=3), (StatType=eStat_HP,StatAmount=1), (StatType=eStat_Strength,StatAmount=0), (StatType=eStat_Hacking,StatAmount=5), (StatType=eStat_CombatSims,StatAmount=0)))
+SoldierRanks=(AbilitySlots=((),            (AbilityType=(AbilityName="SkirmisherVengeance")),            (AbilityType=(AbilityName="ZeroIn", ApplyToWeaponSlot=eInvSlot_PrimaryWeapon)),            (RandomDeckName="SkirmisherXComAbilities")),          aStatProgression=((StatType=eStat_Offense,StatAmount=3), (StatType=eStat_HP,StatAmount=1), (StatType=eStat_Strength,StatAmount=0), (StatType=eStat_Hacking,StatAmount=0), (StatType=eStat_CombatSims,StatAmount=0)))
+SoldierRanks=(AbilitySlots=((),            (AbilityType=(AbilityName="Whiplash")),            (AbilityType=(AbilityName="FullThrottle", ApplyToWeaponSlot=eInvSlot_Unknown)),            (RandomDeckName="SkirmisherXComAbilities")),          aStatProgression=((StatType=eStat_Offense,StatAmount=2), (StatType=eStat_HP,StatAmount=1), (StatType=eStat_Strength,StatAmount=1), (StatType=eStat_Hacking,StatAmount=0), (StatType=eStat_CombatSims,StatAmount=0)))
+SoldierRanks=(AbilitySlots=((AbilityType=(AbilityName="CombatPresence", ApplyToWeaponSlot=eInvSlot_Unknown)),            (AbilityType=(AbilityName="Retribution", ApplyToWeaponSlot=eInvSlot_SecondaryWeapon)),            (AbilityType=(AbilityName="SkirmisherInterrupt")),            (RandomDeckName="SkirmisherXComAbilities")),          aStatProgression=((StatType=eStat_Offense,StatAmount=2), (StatType=eStat_HP,StatAmount=0), (StatType=eStat_Strength,StatAmount=0), (StatType=eStat_Hacking,StatAmount=5), (StatType=eStat_CombatSims,StatAmount=0)))
+SoldierRanks=(AbilitySlots=((AbilityType=(AbilityName="SkirmisherAmbush", ApplyToWeaponSlot=eInvSlot_Unknown)),            (AbilityType=(AbilityName="Reckoning", ApplyToWeaponSlot=eInvSlot_SecondaryWeapon)),            (),            (RandomDeckName="SkirmisherXComAbilities")),          aStatProgression=((StatType=eStat_Offense,StatAmount=1), (StatType=eStat_HP,StatAmount=1), (StatType=eStat_Strength,StatAmount=0), (StatType=eStat_Hacking,StatAmount=0), (StatType=eStat_CombatSims,StatAmount=0)))
+SoldierRanks=(AbilitySlots=((AbilityType=(AbilityName="ManualOverride")),            (AbilityType=(AbilityName="Battlelord")),            (AbilityType=(AbilityName="Judgment")),            (RandomDeckName="SkirmisherXComAbilities")),          aStatProgression=((StatType=eStat_Offense,StatAmount=1), (StatType=eStat_HP,StatAmount=1), (StatType=eStat_Strength,StatAmount=1), (StatType=eStat_Hacking,StatAmount=5), (StatType=eStat_CombatSims,StatAmount=0)))







# Visual Studio Code JSON Pretty Printer

![Screenshot](https://raw.githubusercontent.com/euskadi31/vscode-json-pretty-printer/master/screenshot.gif)

# License

json-pretty-print is licensed under [the MIT license](LICENSE.md).
