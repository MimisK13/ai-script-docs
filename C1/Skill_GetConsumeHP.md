# Skill_GetConsumeHP
```cpp - C++
int Skill_GetConsumeHP(int skillNameID);
```

### Examples
```cpp - C++
if (Skill_GetConsumeMP(@s_siege_hammer1) < myself.sm.mp && Skill_GetConsumeHP(@s_siege_hammer1) < myself.sm.hp && Skill_InReuseDelay(@s_siege_hammer1) == @FALSE)
{
	AddUseSkillDesireEx(i0, 1044225, @ST_ATTACK, reply, ask, 1000000);
}
```
