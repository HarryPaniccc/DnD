Male [[Manticore]]s are the ones that shoot spines and females are the ones with scorpion stingers. The following blocks are a modified combination of the default manticore from the monster manual.
# Male Manticore
```statblock
name: Manticore (Male)
size: Large
type: Monstrosity (skirmisher)
alignment: Lawful Evil
ac: 14
hp: 68
hit_dice: 8d10 + 24
speed: 30ft., Fly 50ft.
stats: [17,16,17,7,12,8]
skillsaves:
  - Perception: +3
  - Stealth: +5
damage_resistances: Piercing, Slashing
senses: Darkvsion 60ft. Passve perception 11
languages: Common, mimicry trait
cr: 3
traits:
  - name: Agile Predator. 
    desc: When the manticore hits a creature with an attack on the manticore's turn, the manticore doesn't provoke opportunity attacks from that creature for the rest of that turn.
  - name: Mimicry.
    desc: The manticore can mimic any words or phrases they have heard in a language they understand. A creature who hears the speech can tell it is an imitation with a successful DC 10 Wisdom (Insight) check.
  - name: Tail Spike Regrowth.
    desc: The manticore has twenty-four tail spikes. Used spikes regrow when the manticore finishes a long rest.

actions:
  - name: Multiattack
    desc: The manticore makes three attacks; one with its bite and two with its claws, or three with its tail spikes
  - name: Bite
    desc: +5 to hit, (1d8 + 3) piercing damage
  - name: Claw
    desc: +5 to hit, (1d6 + 3) slashing damage
  - name: Tailspike
    desc: Ranged weapon attack +5 to hit 100/200 ft. (1d4 + 3) piercing damage plus (1d6) poison damage and the target must succeed a DC 13 Constitution saving throw or be poisoned until the end of their next turn.

bonus_actions:
  - name: Trumpeting Howl (1/Day)
    desc: Each enemy within 120 feet who can hear the manticore must succeed on a DC 13 Wisdom saving throw or be frightened of the manticore for 1 minute (save ends at end of turn). If the initial saving throw fails by 5 or more, a creature is also dazed while frightened in this way.
```

# Female Manticore

```statblock
name: Manticore (Female)
size: Large
type: Monstrosity (Skirmisher)
alignment: Chaotic Evil
ac: 15
hp: 130
hit_dice: 15d10 + 45
speed: 30ft., fly 50ft.
stats: [18,16,16,10,12,7]
skillsaves:
  - Perception: +3
  - Stealth: +5
damage_resistances: Piercing, Slashing
senses: darkvision 60ft., passive Perception 13
languages: Common, mimcry trait
cr: 6
traits:
  - name: Agile Predator.
    desc: When the manticore hits a creature with an attack on the manticore's turn, the manticore doesn't provoke opportunity attacks from that creature for the rest of that turn.
  - name: Mimicry.
    desc: The manticore can mimic any words or phrases they have heard in a language they understand. A creature who hears the speech can tell it is an imitation with a successful DC 10 Wisdom (Insight) check.

actions:
  - name: Multiattack
    desc: The manticore makes one bite and one claw attacks. It can replace one of these attacks with a poisoned sting attack.
  - name: Bite
    desc: +7 to hit, (1d8 + 4) piercing damage or (2d8 + 4) piercing damage if the target is frightened.
  - name: Claw
    desc: +7 to hit, (1d10 + 4) slashing damage, and the manticore can move the target up to 5 feet horizontally.
  - name: Poisoned Sting
    desc: Reach 10ft., +6 to hit, (1d6 + 4) piercing damage and the target must make a DC 14 Constitution saving throw. On a failure they suffer 2d10 poison damage and are poisoned for 1 minute, save ends at end of turn, and while they are poisoned in this way they are dazed. On success, the target takes half as much damage and isnt dazed.
bonus_actions:
  - name: Trumpeting Howl (1/Day)
    desc: Each enemy within 120 feet who can hear the manticore must succeed on a DC 14 Wisdom saving throw or be frightened of the manticore for 1 minute (save ends at end of turn). If the initial saving throw fails by 5 or more, a creature is also dazed while frightened in this way.
```




