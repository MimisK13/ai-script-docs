# GetControlTowerLevel

```cpp - C++
void GetControlTowerLevel(CSharedCreatureData* talker, const wchar_t* controlTowerName);
```

### Examples
```cpp - C++
if (Castle_IsUnderSiege())
{
	ShowPage(talker, fnSiegeStoppedFunction);
}
else if (GetCookie(talker, "dmgzone_num") == 1)
{
	GetControlTowerLevel(talker, dmgzonename1);
}
else if (GetCookie(talker, "dmgzone_num") == 2)
{
	GetControlTowerLevel(talker, dmgzonename2);
}
```
