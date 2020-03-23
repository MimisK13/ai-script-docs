# GetGlobalMap

```cpp - C++
int GetGlobalMap(int key);
```

### Examples
```cpp - C++
i0 = GetGlobalMap(1);
```

```cpp - C++
if (GM_ID != 0)
{
	i0 = GetGlobalMap(GM_ID);
	if (i0 == -1)
	{
		RegisterGlobalMap(GM_ID, GetIndexFromCreature(myself.sm));
	}
}
```