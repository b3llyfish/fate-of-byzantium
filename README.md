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
with the AI in mind, with the end goal of Byzantine decline. 

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

Active From: 1066

In this phase Byzantium receives military and economic penalties, representing corruption and faults within the administration.
They still get access to the two new Casus Bellis and Greek characters gain more monthly influence and an additional
political scheme slot.

This phase is transitioned to once enough political schemes are executed from involved characters. 

##### Decline
Leads to: Optimism

Endings: Fall of Byzantium

Active From: 1187

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
Below list changes to Byzantium that are independent of the struggle.

#### Theodosian Walls
* Tax multiplier modifiers have been removed
* Monthly income has been reduced from 10 to 5 gold 
* Development modifiers have been slightly reduced
* County control and epidemic resistance modifiers have been added

#### Seljuk Invasion
* A Seljuk invasion will occur against Byzantium at some point after 1077 if not using the 1187 start date. 
* The invader will attempt to establish the Sultanate of Rum. 
* The date of the invasion and invader culture can be changed via game rules. The invasion can also be disabled. 

#### Sultanate of Rum
* The decision to form the Sultanate of Rum is now much easier
* All de jure duchies under the Anatolia Kingdom will be transferred to Rum upon its formation

#### Dissolve Bulgaria
* New decision for Byzantium if they are able to vassalise a non-admin Kingdom of Bulgaria
* Will destroy the Kingdom title and convert Bulgarian Dukes into governors

### Administrative Government Changes

#### Defines
* Score required to be a powerful house decreased to 35
* Max number of powerful houses increased to 8
* Base influence cost of hiring theme troops increased to 200

#### Demand Administrative Governance Interaction
* Cultures who do not benefit from Admin governments are less likely to accept

#### Factions
* Removed 'Admin empire should not face new factions during ongoing faction wars' faction blocker
* Populists factions are slightly more likely to form for administrative governments
* Populists factions now fight for independence rather than enforcing a state faith
* Populists counties are no longer prevent from joining factions if their faith matches the state faith
* A character's 'Governor Efficiency' now affects a county's desire to join a Populist faction (poor governors lead to more revolts)

#### Government
* Cost of mercenaries and men-at-arms is increased by 15%

#### Governor Efficiency
* Revamped how skills contribute to the score, with low skills contributing less and high skills contributing more

#### Succession
* Empire level successions in admin governments will give an unpressed claim to the runner-up (can be extended/removed via game rule)

## Game Rules

### Struggle
Whether to enable the 'Fate of Byzantium' struggle

* Enabled (default)
* Disabled

### Emperor Additional Succession Claims
The number of unpressed claims to give to runner-ups on an Admin Emperors death (example: Two means give claims to the candidates in 2nd and 3rd place)

* No additional claims
* One (default)
* Two
* Three

### Invasion of Rum
When should the Seljuk invader attack Byzantium

* Random (default)
* Fixed
* Disabled

### Invader of Rum Culture
What culture should the Seljuk invader have

* Turkmen (default)
* Persian Emperor

### Chance of Frankokratia
This is a base game rule, however the default has been overridden to 'Fourth Crusade' to prevent a very early Latin Empire

## Compatibility
There are a bunch of overrides (populists, rum, governor efficiency, etc...) made by this mod. It is unlikely to cause
any crashes with other mods that override these things but be aware you may get a different experience. 

This mod has been designed with Cultures Expanded enabled and would recommend installing it.

## Localisation
I welcome any localisation mods. Please let me know if you make one, and I will add a link.