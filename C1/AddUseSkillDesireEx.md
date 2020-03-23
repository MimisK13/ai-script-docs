# AddUseSkillDesireEx

```cpp - C++
void AddUseSkillDesireEx(uint32_t targetSID, int skillNameID, int skillType, int actionMoveType, bool force, float value);
```

### Examples

```cpp - C++
{
	AddUseSkillDesireEx(i0, 1044225, @ST_ATTACK, reply, ask, 1000000);
}
```

```cpp - C++
{
	c0 = GetCreatureFromIndex(i0);
	if (c0)
	{
		if (Skill_GetConsumeMP(DDMagic) < myself.sm.mp && Skill_GetConsumeHP(DDMagic) < myself.sm.hp && Skill_InReuseDelay(DDMagic) == @FALSE)
		{
			AddUseSkillDesireEx(myself.master.target_id, DDMagic, @ST_ATTACK, reply, ask, 1000000);
		}
	}
}
```
