# Castle_SetMPRegen

```cpp - C++
void Castle_SetMPRegen(int mpRegen);
```

### Examples
```cpp - C++
if (OwnItemCount(talker, @adena) >= 600000)
{
	DeleteItem1(talker, @adena, 600000);
	Castle_SetMPRegen(2);
	ShowPage(talker, fnAfterOptionAdd);
}
```
