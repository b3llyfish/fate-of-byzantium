# Fate Of Byzantium
Mod the aims to control Byzantium following their post Roads to Power implementation.
There are two parts to this mod:
* a new thematic struggle for Byzantium
* nerfs/tweaks/fixes to administrative governments

## Details

### Fate of Byzantium Struggle
A new struggle exclusively for Orthodox Greeks (no other cultures/faiths may become involved).

The struggle is designed to encourage AI Byzantium to focus conquests towards the Balkans/Italy and to hamper its ability 
to wage war effectively as it goes through the phases.

It is **not** an interactive struggle, as a player do not expect a revamped Byzantine experience. It has been designed 
with the AI in mind, with the ultimate end goal of Byzantine decline. 

#### Phases
The phases have been designed to be one way for the AI. 

##### Optimism
Leads to: Stagnation, Decline

Endings: Byzantine Resurgence

Active From: 867

In this phase Byzantium receives military buffs and two new Casus Bellis to impose their will onto the Balkans and Italy.
Opinions between Greeks will also be better, resulting in fewer claimants.

To transition into this phase a large percentage of the struggle region must be controlled by Byzantium.

##### Stagnation
Leads to: Optimism, Decline

Endings: 

Active From: 1066, 1178 (configurable via game rule)

In this phase Byzantium receives military and economic penalties, representing corruption and faults within the administration.
They still get access to the two new Casus Bellis and Greek characters gain more monthly influence and an additional
political scheme slot.

This phase is transitioned to once enough political schemes are executed from involved characters. 

##### Decline
Leads to: Optimism

Endings: Fall of Byzantium

Active From: 1178 (configurable via game rule)

Similar to the stagnation phase but the penalties are enhanced. The fort level and garrison size of Greek counties is 
also reduced, allowing easier conquest. 

To transition into this phase Byzantium needs to lose control of a large number of provinces within the core Greek region.

#### Endings

#### Byzantine Resurgence
Can only be done in the Optimism phase. Requires majority control of the struggle region.

This ending is pretty lackluster and only exists as a positive way for a player to end the struggle. It is unlikely the 
AI will be coordinated enough to do this.

#### Fall of Byzantium
Can only be done in the Decline phase. Can be done by any interloper once Byzantium loses majority control of the struggle region.

This ending restructures the Byzantium Empire, resulting in a smaller de jure Empire around Greece. The Greek culture
will also gain a negative tradition (with modifiers similar to those in the stagnation phase) that cannot be removed.

### General Byzantium Changes
Below list all changes to Byzantium and the surrounding region that are independent of the struggle.

#### Theodosian Walls
* Tax multiplier modifiers have been removed
* Monthly income has been reduced to 3 
* Development modifiers have been slightly reduced
* County control and epidemic resistance modifiers have been added

#### Seljuk Invasion
* A Seljuk invasion will occur against Byzantium at some point after 1077 if not using the 1178 start date. 
* The invader will attempt to establish the Sultanate of Rum. 
* If possible, Suleiman ibn Qutalmish will lead the invasion.
* Elements of the invasion, including disabling it, can be changed via game rules. 

#### Sultanate of Rum
* The decision to form the Sultanate of Rum is now much easier
* All de jure duchies under the Anatolia Kingdom title will be transferred to Rum upon its formation
* Forming the Sultanate of Rum will give the character a trait with bonuses to help continue the fight against the Byzantines
* This trait is passed on upon succession

#### Dissolve Bulgaria
* New decision for Byzantium if they are able to vassalise a non-admin Kingdom of Bulgaria
* Will destroy the Kingdom title and convert Bulgarian Dukes into governors

#### 867 Game Start
* Byzantium title starts with theme troops

#### 1066 Game Start
* Byzantium title starts with theme troops
* The Seljuk Invasion of Armenia will be resolved on game start (configurable via game rules)

#### 1178 Game Start
* Basileus Manuel now has the depressed trait on game start
* Byzantium title starts with theme troops
* Emperor no longer starts with thematic Varangian Guards troops that exceed the MAA's unit cap
* Sultanate of Rum starts with additional troops
* Sultanate of Rum start with the 'Sultan of Rum' trait
* Kingdom of Rum now is de jure liege of all duchies previously under Anatolia

#### Culture
* Oghuz culture now has the Horse Lords tradition
* Turkmen culture now starts with the mangonel innovation

### Administrative Government Changes

#### Defines
* Score required to be a powerful house decreased to 35
* Max number of powerful houses increased to 8
* Base cost of hiring theme troops increased to 150 influence
* AI will no longer over-estimate an Admin Government's military strength

#### Government
* If the DLC 'All Under Heaven' is unavailable then China, Korea and Japan will use Administrative Government (instead of Feudal)

#### Demand Administrative Governance Interaction
* Cultures who do not benefit from Admin governments are much less likely to accept
* Characters who hold King or higher titles will never accept
* Characters with 0% acceptance chance will no longer choose the 'negotiate' options

#### Factions
* Removed 'Admin empire should not face new factions during ongoing faction wars' faction blocker
* Populists factions are slightly more likely to form for administrative governments
* Populists factions now fight for independence rather than enforcing a state faith
* Populists counties are no longer prevent from joining factions if their faith matches the state faith
* A character's 'Governor Efficiency' now affects a county's desire to join a Populist faction (poor governors increase the chance of revolts)
* Characters will now consider a claimant's 'House Power' (relative to the Emperors) when creating/joining claimant factions

#### Governor Efficiency
* Revamped how Governor Efficiency is evaluated
* Higher scores will now be more difficult
* Base is now 0
* Skills higher than 10 will increase the score, whilst lower will decrease it
* Added negative modifiers for 1-star and 2-star education
* Added negative modifiers for Fate of Byzantium struggle phases

#### House Family Attributes
* Bonuses to the liege in all attributes have been drastically reduced
* Improved the bonuses given to family members

#### Succession
* Empire level successions in admin governments will give an unpressed claims to the runner-ups (configurable via game rules)
* Children of the Emperor will now inherit an unpressed claim (configurable via game rules)
* Children of the Byzantine Emperor now require the 'Born in the Purple' trait in order to inherit a claim (configurable via game rules) 

#### Emperor Succession Appointment
* The skill contribution for Emperor succession appointment has been reduced (now matches the same contribution level as Governor succession appointment)
* Add modifiers for having virtuous or sinful traits to the state faith

#### Powerful Vassal Claim Event
* New event that will periodically trigger on a random powerful vassal
* The vassal may gain a claim on the Empire title, depending on their personality

#### Seize Peripheral Duchy
* Can only target neighbouring land/sea provinces

## Game Rules

### Struggle
Whether to enable the 'Fate of Byzantium' struggle

* Enabled (default)
* Disabled

### Struggle - 1178 start phase
In the 1178 start date what stage should the struggle start in

* Stagnation (default)
* Decline

### Emperor Additional Succession Claims
The number of unpressed claims to give to runner-ups on an Admin Emperors death (example: Two means give claims to the candidates in 2nd and 3rd place)

* No additional claims
* One
* Two (default)
* Three

### Emperor Succession Inheritance Claims
How child claims are handled when an administrative Emperor dies.

* No Change
* No Claims
* Unpressed + Born in the Purple (default)
* Pressed + Born in the Purple

### Invasion of Rum
When should the Seljuk invader attack Byzantium

* Random (default)
* Fixed
* Disabled

### Invader of Rum Culture
What culture should the Seljuk invader have

* Turkmen (default)
* Persian Emperor

### Suleiman ibn Qutalmish
Whether to try and use the historical Rum founder as the Seljuk invader. Suleiman must be AI, an adventurer and not at war. An additional health check can also be done.

* Use Healthy Suleiman (default)
* Use Suleiman
* Do not use Suleiman

### Chance of Frankokratia
This is a base game rule, however the default has been overridden to 'Fourth Crusade' to prevent a very early Latin Empire

### Seljuk Invasion of Armenia ###
In 1066 should the result of Seljuk's invasion of Armenia?

* Seljuk Victory (default)
* Mechanical
* Byzantium Victory

### Sultan of Rum Trait ###
How powerful are the bonuses that the Sultan of Rum gets

* Major
* Moderate (default)
* Minor
* Off

### Sultan of Rum Trait (1178) ###
How powerful are the bonuses that the Sultan of Rum gets in the 1178 start date

* Major (default)
* Moderate
* Minor
* Off

### Administrative China
What government China should have if 'All Under Heaven' is missing

* Administrative (default)
* Default

### Administrative Korea
What government Korea should have if 'All Under Heaven' is missing

* Administrative (default)
* Default

### Administrative Japan
What government Japan should have if 'All Under Heaven' is missing

* Administrative (default)
* Default

## Compatibility
There are a bunch of overrides (populists, rum, governor efficiency, etc...) made by this mod. It is unlikely to cause
any crashes with other mods that override these things but be aware you may get a different experience. 

This mod has been designed with Cultures Expanded enabled and would recommend installing it.

## Localisation
I welcome any localisation mods. Please let me know if you make one, and I will add a link.