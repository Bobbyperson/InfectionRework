# InfectionRework

putting all this just in case it goes public lol

## About

This is an overhaul of the Infection gamemode for Northstar. To put it lightly, the default infection gamemode is an unplayable mess. Infected can never win, there's no room for counter play, and it is overall very boring. This is mostly because survivors with grapple can get to unreachable positions, as the infected are equipped with only infinite stim and mgls. Additionally, survivors are encouraged to equip grapple and go to unreachable positions, because its not possible to not get killed by an infected player, as they have permanant stim and increased air acceleration.

A majority of the heavy lifting for this mod has been done by x3Karma.

## Changes

### Problem

Infected health is too weak, and doesn't scale well with low player counts.

### Solution

- Adjusted the health equation to give the first infected 200 health, which decreases as the amount of infected increases.

### Problem

Infected cannot win and there is no room for counter play

### Solution

- Removed infinite stim from infected
- Removed increased air acceleration from infected
- Gave infected a stim ability
- Gave infected a grapple ability

### Problem

Survivors hide/camp too much, which isn't fun for infected

### Solution

- For survivors to win, they must get in the evac ship at the end of the round (this isn't perfect as the evac ship can only hold 8, but is usually not an issue as this many survivors are not alive at this time)
- Infected can now spawn as variants, which include the seeker, shifter, boomer, and the ultra rare phase boomer

### Problem

When unskilled players get chosen as the first infected, they have a really hard time getting kills

### Solution

- As their death count increases, increase their maximum health

### Problem

When the first infected leaves, no one else can get infected.

### Solution

- When all infected leave the game, randomly choose another infected

### Miscellanous changes

- Fixed several crashes
- Added !hardmode for cocky survivors
- Use FFA spawns so survivors don't all spawn in the same place
- Survivors get a random boost every 5 kills, for shits and giggles
