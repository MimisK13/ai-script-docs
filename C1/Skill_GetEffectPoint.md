# Skill_GetEffectPoint
```cpp - C++
int Skill_GetEffectPoint(int skillNameID);
```

### Examples
```cpp - C++
if (Skill_GetEffectPoint(skill_name_id) > 0)
{
	AddAttackDesire(speller, @AMT_MOVE_TO_TARGET, Skill_GetEffectPoint(skill_name_id) / myself.sm.max_hp / 0.05 * 150);
}
```
