# InstantTeleportInMyTerritory

```cpp - C++
void InstantTeleportInMyTerritory(int x, int y, int z, int range);
```

### Examples
```cpp - C++
class gludio_mass_teleporter : mass_teleporter 
{
	handler:
		EventHandler TIMER_FIRED(myself) 
		{  
			SetTimerPeriodByTick(0);
			InstantTeleportInMyTerritory(-18099, 109297, -2475, 200);
			myself.i_ai0 = 0;
		}
}
```
