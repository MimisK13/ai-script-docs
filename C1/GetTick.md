# GetTick

```cpp - C++
int GetTick();
```

### Examples
```cpp - C++
myself.i_ai1 = GetTick();
```

```cpp - C++
if (GetTick() - myself.i_ai1 > 15 * 60 * 1000)
{
	SetDBValue(myself.sm, 0);
	InstantTeleportInMyTerritory(80464, 152294, -3534, 100);
	InstantTeleport(myself.sm, 185708, 114298, -8221);
	RemoveAllAttackDesire();
}
```
