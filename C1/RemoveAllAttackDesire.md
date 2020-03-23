# RemoveAllAttackDesire
```cpp - C++
void RemoveAllAttackDesire();
```

### Examples
```cpp - C++
EventHandler OUT_OF_TERRITORY()
{
	RemoveAllAttackDesire();
}
```

```cpp - C++
if (InMyTerritory(myself.sm) == 0 && myself.p_state != 3) 
{
	InstantTeleport(myself.sm, myself.start_x, myself.start_y, myself.start_z);
	RemoveAllAttackDesire();
}
```
