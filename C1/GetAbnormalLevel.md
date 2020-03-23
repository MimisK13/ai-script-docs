# GetAbnormalLevel

```cpp - C++
int GetAbnormalLevel(CSharedCreatureData* creature, int abnormalType);
```

### Examples
```cpp - C++
if (Rand(100) < 10 && GetAbnormalLevel(attacker, Skill_GetAbnormalType(DeBuff)) <= 0)
{
	if (Skill_GetConsumeMP(DeBuff) < myself.sm.mp && Skill_GetConsumeHP(DeBuff) < myself.sm.hp && Skill_InReuseDelay(DeBuff) == @FALSE)
	{
		AddUseSkillDesire(attacker, DeBuff, @ST_ATTACK, @AMT_MOVE_TO_TARGET, 1000000);
	}
}
```
