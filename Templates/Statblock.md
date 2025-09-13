# Version 2
> [!note] Statblock
> # Name
> *Size Type (Tag), Alignment*
> 
> ---
> **AC** # **Initiative** 
> **HP** 
> **Speed** # ft.
> 
> | | | MOD | SAVE | | | MOD | SAVE |
> | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
> | **STR** |  |  |  | **INT** |  |  |  | 
> | **DEX** |  |  |  | **WIS** |  |  |  |
> | **CON** |  |  |  | **CHA** |  |  |  |
> **Skills** 
> **Vulnerabilities**
> **Resistances** 
> **Immunities** 
> **Gear** 
> **Senses** 
> **Languages** 
> **CR**
> ---
> **Trait.** Trait stuff (this line break below behaves strange.)
>  ---
> >[!Danger] Actions
> >**Action.** Notes
>
> >[!Tip] Bonus Actions
> >**Bonus Action.** Notes




# Version 1
```statblock
image: [[Wikilink To Image]]
name: Name
size: Size
type: Type
subtype: Subtype
alignment: Alignment
ac: Armor Class
hp: Health
hit_dice: Hit Dice
speed: Speed
stats: [STR,DEX,CON,INT,CHA,WIS]
saves:
  - Ability: +save
skillsaves:
  - Skill: bonus
damage_vulnerabilities: string
damage_resistances: string
damage_immunities: string
condition_immunities: string
senses: string
languages: string
cr: 5
spells:
  - Is a nth level caster
  - 9th level (1 slot): Spell 1, spell 2
traits:
  - name: Trait 1
    desc: This monster has this trait
  - ...
actions:
  - name: Attack
    desc: 5ft, +3 to hit, 3d8 + 2 slashing
  - ...
legendary_actions:
  - name: Move
    desc: Moves legendarily
  - ...
bonus_actions:
  - name: Bonus Act
    desc: Time for bonus things
  - ...
reactions:
  - name: Moves
    desc: Moves reactively
  - ...
```


