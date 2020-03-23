# Agit_SetTeleportLevel

```cpp - C++
void Agit_SetTeleportLevel(int teleportLevel);
```

### Examples

```cpp - C++

	Agit_SetTeleportLevel(2);

```

```cpp - C++

	if (OwnItemCount(talker, @adena) >= 10000)
	{
		DeleteItem1(talker, @adena, 10000);
		Agit_SetTeleportLevel(2);
		ShowPage(talker, fnAfterOptionAdd);
	}

```