# Skill_GetConsumeMP
```cpp - C++
int Skill_GetConsumeMP(int skillNameID);
```

### Examples
```cpp - C++
if (Skill_GetConsumeMP(@s_partisan_flame) < myself.sm.mp && Skill_GetConsumeHP(@s_partisan_flame) < myself.sm.hp && Skill_InReuseDelay(@s_partisan_flame) == @FALSE)
{
	AddUseSkillDesire(creature, @s_partisan_flame, @ST_ATTACK, @AMT_STAND, 1000000);
}
```
