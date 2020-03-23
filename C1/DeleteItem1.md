# DeleteItem1

```cpp - C++
int DeleteItem1(CSharedCreatureData* talker, int itemClassID, int count);
```

### Examples
```cpp - C++
DeleteItem1(talker, @adena, 10000);
```

```cpp - C++
if(OwnItemCount(talker, ItemNeeded) != 0)	
{
	DeleteItem1(talker, ItemNeeded, 1);
	InstantTeleport(talker, -80684, 149770, -3043);

}
```
