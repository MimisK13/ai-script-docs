# Castle_GetPledgeState

```cpp - C++
int Castle_GetPledgeState(CSharedCreatureData* talker);
```

### Examples
```cpp - C++
EventHandler SEE_CREATURE(creature)
{
	if (Castle_GetPledgeState(creature) != 2)
	{
		AddAttackDesire(creature, @AMT_STAND, 200);
	}
}
```
