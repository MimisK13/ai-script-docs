# OwnItemCount

```cpp - C++
int OwnItemCount(CSharedCreatureData* creature, int itemClassID);
```

### Examples
```cpp - C++
if (OwnItemCount(talker, @adena) >= 10000)
{
	DeleteItem1(talker, @adena, 10000);
	Agit_SetTeleportLevel(2);
	ShowPage(talker, fnAfterOptionAdd);
}
```
