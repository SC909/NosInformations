## Character Xp Algorithms
Here are all the character experience algorithms we know so far


### LevelXp & JobXp Algorithm
### XpBonus
- Player level 1~5 = *3 total LevelXp & JobXp
- Player level 6~18 = *2 total LevelXp & JobXp
- Player level 19+ = *1 total LevelXp & JobXp

- ((MonsterXp * LevelXp Penalty) * (bonuses +100)) * ((pets +100) *0.01) * 0.01 * XpBonus *LoD/Heat *Event
- ((MonsterJobXp * JobXp Penalty) * (bonuses +100)) * ((pets +100) *0.01) * 0.01 * XpBonus *LoD/Heat *Event

- Bonuses (Blessing of Ancelloan, Potions of Experience, Tarot Cards, Buffs, Wepon Shell...)
- Awakening Level (Book that says it gives 3% more exp, it gives 5%)
- Event (If it says +100% more EXP then it's *2)
- Glacernon Heat - Heat (When heat runs out LevelXp = *0.2, JobXp = *0.5)
- Dark Horn on Land Of Death - LoD (When appears for the first time, all experience *3)


### Pet & Partner (ONLY WORKS ON LevelXp)
Pet Alive +4,5%
Partner Alive +6,25%
Both Alive +20%

Pet Dead -5%
Parter Dead -15%
Both Dead -20%

Pet Alive Partner Dead -12%
Pet Dead Partner Alive 0%


### LevelXp Penalty
- Player level - Enemy level <= 5 { *1 }
- Player level - Enemy level <= 6 { *0.9 }
- Player level - Enemy level <= 7 { *0.7 }
- Player level - Enemy level <= 8 { *0.5 }
- Player level - Enemy level <= 9 { *0.3 }
- Player level - Enemy level <= 10 { *0.1 }


### JobXp & SPJobXp Penalty
- Enemy level >= 70 { *1 }
- Player level - Enemy level <= 5 { *1 }
- Player level - Enemy level <= 6 { *0.9 }
- Player level - Enemy level <= 7 { *0.7 }
- Player level - Enemy level <= 8 { *0.5 }
- Player level - Enemy level <= 9 { *0.3 }
- Player level - Enemy level <= 10 { *0.1 }


### SPjobXp Algorithm
- SPjobXp level 1~12 = *3 total SPjobXp
- SPjobXp level 13~20 = *2 total SPjobXp
- SPjobXp level 21+ = *1 total SPjobXp

While hunting monsters, an additional 50% of SPjobXp acquired will be added to JobXp.
Works from SPjob level 1 to level 20 (I don't remember if it was up to SPjob level 20)

### HeroLevelXp Algorithm
- (LevelXp /50) *1.5 = HeroXp


### FairyXp Algorithm
Fairy 0~40%
- (current fairy level * current fairy level) +50 

Fairy 41~79%
- ((current fairy level * current fairy level) + 50) *3
