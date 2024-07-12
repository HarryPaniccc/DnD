---
tags:
  - Character
---
# Stats
>[!Notes]
>- Spear/staff and plate armor
>- Spell DC = 8 + 4 + 6 + mods = 18 + 1 (damnation) + 1 (damnation)
>- Charisma = 18 + 2 from damnation
>- [[Spear of Damnation]]

*Italics are modifications*
### Numbers
- HP: 144 (17d8 + 68) => *264 (maximum 22d8 + 88)*
- Modified [[Vampire]]
- Base stats: *Proficiency Bonus +6 CR 20*
	- Str: 18
	- Dex: 18
	- Con: 18
	- Int: 17
	- Wis: 15
	- Cha: 18 => *20 (damnation)*
- Saves: Dex + Wis + Cha
- Skills: Perception + Stealth + *Athletics (**expertise**) + Deception + Arcana + Persuasion*
- Resistances: nonmagical weapons + necrotic
- To hit: +10 => *+12 (damnation)*
- AC: 16 => *20 (Plate Armor)*
	- *Note: MAX AC = 20(plate) + 2 (shield of faith) + 3 (wells) = 25*
### Spells
- 1/day each
- [Shadow of Moil](https://5e.tools/spells.html#shadow%20of%20moil_xge), Power Word Pain, Glibness, Plane Shift, Wall of Fire
### Items
- [[Spear of Damnation]] (Attunement)
- *+2 Plate Armor* -> [[Infernal Cuirass]]
### Notes (Fight)
- Cultists will have *shield of faith* cast on him: *+2 AC*
- **Blood well mechanic** during combat
	- **1 Well**: Additional legendary action and reaction
	- **2 Wells**: Necrotic Damage Life steal
	- **3 Wells**: +3 to AC and saves
- **Chalice lair actions**: On initiative count 20.
	- Choose a well of blood in the lair. The area surrounding it becomes enshrouded in the frigid air of the layer of [[Cania]]. Any creature in an area within 15ft. from that point gains vulnerability to fire damage while in the area until initiative count 20 of the next round.
	- Choose a well of blood in the lair. One of the souls is ripped from the churning well of energy and is transformed into a shadow allied with Lucius.
	- Choose a well of blood in the lair. A 10ft. radius 25ft. cylinder at the well's center writhes with the souls of the damned. When a creature first enters that area on a turn they must succeed on a DC 20 Constitution saving throw or suffer 6d10 necrotic damage.

```statblock
name: Lucius, Vampire Lord
size: Medium
type: Undead
subtype: Shapechanger
alignment: Lawful Evil
ac: 20 (Infernal Cuirass, +2 Plate Armor)
hp: 264 (22d8 + 88)
speed: 30ft.
stats: [18,18,18,17,15,20]
cr: 20
saves:
  - Dexterity: +10
  - Wisdom: +8
  - Charisma: +11
skillsaves:
  - Arcana: +9
  - Athletics: +17
  - Deception: +11
  - Medicine: +9
  - Perception: +8
  - Persuasion: +11
  - Stealth: +10
damage_resistances: nectrotic; bludgeoning, piercing and slashing from nonmagical weapons
damage_immunities: fire (Hellish Attunement)
languages: Common, Infernal, Sirkonian, Elvish
traits:
  - name: Shapechanger
  - name: Regeneration
    desc: Heal 20 HP at the start of his turn unless he was damaged by radiant damage since his last turn, or in sunlight or running water.
  - name: Spider Climb
  - name: Vampire Weaknesses
    desc: Running Water + Forbiddence + Sunlight + Stake to the Heart
  - name : Legendary Resistance (3/Day)
  - name: Misty Escape
  - name: Hurl Through Hell (1/day)
    desc: When Lucius hits a creature with an attack, he can cause that creature to disappear and hurtle through a nightmarish landscape. At the end of Lucius' next turn, the creature reappears in the space it previously occupied, or wherever is nearest, and suffers 10d10 psychic damage.
  - name: Spear of Damnation +2
    desc: Lucius wields the Spear of Damnation +2 magical item.

spells:
  - Lucius is a spellcaster with spell save DC 20 and a spell attack bonus of +12
  - At will: Swarm Step, Searing Lash (4d6)
  - Once per day each: Shadow of Moil*, Power Word Pain, Glibness, Plane Shift, Wall of Fire
  - "*Lucius casts this spell on himself at the start of combat"

actions:
  - name: Multiattack
    desc: Lucius makes one stike with Spear of Damnation +2, casts Searing Lash, and makes one claw attack. He can bite instead of using searing lash.
  - name: Spear of Damnation +2
    desc: Melee attack; +12 to hit, (1d8 + 6) piercing damage plus (2d8) necrotic damage.
  - name: Unarmed Strike
    desc: Melee attack; +10 to hit, 1d8 + 4 slashing damage.
  - name: Bite
    desc: +11 to hit, 5ft against a willing/grappled/incapacitated/restrained creature. (1d6 + 4) piercing plus (6d6) necrotic damage.
  - name: Charm
    desc: Lucius targets one humanoid he can see within 30 ft. of him. If the target can see Lucius, the target must succeed on a DC 18 Wisdom saving throw against this magic or be charmed.
  - name: Searing Lash
    desc: Melee Spell Attack. 30 ft. +12 to hit. 4d6 fire damage, and the target cannot regain hitpoints until the start of Lucius' next turn.
bonus_actions:
  - name: Swarm Step
    desc: Taking the form of smoking bats, Lucius teleports up to 30ft. to a space he can see. Creatures of his choice within 5ft. of him when he casts the spell must succeed on a DEX save or suffer 2d4 piercing damage as the bats ravage the area around him.
reactions:
  - name: Pursue Prey
    desc: When a creature moves out of Lucius' reach Lucius may use his reaction to perfectly follow that creature. Lucius may choose to remain within 5ft. of the creature during their movement, and may choose to stop following at any point during the move, so as to avoid being led into danger. While moving he does not provoke opportunity attacks. If the creature Lucius is pursuing makes it impossible for Lucius to follow, such as by teleporting or by taking flight, Lucius stops moving.
legendary_actions:
  - name: Move
    desc: Moves up to speed without provoking opportunity attacks.
  - name: Attack
    desc: Lucius makes one Unarmed Strike, one Searing Lash, or one Spear of Damnation +2 attack.
  - name: Wrathflight (Costs 2 Actions)
    desc: Lucius summons his bat wings and beats them. Each creature within 10ft. of him must succeed on a DC 19 dexterity saving throw or take 1d6 + 4 bludgeoning damage and be knocked prone. Lucius can then fly up to his movement speed. He loses his flying speed after finishing this movement.
```
