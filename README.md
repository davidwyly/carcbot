# Lumen PHP Framework

## Tentative Roadmap

### Bot Gamification Epic
| Option   | Description |
| -------- | ----------- |
| new      | spend points to get a new battlebot frame |
| rename   | rename your selected battlebot |
| market   | list what battlebot components are currently for sale on the marketplace |
| buy      | spend points to buy a battlebot component and add it to your inventory |
| sell     | get points to sell a battlebot component and remove it from your inventory |
| research | spend points for a chance to research a new battlebot component blueprint |
| craft    | using a blueprint, spend points to craft a component and add it to your inventory |
| attach   | attach a component to your battlebot and remove it from your inventory |
| detach   | detach a component to your battlebot and add it to your inventory |
| store    | store the selected battlebot |
| select   | select a stored bot |
| assault  | use a selected battlebot to assault an enemy camp |
| defend   | use a selected battlebot to defend against an enemy assault |
| duel     | duel another user's battlebot in the gambling ring |
| bet      | gamble points to bet on a particular battlebot winning a duel |

###
| Component Type | Description |
| -------------- | ----------- |
| Locomotion     | wheels, tracks, bipedal legs, quadruped legs, spider legs, water propeller, air rotor blades, jet engine, anti-grav thrusters, etc. |
| Engine         | gasoline, battery, hydrogen cells, fission reactor, fusion reactor, antimatter reactor, etc. |
| Armor          | plastic, kevlar, steel, ceramic, titanium, reactive, etc. |
| Melee Weapon   | overhead hammer, spinning hammer, pneumatic scythe, spring-loaded spikes, sawblade, chainsaw, pneumatic crusher, neurotoxin gas dispenser |
| Ranged Weapon  | ballistic pistol, ballistic shotgun, ballistic rifle, ballistic chaingun, laser pistol, laser shotgun, laser rifle, laser chaingun, plasma pistol, plasma shotgun, plasma rifle, plasma chaingun, railgun, grenade launcher, rocket launcher, missile launcher, mini-nuke, etc. |
| Sensors        | camera, nightvision camera, thermal camera, laser mapper, echolocator, heartbeat sensor, RADAR, SONAR, etc. |
| Computer       | X100, X200, X300, X400, X500, Basic AI, Advanced AI, Synaptic AI, Hypersynaptic AI, Sentient AI, etc. |
| Utility        | plasma cutter, grappling hook, drill, plastic explosives, etc. |

### Locomotion Type
| Name             | Size    | Speed | Land | Rocks | Sea | Air | Stairs | Jumps | Climbs |
| ---------------- | ------- | ----- | ---- | ----- | --- | --- | ------ | ----- | ------ |
| wheels           | 1, 2, 3 | 5     |  X   |       |     |     |        |       |        |
| tracks           | 1, 2, 3 | 3     |  X   |   X   |     |     |        |       |        |
| bipedal legs     | 1, 2    | 2     |  X   |   X   |     |     |  X     | X     |        |
| quadrupedal legs | 2, 3    | 3     |  X   |   X   |     |     |  X     | X     | X      |
| spider legs      | 1, 2, 3 | 4     |  X   |   X   |     |     |  X     | X     | X      |
| hoverfield       | 1, 2, 3 | 3     |  X   |       | X   |     |        |       |        |
| propeller        | 1, 2, 3 | 1     |      |       | X   |     |        |       |        |
| rotor blades     | 1, 2    | 12    |      |       |     | X   |        |       |        |
| jet thruster     | 2, 3    | 18    |      |       |     | X   |        |       |        |
| plasma thruster  | 2, 3    | 20    |      |       |     | X   |        |       |        |
