# Castle_GetRawSiegeTime

```cpp - C++
int Castle_GetRawSiegeTime();
```

### Examples
```cpp - C++
if (Castle_GetRawSystemTime() - Castle_GetRawSiegeTime() < @s_sonic_storm32)
{
	//
}
else if (Castle_GetRawSystemTime() - Castle_GetRawSiegeTime() < 3600)
{
	if (myself.sm.flag < 1)
	{
		AddMoveToDesire(b02_x1, b02_y1, b02_z1, 100000000);
		myself.sm.flag = 1;
	}
}
```
