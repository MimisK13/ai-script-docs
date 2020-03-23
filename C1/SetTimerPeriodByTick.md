# SetTimerPeriodByTick
```cpp - C++
void SetTimerPeriodByTick(int tick);
```

### Examples
```cpp - C++
EventHandler TIMER_FIRED(myself) 
{  
	SetTimerPeriodByTick(0);
	InstantTeleportInMyTerritory(-18099, 109297, -2475, 200);
	myself.i_ai0 = 0;
}
```
