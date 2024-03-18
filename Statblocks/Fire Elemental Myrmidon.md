```statblock
name: Fire Elemental Myrmidon
size: Medium
type: Elemental
alignment: Neutral
ac: 18
hp: 123
hit_dice: 19d8
speed: 40 ft.
stats: [13,18,15,9,10,10]
damage_resistances: bludgeoning, piercing, and slashing from nonmagical attacks
damage_immunities: fire, poison
condition_immunities: paralyzed, petrified, poisoned, prone
senses: darkvision 60ft., passive Perception 10
languages: Ignan, Sirkonian
cr: 7
traits:
  - name: Illumination
    desc: The myrmidon sheds bright light in a 20-foot radius and dim light in a 40-foot radius
  - name: Water Susceptibility
    desc: Take 1d4 cold damage for every 5 ft. moved in 1ft. + deep water
actions:
  - name: Multiattack
    desc: Make 3 longsword attacks
  - name: Longsword
    desc: 5ft. reach, +7 to hit, (1d6 + 4) force damage
  - name: Fiery Strikes (Recharge 6)
    desc: Multiattack but each hit does 2d6 more fire damage
```


# Kenifria Variant
123 HP
```statblock
creature: Fire Elemental Myrmidon
name: Kenifrian Elemental Myrmidon
traits+:
  - name: Fire Shield
    desc: When bloodied (HP<61), deal 2d8 fire damage to anyone who deals melee damage in 5ft
```