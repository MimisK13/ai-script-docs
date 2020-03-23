# Skill_InReuseDelay
```cpp - C++
int Skill_InReuseDelay(int skillNameID);
```

### Examples
```cpp - C++
if (Skill_GetConsumeMP(MagicHeal) < myself.sm.mp && Skill_GetConsumeHP(MagicHeal) < myself.sm.hp && Skill_InReuseDelay(MagicHeal) == @FALSE)
{
	AddUseSkillDesire(victim, MagicHeal, @ST_HEAL, @AMT_MOVE_TO_TARGET, 1000000);
}
```
