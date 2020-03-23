# CreatePrivates

```cpp - C++
void CreatePrivates(const wchar_t* privates);
```

### Examples
```cpp - C++
CreatePrivates(Privates);
```

```cpp - C++
EventHandler CREATED()
{
	InstantTeleportInMyTerritory(51952, 111060, -1970, 200);
	AddTimerEx(2001, 10000);
	myself.sm.flag = 0;
	CreatePrivates(Privates);
}
```
