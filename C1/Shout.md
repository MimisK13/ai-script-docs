# Shout
```cpp - C++
int Shout(const wchar_t* script);
```

### Examples
```cpp - C++
EventHandler MY_DYING()
{
	if (ShoutMsg4 > 0 && Rand(100) < 30)
	{
		Shout(MakeFString(ShoutMsg4, "", "", "", "", ""));
	}
}
```
