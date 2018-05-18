# Item.dat

All informations we've found so far in Item.dat :


File structure :

`FileElement Separator`: `#========================================================\n`

`Column Separator`: `\t`


FileElement Example
```
	VNUM	1	70
	NAME	zts3e
	INDEX	0	0	0	0	1	0
	TYPE	0	1
	FLAG	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0
	DATA	1	20	28	20	4	70	0	0	0	0	0	0	0	0	0	0	0	0	0	0
	BUFF	-1	80	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0
	LINEDESC	1
zts4e
	END
#========================================================
```

FileElement details :
```
	VNUM	{itemVnum}	{itemPrice}
	NAME	{itemCodeName}
	INDEX	0	0	0	0	1	0
        TYPE	{AttackType}	{ItemClass}
	FLAG	0	0	0	{IsSoldable}	{IsDroppable}	{IsTradable}	{IsBlocked}	{IsMinilandObject}	{IsHolder}	0	0	0	0	0	{IsColored}	0	0	0	{IsBuyWhitReputation}	{IsHeroic}	0	0	{IsLimited}
	DATA	1	20	28	20	4	70	0	0	0	0	0	0	0	0	0	0	0	0	0	0
	BUFF	-1	80	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0
	LINEDESC	1
zts4e
	END
#========================================================
```

```
More details :

{AttackType}
Attack Type 0 = Cac
Attack Type 1 = Distance/range
Attack type 2 = Magical

{ItemClass}
ItemClass 1 = Adventurer
ItemClass 2 = Swordman
ItemClass 4 = Archer
ItemClass 8 = Mage

```

Last Update 5/18/2018
