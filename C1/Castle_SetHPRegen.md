# Castle_SetHPRegen

```cpp - C++
void Castle_SetHPRegen(int hpRegen);
```

### Examples
```cpp - C++
if (OwnItemCount(talker, @adena) >= 100000)
{
	DeleteItem1(talker, @adena, 100000);
	Castle_SetHPRegen(1);
	ShowPage(talker, fnAfterOptionAdd);
}
```
