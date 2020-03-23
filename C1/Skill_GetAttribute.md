# Skill_GetAttribute
```cpp - C++
int Skill_GetAttribute(int skillNameID);
```

### Examples
```cpp - C++
if (Skill_GetAttribute(skill_name_id) == 12 && Rand(100) < 70 && InMyTerritory(attacker))
{
	if (Skill_GetConsumeMP(@s_queen_ant_strike) < myself.sm.mp && Skill_GetConsumeHP(@s_queen_ant_strike) < myself.sm.hp && Skill_InReuseDelay(@s_queen_ant_strike) == @FALSE)
	{
		AddUseSkillDesire(attacker, @s_queen_ant_strike, @ST_ATTACK, @AMT_MOVE_TO_TARGET, 1000000);
	}
}
```
