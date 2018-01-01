# Equipment Materials and other Modifiers

Quality and Material cost modifiers are additive. For example, an item that is expert-crafted green steel will have a cost modifier of x9.

If the base item type has a cost of 0, then it is considered to have a base cost of 1 gold for material and modification purposes.

## Quality Modifiers

Quality modifiers add an amount of cost that is relative to the base cost of the equipment. They only provide benefits if the user possesses certain skill requirements.

| Quality                | Cost Mod | Requirement               | Notes |
| ---                    | ---      | ---                       | ---   |
| Expert-Crafted Armor   | + x5     | Armor Training 2          | +1 AC
| Master-Crafted Armor   | + x10    | Armor Training 5          | +2 AC
| Custom-Fitted Armor    | + x20    | Armor Training 10         | +3 AC
| Expert-Crafted Shield  | + x5     | Armor Training 4          | +1 AC
| Master-Crafted Shield  | + x10    | Armor Training 10         | +2 AC
| Custom-Fitted Shield   | + x20    | Armor Training 20         | +3 AC
| Expert-Crafted Weapon  | + x5     | Melee/Ranged Fighting 2   | +1 accuracy and damage
| Master-Crafted Weapon  | + x10    | Melee/Ranged Fighting 5   | +2 accuracy and damage
| Custom-Grip-and-Balance Weapon | + x20 | Melee/Ranged Fighting 10 | +3 accuracy and damage

## Material Modifiers

Material modifiers add an amount of cost that is relative to the base cost of the equipment. The default material is assumed to be Common Steel.

| Material              | Cost Mod  | Weight Mod | Armor AC       | Weapon Mod                       | Special |
| ---                   | ---       | ---        | ---            | ---                              | ---     |
| Bronze                | halved    | none       | -1 AC          | -1 accuracy and damage           |         |
| Common Steel          | no mod    | no mod     | no mod         | no change                        | the default material |
| Exotic Steel          | + x2      | +1         | +1 AC          | +1 accuracy and damage           |         |
| Ironwood              | + x4      | none       | none           | none                             | not metal
| Meteoric Cold-Forged  | + x4      | none       | none           | none                             | not metal
| Green Steel           | + x4      | +1         | +1 AC (magic)  | +1 accuracy and damage (magic)   | functions equally in all planes that have magic |
| Silvered Steel        | + x5      | +1         | +1 AC (silver) | +1 accuracy and damage (silver)  |         |
| Dwarven Graysteel     | + x25     | +2         | +2 AC          | +2 accuracy and damage           |         |
| Elven Bluesteel       | + x50     | +1         | +2 AC          | +2 accuracy and damage           | +1 against evil-crafted humanoids |
| Orichalcum            | + x100    | +3         | +3 AC          | +3 accuracy and damage           |         |
| Graphite Composite    | + x120    | +1         | +2 AC          | +2 accuracy and damage           | not metal
| Carbon Fiber          | + x200    | none       | +2 AC          | +2 accuracy and damage           | not metal
| Konkressite           | + x200    | +4         | +4 AC          | +4 accuracy and damage           |         |
| Slammite              | + x250    | +5         | +5 AC          | +5 accuracy and damage           |         |
| Burned Miasma Ceramic | + x350    | +5         | +5 AC          | +5 accuracy and damage           | not metal
| Validium              | + x400    | +6         | +6 AC          | +6 accuracy and damage           |         |
| Ormu Carapace         | + x450    | +6         | +6 AC          | +6 accuracy and damage           | not metal
| Dragonbone            | + x500    | +7         | +7 AC          | +7 accuracy and damage           | not metal
| Mithril               | + x1,000  | +2         | +6 AC          | +6 accuracy and damage           |         |
| Adamantine            | + x2,500  | +3         | +7 AC          | +7 accuracy and damage           |         |
| Forged Terracore      | + x5,000  | +8         | +8 AC          | +8 accuracy and damage           |         |
| Forged Starcore       | + x10,000 | +9         | +9 AC          | +9 accuracy and damage           |         |
| Black-Hole-Forged     | + x50,000 | +10        | +10 AC         | +10 accuracy and damage          |         |

## Equipment Reinforcement Modifiers

Reinforcement adds a flat cost to the item, after all other modifiers are applied. In many cases, it may be cheaper to reinforce an old piece of equipment rather than get a new one crafted from superior materials. Reinforcement can be either magical or psionic - a distinction that initially matters little, but becomes more important as you face increasingly deadly foes of various sorts.

Weapons gain a bonus of +1 to accuracy and damage for each point of reinforcement.

Throwing weapons are reinforced in batches of 10, and gain a bonus equal to four times their reinforcement value to be reusable. For example, reinforcing a Throwing Axe to +2 gives it a bonus of +8 to be reusable.

Ammunition is reinforced in batches of 20, and gains a bonus equal to double its reinforcement value to be reusable. For example, reinforcing an arrow to +2 gives it a bonus of +4 to be reusable. The bonus is also applied to visually searching for ammunition with the help of *Detect Magic*, *Detect Psionics*, or similar power, depending on whether the ammunition was magically or psionically reinforced.

Armor gains 1 AC for each point of reinforcement.

Other wearable gear, such as shields, rings, amulets, bracers, and robes can be reinforced as armor for double the gold value. For example, the gold value of Robes of Armor +1 is 2,000 gold.

- +1: +1,000 gold value
- +2: +4,000 gold value
- +3: +9,000 gold value
- +4: +16,000 gold value
- +5: +25,000 gold value
- +6: +36,000 gold value
- +7: +49,000 gold value
- +8: +64,000 gold value
- +9: +81,000 gold value
- +10: +100,000 gold value

### Crafting Equipment Reinforcements

The crafter's experience level must be at least triple the desired reinforcement level. The crafter must use up half of the gold cost in reinforcement materials. The skill check to craft is an extended check, with a difficulty of 100 x Reinforcement Level and a time scale of one roll per day.

## Weapon Infusion Modifiers

Weapon Infusions can only be applied to weapons, and other objects that can be used for attacking. If applied to a natural weapon, then the infusion only lasts 7 days.

Each infusion has a flat cost of 5,000 gold.

- Fire: The weapon damage's element is changed to fire.
- Blessed: The weapon damage's element is changed to true sunlight. The weapon now always uses Wisdom for accuracy and damage.
- Blood: On an attack accuracy roll of a natural 19 or 20, the target starts bleeding. This only applies to targets that are capable of bleeding.
- Crystal: The weapon damage's element is changed to magic. The weapon now always uses Intelligence for accuracy and damage.
- Dark: The weapon damage's element is changed to darkness. It also drains 1 hit point on every damaging attack.
- Deep: The weapon damage's element is changed to darkness. It gains a bonus of +1 to damage.
- Heavy: The weapon requires (16 + Reinforcement) Strength in order to use. The weapon now always uses Strength for accuracy and damage. For each Strength bonus at +4 and higher, an additional point of bonus is gained.
- Hollow: The weapon requires (16 + Reinforcement) Charisma in order to use. The weapon now always uses Charisma for accuracy and damage. For each Charisma bonus at +4 and higher, an additional point of bonus is gained.
- Lightning: The weapon damage's element is changed to electricity.
- Poison: The weapon damage's element is changed to poison.
- Raw: The weapon gains +5 accuracy and damage. It no longer uses any attributes for accuracy or damage, nor can it be reinforced.
- Refined: The average of the user's Strength & Dexterity are used for attack accuracy and damage.
- Sharp: The weapon requires (16 + Reinforcement) Dexterity in order to use. The weapon now always uses Dexterity for accuracy and damage. For each Dexterity bonus at +4 and higher, an additional point of bonus is gained.
- Simple: The weapon has a penalty of -3 to accuracy and damage. It increases caster experience level by an amount equal to its Reinforcement number.

### Crafting Weapon Infusions

The crafter must have at least 10 experience levels, and must provide half of the gold cost in infusion materials. The skill check to infuse is an extended check, with a difficulty of 200 and a time scale of one roll per day.
