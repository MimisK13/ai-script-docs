# AddAttackDesire
```cpp - C++
void AddAttackDesire(CSharedCreatureData* target, int actionMoveType, float value);
```

### Examples
```cpp - C++
AddAttackDesire(speller, 1, 50000);
```

```cpp - C++
if (GetLifeTime() > 7 && InMyTerritory(myself.sm))
{
	AddAttackDesire(creature, @AMT_MOVE_TO_TARGET, 200);
}
```
