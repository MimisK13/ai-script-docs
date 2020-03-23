# SendScriptEvent
```cpp - C++
void SendScriptEvent(CSharedCreatureData* to, int arg1, int arg2);
```

### Examples
```cpp - C++
if (OwnItemCount(talker, @q_portal_stone_1) > 0)
{
	DeleteItem1(talker, @q_portal_stone_1, 1);
	SendScriptEvent(c0, 0, 0);
	i1 = 179700 + Rand(700);
	i2 = 113800 + Rand(2100);
	InstantTeleport(talker, i1, i2, -7709);
}
```
