# Castle_GetLifeControlLevel

```cpp - C++
int Castle_GetLifeControlLevel();
```

### Examples

```cpp - C++

	if (Castle_IsUnderSiege() && Castle_GetLifeControlLevel() == 0)
	{
		AddTimerEx(1001, 480000);
	}
	
```
