# Despawn
```cpp - C++
void Despawn();
```

### Examples
```cpp - C++
if(ask == -201 && reply == 1) 
{
	Despawn();
}
```

```cpp - C++
handler:
	EventHandler TALKED(talker, fhtml0) 
	{
		if (talker.builder_level > 0)
		{
			ShowPage(talker, fnHi);
			
		} else {
			
			Despawn();
		}
	}
```
