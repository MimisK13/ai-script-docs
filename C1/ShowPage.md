# ShowPage
```cpp - C++
void ShowPage(CSharedCreatureData* to, const wchar_t* file);
```

### Examples
---
```cpp - C++
if (talker.karma > 0)
{
	ShowPage(talker, fnYouAreChaotic);
}
else
{
	ShowPage(talker, fnHi);
}
```
