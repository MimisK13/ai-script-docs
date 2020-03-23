# SpecialCamera
```cpp - C++
void SpecialCamera(CSharedCreatureData* to, int force, int angle1, int angle2, int time, int range, int duration);
```

### Examples
```cpp - C++
EventHandler MY_DYING()
{
	SpecialCamera(myself.sm, 1200, 20, -10, 0, 10000, 13000);
	SetDBValue(myself.sm, 0);
	UnregisterGlobalMap(GM_ID);
}
```
