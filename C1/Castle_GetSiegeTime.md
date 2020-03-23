# Castle_GetSiegeTime

```cpp - C++
const wchar_t* Castle_GetSiegeTime();
```

### Examples
```cpp - C++
EventHandler TALKED(talker, fhtml0)
{
	if (Castle_GetSiegeTime()!="")
	{
		////say("공성시간확인");	// Debug
		FHTML_SetFileName(fhtml0, fnHi);
		FHTML_SetStr(fhtml0, "next_siege", Castle_GetSiegeTime());
		ShowFHTML(talker, fhtml0);
	}
}
```
