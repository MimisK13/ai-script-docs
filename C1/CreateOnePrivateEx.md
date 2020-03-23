# CreateOnePrivateEx

```cpp - C++
int CreateOnePrivateEx(int privateClassId, const wchar_t* ai, int privateWeightPoint, int respawnTime, int x, int y, int z, int direction, int arg_9, int arg_10);
```

### Examples
```cpp - C++
if (HavePet == 1)
{
	CreateOnePrivateEx(silhouette, "pet_around_pet_manager", 0, 0, FloatToInt(myself.sm.x + 10), FloatToInt(myself.sm.y + 10), FloatToInt(myself.sm.z), 0, 0, 0);
}
```
