# FHTML_SetFileName

```cpp - C++
void FHTML_SetFileName(CFHTML* html, const wchar_t* fileName);
```

### Examples
```cpp - C++
FHTML_SetFileName(fhtml0, fnOptionList);
```

```cpp - C++
if (level >= 2 * i1)
{
	FHTML_SetFileName(fhtml0, fnCurrentDmgzoneLevelHigher);
	FHTML_SetInt(fhtml0, "dmglevel", level / 2);
	ShowFHTML(talker, fhtml0);
}
```
