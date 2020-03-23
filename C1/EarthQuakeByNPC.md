# EarthQuakeByNPC

```cpp - C++
void EarthQuakeByNPC(CSharedCreatureData* creature, int force, int duration, int left, int right, int up, int down);
```

### Examples
```cpp - C++
if (reply == 0)
{
	SetDBValue(myself.sm, 0);
	EarthQuakeByNPC(myself.sm, 20, 10, 1, 0, 0, 0);
}
```
