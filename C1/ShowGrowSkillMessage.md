# ShowGrowSkillMessage
```cpp - C++
void ShowGrowSkillMessage(CSharedCreatureData* talker, int skillNameID, const wchar_t* afterGrow);
```

### Examples
```cpp - C++
EventHandler ONE_SKILL_SELECTED(talker, skill_name_id, need_quest)
{
	ShowGrowSkillMessage(talker, skill_name_id, "");
}
```
