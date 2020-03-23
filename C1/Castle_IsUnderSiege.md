# Castle_IsUnderSiege

```cpp - C++
int Castle_IsUnderSiege();
```

### Examples
```cpp - C++
if (Castle_IsUnderSiege())
{
	ShowPage(talker, fnSiegeViewReport);
}
else
{
	ShowPage(talker, fnViewReport);
}
```

```cpp - C++
if (Castle_IsUnderSiege() && Castle_GetLifeControlLevel() == 0)
{
	ShowPage(talker, fnBrokenCtrlTower);
}
else
{
	ShowPage(talker, fnHi);
}
```
