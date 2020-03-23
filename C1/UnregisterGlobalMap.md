# UnregisterGlobalMap
```cpp - C++
int UnregisterGlobalMap(int key);
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
