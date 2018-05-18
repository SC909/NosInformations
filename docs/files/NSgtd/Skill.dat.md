# Skill.dat

All informations we've found so far in Skill.dat :


File structure :

FileElement Separator: #========================================================\n

Column Separator: \t

FileElement Example
```
	VNUM	1
	NAME	zts1e
	TYPE	3	4	0	0	0	0
	COST	0	0	0
	LEVEL	0	0	0	0	0
	EFFECT	5001	0	14	0	11	0	0	0	0
	TARGET	0	0	0	0	0
	DATA	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0
	BASIC	0	0	0	0	0	0
	BASIC	1	0	0	0	0	0
	BASIC	2	0	0	0	0	0
	BASIC	3	0	0	0	0	0
	BASIC	4	0	0	0	0	0
	FCOMBO	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0
	CELL	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0
	Z_DESC	0

#=========================================================
```

FileElement details :

```
	VNUM	{SkillVnum}
	NAME	{SkillCodeName}
	TYPE	{SkillType}	{CastId}	{Class}	{Type}	{Element}	0
	COST	{CPCost}	{Price}	{ReputationMinimum}
	LEVEL	{LevelMinimum}	{MinimumAdventurerLevel}	{MinimumSwordmanLevel}	{MinimumArcherLevel}	{MinimumMagicianLevel}
	EFFECT	5001	{CastEffect}	{CastAnimation}	{Effect}	{AttackAnimation}	0	0	0	0
	TARGET	{TargetType}	{HitType}	{Range}	{TargetRange}	0
	DATA	{UpgradeSkill}	{UpgradeType}	0	0	{CastTime}	{Cooldown}	0	0	{MpCost}	0	{ItemVNum}	0	0	0	0
	BASIC	0	0	0	0	0	0
	BASIC	1	0	0	0	0	0
	BASIC	2	0	0	0	0	0
	BASIC	3	0	0	0	0	0
	BASIC	4	0	0	0	0	0
	FCOMBO	{IsCombo}	{FirstActivationHit}	{FirstComboAttackAnimation}	{FirstComboEffect}	{SecondActivationHit}	{SecondComboAttackAnimation}	{SecondComboEffect}	{ThirdActivationHit}	{ThirdComboAttackAnimation}	{ThirdComboEffect}	{FourthActivationHit}	{FourthComboAttackAnimation}	{FourthComboEffect}	{FifthActivationHit}	{FifthComboAttackAnimation}	{FifthComboEffect}
	CELL	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0	0
	Z_DESC	{LineDescription}

#=========================================================
```


Last Update 5/18/2018
