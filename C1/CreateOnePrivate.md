# CreateOnePrivate

```cpp - C++
void CreateOnePrivate(int privateClassId, const wchar_t* ai, int privateWeightPoint, int respawnTime);
```

### Examples
```cpp - C++
EventHandler PARTY_DIED(private)
{
	if (private != myself.sm)
	{
		CreateOnePrivate(private.class_id, private.ai, private.weight_point, private.respawn_time);
	}
}
```
