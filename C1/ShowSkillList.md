# ShowSkillList
```cpp - C++
void ShowSkillList(CSharedCreatureData* to, const wchar_t* byePage);
```

### Examples
```cpp - C++
if (talker.race == myself.sm.race && IsInCategory(@fighter_group, talker.occupation))
{
	ShowSkillList(talker, "");
}
else
{
	ShowPage(talker, fnClassMismatch);
}
```
