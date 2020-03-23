# InMyTerritory

```cpp - C++
int InMyTerritory(CSharedCreatureData* creature);
```

### Examples
```cpp - C++
EventHandler SEE_CREATURE(creature, myself) 
{
	if ((GetLifeTime() > 0)  &&  InMyTerritory(myself.sm)) 
	{
		AddAttackDesire(creature, 1, 200);
	}
}
```
