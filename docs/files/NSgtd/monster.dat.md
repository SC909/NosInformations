# Monster.dat

All informations we've found so far in Monster.dat :


File structure :

`Column Separator`: `\t`


FileElement Example
```
	VNUM	0
	NAME	zts1e
	LEVEL	16
	RACE	0	1
	ATTRIB	0	0	13	0	1	0
	HP/MP	0	0
	EXP	0	0
	PREATT	0	0	8	8	400
	SETTING	0	0	-1	0	0	0
	ETC	8	1	0	0	0	0	0	0
	PETINFO	1	10	0	50
	EFF	200	0	0
	ZSKILL	0	1	3	2	12	0	0
	WINFO	0	0	0
	WEAPON	16	1	0	0	0	11	-20
	AINFO	0	0
	ARMOR	16	0	-25	0	0
	SKILL	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0
	PARTNER	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0
	BASIC	0	0	4	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0
	CARD	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0
	MODE	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0
	ITEM	2000	9000	1	16	800	1	-1	0	0	-1	0	0	-1	0	0	-1	0	0	-1	0	0	-1	0	0	-1	0	0	-1	0	0	-1	0	0	-1	0	0	-1	0	0	-1	0	0	-1	0	0	-1	0	0	-1	0	0	-1	0	0	-1	0	0	-1	0	0
```


FileElement details
```
	VNUM	{monsterVnum:short}
	NAME	{monsterCodeName:string}
	LEVEL	{monsterLevel:byte}
	RACE	{monsterRace:byte}	{monsterRaceType:byte}
	ATTRIB	{monsterElement:byte}	{monsterElementRate:short}	{monsterResistanceFire:sbyte}	{monsterResistanceWater:sbyte}	{monsterResistanceLight:sbyte}	{monsterResistanceDark:sbyte}
	HP/MP	{monsterMaxHpBonus}	{monsterMaxMpBonus}
	EXP	{monsterXpBonus:int32}	{monsterJobXpBonus:int32}
	PREATT	{monsterIsHostile:bool}	0	{monsterNoticeRange:byte}	{monsterSpeed:byte}	{monsterRespawnTime:int32(milliseconds)}
	SETTING	0	0	-1	0	0	0
	ETC	{monsterETCVAL1}	1	0	0	0	0	0	0
	PETINFO	{tries}	{r_time} {remove}	{time}
	EFF	200	0	0
	ZSKILL	0	1	3	2	12	0	0
	WINFO	0	0	0
	WEAPON	16	1	0	0	0	11	-20
	AINFO	0	0
	ARMOR	16	0	-25	0	0
	SKILL	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0
	PARTNER	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0
	BASIC	0	0	4	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0
	CARD	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0
	MODE	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0
	ITEM	2000	9000	1	16	800	1	-1	0	0	-1	0	0	-1	0	0	-1	0	0	-1	0	0	-1	0	0	-1	0	0	-1	0	0	-1	0	0	-1	0	0	-1	0	0	-1	0	0	-1	0	0	-1	0	0	-1	0	0	-1	0	0	-1	0	0	-1	0	0
```

### monsterETCVAL1
`int` : 0b 0000 0000 0000 0000
```
cantWalk = monsterETCVAL1 & 0x1
canCollect = monsterETCVAL1 & 0x2
cantDebuff = monsterETCVAL1 & 0x4
canCatch = monsterETCVAL1 & 0x8
canRegenMp = monsterETCVAL1 & 0x400
cantVoke = monsterETCVAL1 & 0x800
boss-ish = monsterETCVAL1 & 0x‭40000000‬
cantTargetInfo = monsterETCVAL1 & 0x‭80000000‬
```

### PETINFO (thanks to SC909)
`Needs to be checked with other entities, it only works on collection entities (water well, ice flower, smelling grass, wheat)`
```
item_id = item required
amount = amount of required item
tries = amount of tries, successful and unsuccessful
r_time = time it takes to reset the number of tries
remove = amount of required items to remove
f_time = time it takes to collect
```
Last Update 5/19/2018
